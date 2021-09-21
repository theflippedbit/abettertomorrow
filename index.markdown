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
        <tr>
            <td><a href="https://www.khanacademy.org/careers" target="_blank">Khan Academy</a></td>
            <td>Education</td>
            <td>JavaScript, React, Redux, GraphQL, Python, Go</td>
            <td>United States, Canada, India</td>
        </tr>
        <tr>
            <td><a href="https://goforward.com/jobs" target="_blank">Forward</a></td>
            <td>Health</td>
            <td>Not specific</td>
            <td>United States</td>
        </tr>
        <tr>
            <td><a href="https://web.noom.com/careers/" target="_blank">Noom</a></td>
            <td>Health</td>
            <td>Java, Python, Go, Django, React, SQL</td>
            <td>United States, Germany, Canada, United Kingdom</td>
        </tr>
    </tbody>
</table>


<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.6.0/jquery.min.js"></script>
<script type="text/javascript" charset="utf8" src="https://cdn.datatables.net/1.11.2/js/jquery.dataTables.js"></script>
<script src="{{ base.url | prepend: site.url }}/assets/js/index.js"></script>
