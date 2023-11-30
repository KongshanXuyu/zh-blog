# 主页



###  2020.9.1-2023.6.9

就读于河北枣强中学

北校区-梧桐树

![image-20231111093449443](./pictures/001.jpeg "北校区-梧桐树")

北校区

![image-20231111100454620](./pictures/002.png "北校区")

东南校区

![image-20231111100602148](./pictures/004.png "东南校区")



西校区

![image-20231111100646889](./pictures/003.png "西校区")



<script src="https://cdn.jsdelivr.net/npm/hls.js"></script>
<video id="video" preload muted loop controls autoplay style="height: 100%;width: 100%;object-fit: cover;">
</video>
<script>
  var video = document.getElementById('video');
  var videoSrc = './pictures/video.001/playlist.m3u8';
  if (Hls.isSupported()) {
    var hls = new Hls();
    hls.loadSource(videoSrc);
    hls.attachMedia(video);
    hls.on(Hls.Events.MANIFEST_PARSED, function() {
      video.play();
    });
  }
</script>

### 2023.9.6

就读于北京印刷学院
