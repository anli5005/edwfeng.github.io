---
title: Notes
description: School Stuff
type: main
permalink: /notes/
---
{% include title.html %}

<head>
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
    <style>
    .desc {
        position: relative; padding-bottom: 75%; height: 0; overflow: hidden;
    }
    .desc iframe {
        position: absolute; top:0; left: 0; width: 100%; height: 100%;
    }
    </style>
    <script>
    $(document).ready(function() {
        $("input[name$='calView']").click(function() {
            var test = $(this).val();

            $("div.desc").hide();
            $("#calView" + test).show();
        });
    });
    </script>
</head>

<div id="radio selector">
    <input type="radio" name="calView" checked="checked" value="1"/>Month View<br />
    <input type="radio" name="calView" value="2" />Agenda View

    <div id="calView1" class="desc">
        <iframe src="https://calendar.google.com/calendar/embed?showTitle=0&amp;showNav=0&amp;showPrint=0&amp;showTabs=0&amp;showTz=0&amp;height=600&amp;wkst=1&amp;bgcolor=%23FFFFFF&amp;src=aivjikt86are7eviujkepljbro%40group.calendar.google.com&amp;color=%231B887A&amp;src=ohem2scphu75bjaljk4lnmi3h0%40group.calendar.google.com&amp;color=%2342104A&amp;src=f4k56121gcgd1udm6sir7duass%40group.calendar.google.com&amp;color=%23865A5A&amp;src=ndbhrl0us690iaq8v57a8t6elk%40group.calendar.google.com&amp;color=%2328754E&amp;ctz=America%2FNew_York" style="border-width:0" width="800" height="600" frameborder="0" scrolling="no"></iframe></div>
    <div id="calView2" class="desc" style="display: none;">
        <iframe src="https://calendar.google.com/calendar/embed?showTitle=0&amp;showNav=0&amp;showPrint=0&amp;showTabs=0&amp;showTz=0&amp;mode=AGENDA&amp;height=600&amp;wkst=1&amp;bgcolor=%23FFFFFF&amp;src=aivjikt86are7eviujkepljbro%40group.calendar.google.com&amp;color=%231B887A&amp;src=ohem2scphu75bjaljk4lnmi3h0%40group.calendar.google.com&amp;color=%2342104A&amp;src=f4k56121gcgd1udm6sir7duass%40group.calendar.google.com&amp;color=%23865A5A&amp;src=ndbhrl0us690iaq8v57a8t6elk%40group.calendar.google.com&amp;color=%2328754E&amp;ctz=America%2FNew_York" style="border-width:0" width="800" height="600" frameborder="0" scrolling="no"></iframe></div>
</div>

To view a specific group of notes, click the top right dropdown and select the option you would like to view.
