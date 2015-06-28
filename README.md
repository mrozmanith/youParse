# YouParse.py
This is a forked (and fixed) version of [youParse.py](https://sourceforge.net/projects/youparse) from SourceForge. The old version did not preserve the correct order of videos in provided YouTube playlists. I fixed this simple bug by using an ```OrderedDict``` instead of a plain old ```set```.

I couldn't get in touch with the author, so I've forked the project here. This version of YouParse returns a properly ordered list of YouTube videos when passed a well-formed playlist URL.

## Usage
First make sure you give youParse.py executable permissions.

```sudo chmod +x youParse.py```

YouParse takes a single YouTube playlist URL as its only argument. It outputs an ordered list of all video URLs from the provided playlist:

```
> youParse.py https://www.youtube.com/playlist?list=PLQ1MEo-qx100AhXAZxyQCjEbouXRcLYfb
http://www.youtube.com/watch?v=C1HAuXMua5s
http://www.youtube.com/watch?v=jQSuNdJmr60
http://www.youtube.com/watch?v=B9Y_FlIpP0k
http://www.youtube.com/watch?v=WdF_MQPuGLA
http://www.youtube.com/watch?v=zh4Z4QRN10s
http://www.youtube.com/watch?v=_sj1Rra0fIY
http://www.youtube.com/watch?v=VLOaXfVq5sk
http://www.youtube.com/watch?v=fX7jbMpJGp8
http://www.youtube.com/watch?v=UIvkFNaHEBw
```

## Requires
YouParse requires Python 2.7 or greater.
