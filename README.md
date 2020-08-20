# ffmpeg_libnvenc
用于H265编码转码推送，需要nVidia显卡

ffmpeg  -i "C:\Users\dexte\Desktop\true jesus church.mp4" -r 15 -c:v hevc_nvenc -pix_fmt yuv420p -f flv rtmp://localhost/live/user1
