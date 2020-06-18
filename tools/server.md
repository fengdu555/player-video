<!--
 * @Author: your name
 * @Date: 2020-06-17 15:05:07
 * @LastEditTime: 2020-06-17 15:08:46
 * @LastEditors: Please set LastEditors
 * @Description: In User Settings Edit
 * @FilePath: /github/player-video/tools/server.md
--> 

推流命令
ffmpeg -re -i test.mp4 -c copy -f flv rtmp://localhost:1935/live/movie

验证地址
http://127.0.0.1:7002/live/movie.m3u8  hls协议

http://127.0.0.1:7001/live/movie.flv   flv协议

rtmp://localhost:1935/live/move        rtmp协议
