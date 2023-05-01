---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: main
---

<h1 style="text-align: center;">Our Portfolio</h1>

{% for item in site.data.projects.navigation %}

<h2>{{ item.title }}</h2>
<p>{{ item.description }}</p>
<a href="{{ item.url }}">{{ item.url }}</a>
<hr/>
{% endfor %}

<!-- <ul>
  <li>I have started working at <a href="https://www.educative.io/">educative.io</a> as Software Engineer.</li>
  <li>Our <b>paper</b> on 5G Low Latency and Consistent Control Plane has been accepted at SigComm 2020, NYC.</li>
  <li>Our <b>poster</b> on Edge based Cellular Networks has been accepted at SigComm 2019, Beijing.</li>
</ul> -->
