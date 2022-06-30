---
layout: home
title:  "About"
---

## Projects

- [Open Acidification Project](https://open-acidification.github.io/)
  - Assisted in mentoring Walla Walla University Senior Projects in 2019, 2020, 2021.
- [Submitty](https://submitty.org/)
  - Assisted in mentoring a Google Summer Of Code student on the Submitty API in 2019.
- [Apache AsterixDB](https://asterixdb.apache.org/)
  - Mentored a Google Summer Of Code students in 2019.
  - Check out the [research](http://asterix.ics.uci.edu/) aspect of the project.
  - My improvements to Apache VXQuery require a few changes to Hyracks which executes the parallel job.
  - My current research in scalable interval joins has also make improvements to the code base.
    More changes are in the pipeline pending the results of the scale and speed up tests.
  - A complete list of [commits](https://github.com/apache/asterixdb/commits?author=prestoncarman) I have made to the project.
- [Apache VXQuery](https://vxquery.apache.org/)
  - Mentored a Google Summer Of Code students in 2015, 2016, and 2017.
  - Extended the initial single processor XQuery engine to run in a distributed environment.
  - Performed scale up and speed up tests and used this information to improve the distributed processing.
  - Mentored three students through Google Summer of Code and assisted with four more student projects.
    Their projects include adding JSONiq extension for XQuery and HDFS support.
  - A complete list of [commits](https://github.com/apache/vxquery/commits?author=prestoncarman) I have made to the project.

## Teaching Posts

<ul>
{% for teaching_post in site.teaching %}
     <li><a href="{{ teaching_post.url }}">
      {{ teaching_post.title }}
    </a></li>
{% endfor %}
</ul>
