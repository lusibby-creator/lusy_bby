<!DOCTYPE html>
<html>
<head>
  <script src='//libtl.com/sdk.js' data-zone='10951492' data-sdk='show_10951492'></script>
<meta charset="UTF-8">
<title>Video Unlock</title>

<style>
body{
background:#111;
color:white;
font-family:Arial;
text-align:center;
padding:20px;
}

video{
width:100%;
max-width:400px;
border-radius:15px;
}

button{
padding:15px 25px;
font-size:18px;
border:none;
border-radius:10px;
background:red;
color:white;
margin-top:20px;
cursor:pointer;
}

#fullVideo{
display:none;
}
</style>
</head>

<body>

<h1>Watch Full Video</h1>

<!-- Preview Video -->
<video controls autoplay muted>
<source src="PREVIEW_VIDEO_LINK.mp4" type="video/mp4">
</video>

<br>

<button onclick="unlockVideo()">
Watch Full Video
</button>

<div id="fullVideo">
<h2>Unlocked Video</h2>

<video controls>
<source src="FULL_VIDEO_LINK.mp4" type="video/mp4">
</video>
</div>

<script>

let clicks = 0;

function unlockVideo(){

clicks++;

if(clicks == 1){
window.open("https://omg10.com/4/10951496");
}

else if(clicks == 2){
window.open("https://omg10.com/4/10951502");
}

else if(clicks >= 3){
document.getElementById("fullVideo").style.display="block";
}

}

</script>

</body>
</html>
