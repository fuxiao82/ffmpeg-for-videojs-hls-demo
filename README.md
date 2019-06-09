"# ffmpeg-for-videojs-hls-demo" 
ffmpeg -i in.mp4 -c:v libx264 -c:a copy -f hls out.m3u8
