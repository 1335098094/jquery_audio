# jquery_audio
效果展示图：
![image](https://github.com/1335098094/jquery_audio/blob/master/img/audioPlay/h.png)
![image](https://github.com/1335098094/jquery_audio/blob/master/img/audioPlay/g.png)
1.首先
<audio id="audio">
    <source src="http://sc1.111ttt.com/2017/1/11/11/304112002347.mp3" type="audio/mp3">//导入一个音频文件
</audio>
2.
<div class="audio-right">
    <div class="progress-bar-bg" id="progressBarBg">//自定义进度条
      <span id="progressDot" style="left:0px"></span>//进度点
        <div class="progress-bar" id="progressBar"></div>//正在播放到自定义进度条
   </div>
    <div class="audio-time"><span class="audio-length-current" id="audioCurTime">00:00</span><span class="audio-length-total"               id="audio-length-total"></span></div>//自定义播放器按钮
</div>
3.js自定义控制播放
