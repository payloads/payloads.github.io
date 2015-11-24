---
layout: default
title: 「动次打次」
permalink: /archive.html
archive: 1
---

<div class="mod" id="bulletin-9314111">
    <div class="hd">     
    <h2><span>{{ page.title }} </span></h2>
    </div>
<div class="bd">
{% for post in site.posts  %}
<div class="item-entry">
    <div class="title">
        ❤ <a title="{{ post.title }}" href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a> - {{ post.date | date_to_string }}
    </div>
    <!--div class="datetime">{{ post.date | date_to_string }}</div> 
<div class="summary" id="note_511774977_short">
        <div class="ll"><a href="http://www.douban.com/note/511774977/">
        <img src="/static/img/archive.jpg" alt=""></a></div>
       {{ post.excerpt | strip_html | strip_newlines | truncate: 160 }}
</div>
    </div-->
    {% endfor %}
</div>
</div>