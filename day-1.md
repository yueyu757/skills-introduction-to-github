# Daily Learning
## Morning Planning
<img alt="Cloudy morning" src="https://octodex.github.com/images/cloud.jpg" width="100" align="right">
## Review
使用 [ffmpeg](https://www.ffmpeg.org) 将图片或视频从深色模式转换为浅色模式
```bash
ffmpeg -i input.mp4 -vf "negate,hue=h=180,eq=contrast=1.2:saturation=1.1" output.mp4
```
