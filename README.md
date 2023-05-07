# convert_video_1_0
convert_video_1_0 - utility for converting video using ffmpeg console
ffmpeg uses CPU resources for video conversion, runs in the background through the console
For the conversion utility to work, you must first install ffmpeg and connect the Working Environment in the PC settings

The utility allows you to convert in two clicks all video files in the folder with the executable files to .mp4 from any other format, the converted files are saved in the out folder after rendering


There are several presets -
Base .mp4 HD h264 24fps and
.mp4 Full HD h264 24fps (only convert .avi, .mkv, .mov, .mp4 to .mp4 720p/1080p)

Extended .mp4 HD h264 24fps and
.mp4 Full HD h264 24fps (convert all known formats to .mp4 720p/1080p)

Convert audio files to .mp4
Full HD h264 24fps (convert all known audio formats to .mp4 1080p)

- convert_video1080p_extended.exe - convert all video formats to .mp4 1080p
- convert_video720p_extended.exe - convert all video formats to .mp4 720p
- convert_audio_video1080p.exe - convert all audio formats to .mp4 1080p

The .exe file to run the utility must be in the same folder as the video or audio materials to be converted

Installation:
Requires pre-installation of Windows PowerShell
For the utility to work, you must first install ffmpeg and connect the Working Environment in the PC settings
1. Install
Unzipping the contents of the archive
 ffmpeg-2023-04-26-git-e3143703e9-full_build_alt
to the directory
 ffmpeg to directory C:\ffmpeg\
2. Add the C:\ffmpeg\bin directory to Windows desktop environments
3. We check the performance through the console, check whether the working environment is installed by entering the "ffmpeg" command into the command line
4. Run the .exe file with preset render settings, after conversion the files are saved to the /out folder
The .exe file to run the utility must be in the same folder as the video or audio materials to be converted
