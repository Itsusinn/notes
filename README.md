# notes
Download YouTube playlist:

max 2K, mp4/mkv output, audio mixed, with subtitles

`yt-dlp https://youtube.com/playlist?list=PLhQjrBD2T380F_inVRXMIHCqLaNUd7bN4 -f "bv*[height<=1440]+ba/b[height<=1440] / wv*+ba/w“ --downloader aria2c  --remux-video "aac>m4a/mov>mp4/mkv" --embed-metadata  --write-subs`
