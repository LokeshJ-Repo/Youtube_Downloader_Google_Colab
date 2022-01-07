# Youtube Downloader Google Colab

# Use google colab to download youtube audio and video
Tired of adds while downlading youtube audio and video, using third party websites and apps?
Then this is one of the best way to download video and audio from youtube. 
The script uses pytube python package to download video/audio from youtube, 

<a href="https://colab.research.google.com/drive/1la5FIXF37lQ-hVxMa3PQn4mIaA71VjSL"
   target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

### Tutorial
1. Click the badge which says 'Open in Colab'.

Option 1 : Direct download from google colab to local drive. (without having a copy in google drive)
1. Enter youtube URL that you wish to downlaod in YT_URL form.
2. Select Audio or Video to be downloaded from FILE_TYPE dropdown
3. Run the cell and wait for it to downlaod.

Option 2 : Download video/Audio to google drive and provide a link (faster download and copy in drive)
1. run the cell to mount google drive.
2. Go to link provided, sign in to google account and copy and paste the outh key in the input to mount google drive. 
3. Enter youtube URL that you wish to downlaod in YT_URL form.
4. Select Audio or Video to be downloaded from FILE_TYPE dropdown
5. Run the cell and wait for it to provide google drive download link.


### What is the purpose of it?
1. High bandwidth from google servers
2. Avoid advertisements while downloading YT video/Audio from third party websites.
3. Keeping copy of files in google colab.



### Frequently Asked Questions

1. **How to share files with others**: (for option 2)

Turn on link sharing on for folder /drive/Downloads in your gdrive and share the link of the folder or zip file generated.

2. **How to download Audio in different bps and diffrent res for video**: (for option 1 and 2)

Script uses itags in pytube pakage to download Audio/video files. itag:18 for 360p video/mp4 (progressive video) and itag:140 for 128kbps
Audio/mp4 (Audio) is used as default in the script. You can change the itag values in the code to download different bps/res audio/video file.
please visit below link to get itag values.
https://pytube.io/en/latest/user/streams.html




# This whole repo is against Google Colab policy and you shouldn't be using it.
> **Why are hardware resources such as T4 GPUs not available to me?**
The best available hardware is prioritized for users who use Colaboratory interactively rather than for long-running computations. Users who use Colaboratory for long-running computations may be temporarily restricted in the type of hardware made available to them, and/or the duration that the hardware can be used for. We encourage users with high computational needs to use Colaboratory’s UI with a local runtime.
Please note that using Colaboratory for cryptocurrency mining is disallowed entirely, and may result in being banned from using Colab altogether.

<sub>Source: https://research.google.com/colaboratory/faq.html</sub>

### Maintained By : [Lokesh J](https://www.linkedin.com/in/lokesh-j-13b844140/)
