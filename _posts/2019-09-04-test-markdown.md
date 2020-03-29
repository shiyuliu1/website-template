---
layout: post
title: Test markdown
subtitle: Each post also has a subtitle
gh-repo: daattali/beautiful-jekyll
gh-badge: [star, fork, follow]
tags: [test]
comments: true
---

You can write regular [markdown](http://markdowntutorial.com/) here and Jekyll will automatically convert it to a nice webpage.  I strongly encourage you to [take 5 minutes to learn how to write in markdown](http://markdowntutorial.com/) - it'll teach you how to transform regular text into bold/italics/headings/tables/etc.

**Here is some bold text**

## Here is a secondary heading

Here's a useless table:

| Number | Next number | Previous number |
| :------ |:--- | :--- |
| Five | Six | Four |
| Ten | Eleven | Nine |
| Seven | Eight | Six |
| Two | Three | One |


How about a yummy crepe?

![Crepe](https://s3-media3.fl.yelpcdn.com/bphoto/cQ1Yoa75m2yUFFbY2xwuqw/348s.jpg)

It can also be centered!

![Crepe](https://s3-media3.fl.yelpcdn.com/bphoto/cQ1Yoa75m2yUFFbY2xwuqw/348s.jpg){: .center-block :}

Here's a code chunk:

~~~
var foo = function(x) {
  return(x + 5);
}
foo(3)
~~~

And here is the same code with syntax highlighting:

```javascript
var foo = function(x) {
  return(x + 5);
}
foo(3)
```

And here is the same code yet again but with line numbers:

{% highlight javascript linenos %}
var foo = function(x) {
  return(x + 5);
}
foo(3)
{% endhighlight %}

## Boxes
You can add notification, warning and error boxes like this:

### Notification

{: .box-note}
**Note:** This is a notification box.

### Warning

{: .box-warning}
**Warning:** This is a warning box.

### Error

{: .box-error}
**Error:** This is an error box.


<img src="https://render.githubusercontent.com/render/math?math=e^{i \pi} = -1">


<script type="text/javascript">
function randomlinks(){
    var myrandom=Math.round(Math.random()*9)
    var links=new Array()
    links[0]="http://www.javascriptkit.com"
    links[1]="http://www.dynamicdrive.com"
    links[2]="http://www.cssdrive.com"
    links[3]="http://www.codingforums.com"
    links[4]="http://www.news.com"
    links[5]="http://www.gamespot.com"
    links[6]="http://www.msnbc.com"
    links[7]="http://www.cnn.com"
    links[8]="http://news.bbc.co.uk"
    links[9]="http://www.news.com.au"
 
    window.location=links[myrandom]
}
</script>

<p>aaa<a href="javascript:randomlinks()">其中一个</a>??</p>
