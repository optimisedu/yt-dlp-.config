## A basic YT-DLP config.

I have tried being as clear as possible with my settings - yt-dlp comes with a great manual. This is easily extended.
Keep regularly updated
Feel free to fork.
Config files are kept %home%/.config/yt-dlp/config following linux conventions. Consider a child config if using with termux (TBA)


<h1> OPTIMISEDU YT-DLP CONFIG - READ FIRST </h1>
<strong> ALWAYS READ THE MANPAGE, HOWEVER THIS IS MY MOST COMMON SETUP.</strong>                                               

<code>man yt-dlp</code> 
Should work with no further steps but will print an error

## IMPORTANT LEGAL WARNING 
<strong>I DIDN'T CREATE YT-DLP - THIS IS A CONFIG FOR EDUCATIONAL PURPOSES ONLY. DOWNLOADS OF COPYRIGHTED MATERIAL IS ILLEGAL SO DO NOT ABUSE AND BE CAREFUL THAT YOU HAVE PERMISSION IF YOU USE THIS TO SCRAPE ANY PAGE!</strong>
<strong>yt-dlp is a pentesting tool. I have no affiliation or connection with this open source project.</strong>
Feel free to fork this repo, I would love to see how you modify this base config. 

### Hypothetical Safety For Pentesters
<code>
  --proxy |YOUR PROXY URL|
</code>
Not required but strongly advised. I have kept settings human. I suggest using a browser cookie/meta if you are using for this purpose



## TODO:
 - List useful cmds - tldr style
 - Add ffmpeg / other external pkgs for quality and wav/mp3 audio extraction
 - ytfzf suggested. implement fzy search params
 - Setup shell script install and extend extra dependencies 

## CHANGE LOG 25/11/23

 - Added TODOS
 - Added additional comments re setting options. (edit for clarity)


This is one of my current config files for yt-dlp. it works but you will probably want to customise yourself.

## Audio Focussed

Audio is more important for me than video. Some suggestions have been given but these are my settings. If there is any popularity I will give some child configs. I have tried to comment up some suggestions.

- Verbose by default: If you are getting errors you will want to know. (Remove this setting on first use)
- Drag and drop, run yt-dlp once, then remove the dryrun flag
- Unlimitedly extendable with python
- Chunked, optimal for my machine, won't be optimal for everybodies
- Metadata kept for postprocessing. With termux use that might be undesirable
- 30 fps should be plenty fast. Don't be stupid wkith filesize save time and data
- regex matching suggestions for different usecases

