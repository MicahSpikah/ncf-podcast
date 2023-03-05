# Requirements
* fish
* yt-dlp
* ffmpeg
* jq

If you don't have these, download and install homebrew, then run `brew install fish yt-dlp ffmpeg jq`

# Usage
./podcast \<youtube url\> \<start time\> \<stop time\> [output filename]

Example: ./podcast "https://www.youtube.com/watch?v=Uk3H21HHDlo" 37:21 1:07:57 20220828.m4a 

If not given, the output filename defaults to a date code matching the most recent Sunday
