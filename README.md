📥 YouTube Downloader Pro

<p align="center">
A clean and powerful desktop tool for downloading YouTube videos and playlists with advanced audio and subtitle options.
</p>

<div align="center">
<img alt="Single Video Download View" src="https://github.com/user-attachments/assets/7f39ed42-3c02-4b7c-b21b-2038d144c67e" />
</div>

### ✨ Key Features

This tool uses yt-dlp and the YouTube API v3 to provide a comprehensive download experience.

Single Video Downloader: Paste any video URL or search term and get a full list of available MP4 streams.

Full Playlist Support: Download entire playlists at once, with options to select specific videos.

Multiple Formats:

Video: Download as MP4 in various resolutions (1080p, 720p, etc.).

Audio-Only: Extract and convert audio to MP3, M4A, or WAV.

Advanced Audio Selection:

Download a video with a specific audio language track (e.g., download a video with its Spanish or Japanese audio).

Subtitle Integration:

Download and embed available subtitles into your video file.

Self-Updating: Includes a built-in "Update Tools" button to fetch the latest version of yt-dlp, ensuring it keeps working even if YouTube makes changes.

Smart Merging: Automatically merges video-only and audio-only streams (using the bundled FFmpeg) for the best possible quality.

### 🚀 How to Use

Search: Paste a full YouTube video/playlist URL or any search term into the search box and press Enter or click Search.

Select:

For a Single Video: A list of all available MP4 streams will appear. Select the quality you want.

For a Playlist: A list of all videos in the playlist will appear. Select the videos you want (you can select multiple) and choose a global format (e.g., MP3, MP4).

Advanced (Optional):

Click the "Advanced..." button to select a specific audio language track or to embed subtitles for your download.

Download:

Choose your "Save to" directory.

Click "Download Selected Video Stream" (for single videos) or "Download Selected from Playlist".

🖼️ Screenshots

<table align="center">
<tr>
<td align="center"><b>Single Video View</b>



<i>Select specific streams and advanced options.</i></td>
<td align="center"><b>Playlist View</b>



<i>Select multiple videos and a global format.</i></td>
</tr>
<tr>
<td><img alt="Single Video Screenshot" src="https://github.com/user-attachments/assets/7f39ed42-3c02-4b7c-b21b-2038d144c67e" /></td>
<td><img alt="Playlist Screenshot" src="https://github.com/user-attachments/assets/d7e63080-16ea-4581-83cc-e8f9116d0129" /></td>
</tr>
</table>

⚠️ A Note on FFmpeg

This application comes with ffmpeg.exe and ffprobe.exe bundled inside the final .exe file. It's required for merging video/audio and converting to MP3.

💡 If you see an FFmpeg error saying it failed to download—don’t worry! > Just check the folder you selected; your downloaded files will most likely be there. This can happen if the merging process completes but reports an error incorrectly.

## 🛠️ Optional: Add FFmpeg to System PATH (Recommended)

To improve compatibility and performance, you can add FFmpeg to your system PATH:

1. Download FFmpeg from: [https://www.gyan.dev/ffmpeg/builds/](https://www.gyan.dev/ffmpeg/builds/)
2. Select: `ffmpeg-git-essentials.7z`
3. Extract the folder anywhere (e.g., `D:\Apps\ffmpeg\`).
4. Open the extracted folder and go to the `bin` directory. Example:  

C:\Program Files (x86)\ffmpeg-<date>-git-<version>-essentials_build\bin

5. Copy that path.
6. Add it to your **System PATH** environment variable.

### 🤔 How to Edit the System PATH?

If you're unsure how to do this, you can search for:

> **“Edit the system environment variables”** in the Windows Start Menu,  
> then click **Environment Variables** and edit the `Path`.

---

I'm done for now 😅
