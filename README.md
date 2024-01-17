<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Video Playlist with Dropdown</title>
    <style>
        body {
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
            margin: 0;
        }

        #selectedVideoContainer, #videoSelect {
            margin-bottom: 20px;
        }

        #videoPlayer {
            max-width: 100%;
        }
    </style>
</head>
<body>

<label for="videoSelect">Select a video:</label>
<select id="videoSelect" onchange="changeVideo()">
    <option value="pt1.mp4">Gunsmith PT 1</option>
    <option value="pt2.mp4">Gunsmith PT 2</option>
	<option value="pt3.mp4">Gunsmith PT 3</option>
    <option value="pt4.mp4">Gunsmith PT 4</option>
	<option value="pt5.mp4">Gunsmith PT 5</option>
    <option value="pt6.mp4">Gunsmith PT 6</option>
	<option value="pt7.mp4">Gunsmith PT 7</option>
    <option value="pt8.mp4">Gunsmith PT 8</option>
	<option value="pt9.mp4">Gunsmith PT 9</option>
    <option value="pt10.mp4">Gunsmith PT 10</option>
	<option value="pt11.mp4">Gunsmith PT 11</option>
    <option value="pt12.mp4">Gunsmith PT 12</option>
	<option value="pt13.mp4">Gunsmith PT 13</option>
    <option value="pt13.mp4">Gunsmith PT 14</option>
	<option value="pt14.mp4">Gunsmith PT 15</option>
    <option value="pt15.mp4">Gunsmith PT 16</option>
	<option value="pt16.mp4">Gunsmith PT 17</option>
    <!-- Add more options for each video -->
</select>

<div id="selectedVideoContainer">
    <h2>Selected Video:</h2>
    <video id="videoPlayer" width="640" height="360" controls>
        <source id="videoSource" src="video1.mp4" type="video/mp4">
        Your browser does not support the video tag.
    </video>
</div>



<script>
    function changeVideo() {
        var videoSelect = document.getElementById("videoSelect");
        var videoPlayer = document.getElementById("videoPlayer");
        var videoSource = document.getElementById("videoSource");

        var selectedVideo = videoSelect.value;
        videoSource.src = selectedVideo;
        videoPlayer.load();
    }
</script>

</body>
</html>
