## A basic YT-DLP config.

I have tried being as clear as possible with my settings - yt-dlp comes with a great manual. This is easily extended.
Keep regularly updated



, feel free to fork.
Config files are kept %home%/.config/yt-dlp/config following linux convensions.

<strong>yt-dlp is a pentesting tool. I have no affiliation or connection with this open source project.</strong>
add:
<code>
  --proxy |YOUR PROXY URL|
</code>
Not required but strongly advised. I have kept settings human. I suggest using a browser cookie/meta if you are using for this purpose

### Audio Focussed

Audio is more important for me than video. Some suggestions have been given but these are my settings. If there is any popularity I will give some child configs. I have tried to comment up some suggestions.

- verbose by default: If you are getting errors you will want to know. 
- drag and drop, run yt-dlp once, then remove the dryrun flag
- unlimitedly extendable with python
- chunked, optimal for my machine, won't be optimal for everybodies
- metadata kept for postprocessing. With termux use that might be undesirable
- 30 fps should be plenty fast. Don't be stupid wkith filesize
- regex matching suggestions for different usecases

