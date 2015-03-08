ytmp3
=====

ytmp3 is a command line Youtube mp3 downloader for OSX.

<p>
  <img src="http://wono.me/images/ytmp3.gif?raw=true"/>
</p>

Defendencies
------------
*   ytdl - Pure Javascript youtube video downloader:
    https://github.com/fent/node-ytdl (Node Package Modules required)
    
*   FFmpeg - A complete, cross-platform solution to record, convert and stream 
    audio and video: https://github.com/FFmpeg/FFmpeg (Recommend using 
    Homebrew)
    
To install the defendencies, you can either 1) run installation script 
or 2) manually type the installation command like this:
    
    # ytdl installation
    sudo npm -g install ytdl

    # FFmpeg installation (Please refer http://ffmpeg.org to see 
    # available installation options)
    brew install ffmpeg

How To Use
----------
The run command is like this:
    
    ytmp3 music_title video_url
