# https://mp3.shortener.ma | https://shortener.ma/iframe

# INSTALLATION :
1. it's simple, first download the zip file.
2. Copy them to localhost or to your site.
3. And you can change Style from css/iframe.css is free.

# iFrame API
~~~
- Example [iframe]
<iframe src="https://shortener.ma/iframe/" width="600" height="360" scrolling="no" style="border:none;"></iframe>
~~~

~~~
- Example [iframe / mp3]
<iframe src="https://shortener.ma/iframe/?v=gIYaTs1Kw90&f=mp3" width="600" height="360" scrolling="no" style="border:none;"></iframe>
~~~

~~~
- Example [iframe / mp4]
<iframe src="https://shortener.ma/iframe/?v=gIYaTs1Kw90&f=mp4" width="600" height="360" scrolling="no" style="border:none;"></iframe>
~~~

## Preview : https://mp3.shortener.ma/Developers/
#### Parameters (optional):
- v [youtube video id] - must contain a valid 11 digits YouTube video id (gIYaTs1Kw90)
- f [format] - must contain a supported format (mp3 or mp4)

________________________________________________________________________________________________________________________________________
# Link API
~~~
Example [mp3 / href] 
<a href="https://www.youtube.com/watch?v=gIYaTs1Kw90" target="_self" class="y2m"> Click to Download MP3</a>
~~~

~~~
- Example [mp3 / data-href]
<a href="" data-href="https://www.youtube.com/watch?v=gIYaTs1Kw90" target="_self" class="y2m"> Click to Download MP3</a>
~~~

~~~
- Example [mp4 / href]
<a href="https://www.youtube.com/watch?v=gIYaTs1Kw90" target="_self" class="y2m mp4"> Click to Download MP4</a>
~~~

~~~
- Example [mp4 / data-href]
<a href="" data-href="https://www.youtube.com/watch?v=gIYaTs1Kw90" target="_self" class="y2m mp4"> Click to Download MP4</a>
~~~

## Preview : https://mp3.shortener.ma/Developers/
#### Parameters (required):
~~~
<script type="text/javascript" src="https://shortener.ma/mp3/js/link.js"></script>
~~~
- href or data-href - must contain a valid YouTube video url (https://www.youtube.com/watch?v=gIYaTs1Kw90 or https://youtu.be/gIYaTs1Kw90)
class - must contain y2m / if you would like to convert to mp4 (y2m mp4)
