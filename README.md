# youParse
Returns a list of YouTube videos when passed a playlist URL.

This repository is a forked and fixed version of ```youParse.py``` from pantuts on SourceForge. The old version did not preserve the order of videos in provided playlists. I fixed this bug by using an ```OrderedDict``` instead of a plain old ```set```. Now youParse.py returns a properly ordered list of YouTube videos when passed a playlist URL.
