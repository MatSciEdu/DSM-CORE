---
layout: default
title: Resource Collection
---

<body>
  <h1>Index of Resources</h1>
  
  <ul>
    {% for resource in site.resources %}
    <li>
      <a href="{{ site.baseurl | escape }}{{resource.url}}" style="font-size: larger"><b>{{resource.title}}</b></a><br>
      <b>Author:</b> {{resource.author}}<br>
      <b>Content Type:</b> {{resource.type | array_to_sentence_string }}<br>
      <b>Content Length:</b> {{resource.length}}<br>
      <b>Content Audience:</b> {{resource.audience}}<br>
      <b>Content Topics:</b> {{resource.topics | array_to_sentence_string }}<br>
      <b>Last Updated:</b> {{resource.date | date: "%Y-%m-%d"}}<br>
    </li>
    {% endfor %}
  </ul>
</body>

***
### [Return to Collection](https://MatSciEdu.github.io/DSM-CORE/resource-collection)
### [Return Home](https://MatSciEdu.github.io/DSM-CORE)
