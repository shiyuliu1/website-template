---
layout: page
title: Shiyu's Gallery
subtitle: View some of Shiyu's photography Works and Video Clips
---
### Joshua Tree National Park, CA




<p>我有很多聪明有趣的朋友。 一起来看看他们<a href="javascript:randomSite()">其中一个</a>是谁吧!</p>


<script>
function randomSite() {
var links = [
              "google.com",
              "youtube.com",
              "reddit.com",
              "apple.com"]

            openSite = function() {
              // get a random number between 0 and the number of links
              var randIdx = Math.random() * links.length;
              // round it, so it can be used as array index
              randIdx = parseInt(randIdx, 10);
              // construct the link to be opened
              var link = 'http://' + links[randIdx];
              };
              
    return link;
    
    document.getElementById("link").innerHTML = openSite();
}
</script>

