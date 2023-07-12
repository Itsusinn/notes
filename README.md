# notes
Download YouTube playlist:

max 2K, mp4 output

`yt-dlp https://youtube.com/playlist?list=PLhQjrBD2T380F_inVRXMIHCqLaNUd7bN4 -f "bv*[height<=1440]+ba/b[height<=1440] / wv*+ba/w“  –embed-metadata –merge-output-format mp4 --downloader aria2c`
