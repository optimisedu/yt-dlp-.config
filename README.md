## A basic YT-DLP config.

I have tried being as clear as possible with my settings - yt-dlp comes with a great manual. This is easily extended.
Keep regularly updated
Feel free to fork.
Config files are kept %home%/.config/yt-dlp/config following linux conventions. Consider a child config if using with termux (TBA)


## Optimisedu's YTDLP Config 
ALWAYS READ THE MANPAGE, HOWEVER THIS IS MY MOST COMMON SETUP.                                              

<code>man yt-dlp</code> 
Should work with no further steps but will print an error

## IMPORTANT LEGAL WARNING 
I didn't create YT-DLP - This is a config for educational purposes only. Downlaods of copyrighted material is illegal so do not abuse. Be careful you have permission if you are using tools which scrape webpages! I have no affiliation with this open source project.

Feel free to fork this repo, I would love to see how you modify this base config. 

#### Hypothetical Safety For Pentesters

<code>
  --proxy |YOUR PROXY URL|
</code>
Not required but strongly advised. I have kept settings human. I suggest using a browser cookie/meta if you are using for this purpose

#### Todo:

 - List useful cmds - tldr style
 - Add ffmpeg / other external pkgs for quality and wav/mp3 audio extraction
 - ytfzf suggested. implement fzy search params
 - Setup shell script install and extend extra dependencies 

#### CHANGE LOG 25/11/23

 - Added TODOS
 - Added additional comments re setting options. (edit for clarity)
 - Updated readme.md

This is one of my current config files for yt-dlp. it works but you will probably want to customise yourself.

## Audio Focussed

Audio is more important for me than video. Some suggestions have been given but these are my settings. If there is any popularity I will give some child configs. I have tried to comment up some suggestions.

- Compatible with Termux on android, fully cross platform.
- Unlimitedly extendable with python
- Verbose by default: If you are getting errors you will want to know. (Remove this setting on first use)
- Drag and drop, run yt-dlp once, then remove the dryrun flag
- Chunked, optimal for my machine, tweak to find the sweet spot on your system (low on old systems or phones)
- Metadata kept for postprocessing. With termux use that might be undesirable
- 30 fps should be plenty fast. Don't be stupid wkith filesize save time and data un;ess you know what you are doing and have a usecase for downloading videos at a refresh rate faster than the human eye can register - 30fps is what average tv's run at.
- regex matching suggestions for different usecases - suggestions coming.

