---
title: Latest Videos
permalink: /videos
---
<div id="ytplayer"></div>

<script>
  var tag = document.createElement('script');
  tag.src = "https://www.youtube.com/player_api";
  var firstScriptTag = document.getElementsByTagName('script')[0];
  firstScriptTag.parentNode.insertBefore(tag, firstScriptTag);
  var player;
  function onYouTubePlayerAPIReady() {
    player = new YT.Player(<iframe src="https://www.youtube.com/embed/?listType=user_uploads&list=W_dsmLJe5dIrVw34y9IOew" width="480" height="400"></iframe>);
  }
</script>
