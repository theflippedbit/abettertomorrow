---
layout: default
---

<link rel="stylesheet" type="text/css" href="https://cdn.datatables.net/1.11.2/css/jquery.dataTables.css">

<table id="companies" class="display" style="width:100%">
    <thead>
        <tr>
            <th>Company</th>
            <th>Category</th>
            <th>Tech Stack</th>
            <th>Country</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td><a href="https://www.spacex.com/careers" target="_blank">SpaceX</a></td>
            <td>Space</td>
            <td>Python, C#.NET, Go, Java, Angular, React</td>
            <td>United States</td>
        </tr>
        <tr>
            <td><a href="https://boweryfarming.com/farm-careers" target="_blank">Bowery Farming</a></td>
            <td>Farming, Robotics</td>
            <td>Elixir, Phoenix, Rails, Node, C, C++, Nerves, Python, Vue.js, React, Angular</td>
            <td>United States</td>
        </tr>
    </tbody>
</table>


<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.6.0/jquery.min.js"></script>
<script type="text/javascript" charset="utf8" src="https://cdn.datatables.net/1.11.2/js/jquery.dataTables.js"></script>
<script src="{{ base.url | prepend: site.url }}/assets/js/index.js"></script>
