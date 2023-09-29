---
title: Latest Videos
permalink: /videos
---
<div id="ytplayer"></div>

<script>
  // Load the IFrame Player API code asynchronously.
  var tag = document.createElement('script');
  tag.src = "https://www.youtube.com/player_api";
  var firstScriptTag = document.getElementsByTagName('script')[0];
  firstScriptTag.parentNode.insertBefore(tag, firstScriptTag);

  // Replace the 'ytplayer' element with an <iframe> and
  // YouTube player after the API code downloads.
  var player;
  function onYouTubePlayerAPIReady() {
    player = new YT.Player(<iframe src="https://www.youtube.com/embed/?listType=user_uploads&list=UCW_dsmLJe5dIrVw34y9IOew" width="480" height="400"></iframe>);
  }
</script>

<iframe src="https://www.youtube.com/embed/?listType=user_uploads&list=UCW_dsmLJe5dIrVw34y9IOew" width="480" height="400"></iframe>
