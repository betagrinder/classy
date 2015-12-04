---
layout: post
title: Export.gov Specific Styles
excerpt: "Find the styles you need for your page"
tags: [sample post, code, highlighting]
modified: 2015-12-03
comments: true
---

Below are the styles for Export.gov and how they will appear on your webpage. 


### Buttons

#### Export.gov Default Button.

This button is the default button for the site. It should be used in situations that require the user to perform an action. Ideally, there should only be one default button per page. <br><br><center><a class="egDefaultBtn">Search</a></center> 



{% highlight css %}
.egDefaultBtn{
font-size: 1.08em;
font-weight: bold;
color: #ffffff;
padding: 2px 8px 1px 8px;
background-color: #4cae4c;
border: 1px solid #3D8D3D;
border-radius: 2px;
display: inline-block;
height: 30px;
text-decoration: none;
} 
.egDefaultBtn:hover {
background-color: #3D8D3D;  
color: #ffffff;
text-decoration: none;
}
{% endhighlight %}

{% highlight html %}
{% raw %}
<a class="egDefaultBtn">Search</a>
{% endraw %}
{% endhighlight %}

