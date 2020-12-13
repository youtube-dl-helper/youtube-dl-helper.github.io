# youtube-dl-helper

youtube-dl-helper is a tool for Windows that can download video or audio from [many sites](https://ytdl-org.github.io/youtube-dl/supportedsites.html) without requiring you to use the command-line.

### If you have any problems or suggestions, send me an email: **mesdartin@gmail.com**

## How to use

* Download [youtube-dl-helper.zip](https://github.com/youtube-dl-helper/youtube-dl-helper.github.io/releases/download/v0.1/youtube-dl-helper.zip) and extract it anywhere on your computer that doesn't require administrator permission to write to (for example, the desktop or downloads folder are OK, but not the Program Files folder) and open the **youtube-dl-helper** folder.

![](folder.png)

* Double-click on **download.txt** to open it in Notepad and paste in the URLs of the pages containing the video or audio you want to download. You can put multiple URLs on separate lines. Save the file with **Ctrl + S** or by clicking **File > Save**.

![](notepad.png)

* Double-click on **run.bat**. A command-line window will open, showing the status of the downloading files. The downloaded files will be in the **downloaded** folder.

![](finished.png)

## More options

Open the **more** folder and instead of **run.bat** you can run...

* **audio.bat**: Download just the audio in the best quality available
* **mp3.bat**: Download just the audio and re-encode it to MP3
* **best.bat**: Download video in the best quality available (which may not be MP4)
* **id.bat**: Append the ID to the filename
* **date.bat**: Prepend the upload date to the filename

## About this project

This tool is just a few very simple batch files that use [youtube-dl](https://youtube-dl.org/). The reason why you might want to use this instead of using youtube-dl directly is because youtube-dl by default...

* Requires the use of the command-line
* Can require additional software (FFmpeg, RTMPDump, Microsoft Visual C++ 2010 Redistributable Package)
* Names downloaded files with the ID appended to the title
* Downloads videos from YouTube in various formats instead of only MP4
* Doesn't update automatically

You may prefer to use [TheFrenchGhosty's YouTube-DL Archivist Scripts](https://github.com/TheFrenchGhosty/TheFrenchGhostys-YouTube-DL-Archivist-Scripts).
