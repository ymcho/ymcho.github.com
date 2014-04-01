---
layout: page
title: About Me
tagline:
---
{% include JB/setup %}

### 자주쓰는 언어
 
 - web(javascript, jquery, css, html, actionscript)
 - s/w(Objective C#)

   
### SNS
  
 - Twitter : [@ingUser](https://twitter.com/ingUser)  
 - Facebook : [yongmini](https://www.facebook.com/yongmini)  
 - blog : [ymCho'blog](http://ymcho.github.io/)  

  
### Posts
 
<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>


