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

**Note:** this class was called **"egDefaultBtn"** and it has been renamed. 


This button is the default button for the site. It should be used in situations that require the user to perform an action. Ideally, there should only be one default button per page. 

<center><a class="itaDefaultBtn">Search</a></center> 

{% highlight html %}
{% raw %}
<a class="itaDefaultBtn">Search</a>
{% endraw %}
{% endhighlight %}

{% highlight css %}

export-long.css

.itaDefaultBtn{
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
.itaDefaultBtn:hover {
background-color: #3D8D3D;  
color: #ffffff;
text-decoration: none;
}
{% endhighlight %}

#### Export.gov Alternative Button.

This is the alternative to the default button. This button should be used when the default button is already visible on the page and/or clicking the button is not a required action. 

<center><a class="itaAltBtn">Join Group</a></center> 

{% highlight html %}
{% raw %}
<a class="itaAltBtn">Join Group</a>
{% endraw %}
{% endhighlight %}

{% highlight css %}

export-long.css

.itaAltBtn{
font-size: .90em;
font-weight: bold;
color: #4cae4c;
background-color: #ffffff;
border: 2px solid #4cae4c;
border-radius: 2px;
display: inline-block;
padding: 3px 15px 1px 15px;
height: 30px;
}	
.itaAltBtn:hover {
background-color: #3D8D3D;	
border: 2px solid #3D8D3D;
color: #ffffff;
text-decoration: none;
}
{% endhighlight %}

#### Export.gov Search Large Button.

**Note:** the formatting of the search box is important, in ordert to achieve a snug fit.  

This button was specifically created for a landing page where a search box is the focal point. One example is The Market Intelligence Tool.

<form>
<input type="text" class="form-control input-lg" style="width: 50%; display: inline-block; height: 46px; padding: 10px 16px; font-size: 18px; line-height: 1.33333; border-radius: 6px; border-top-right-radius: 0; border-bottom-right-radius: 0;" placeholder="Keyword" name="q" data-reactid=".0.0.1.0.1.0"><span class="input-group-btn" data-reactid=".0.0.1.0.1.1"><button class="srchExportBtn" data-reactid=".0.0.1.0.1.1.0"><i class="fa fa-search" data-reactid=".0.0.1.0.1.1.0.0"></i></button></span>
</form>

{% highlight html %}
{% raw %}
<button class="srchExportBtn"><i class="fa fa-search"></i></button>
{% endraw %}
{% endhighlight %}

{% highlight css %}

global.css

.srchExportBtn{
font-size: 1.5em;
font-weight: bold;
color: #ffffff;
padding: 4px 12px 10px 12px;
background-color: #4cae4c;
border: 1px solid #3D8D3D;
border-radius: 1px 4px 4px 1px;
display: inline-block;
height: 46px;
}	
.srchExportBtn:hover {
background-color: #3D8D3D;	
}
{% endhighlight %}



