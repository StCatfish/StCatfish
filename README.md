<video class="demo-video" src="https://ik.imagekit.io/ikmedia/example_video.mp4" width="640" height="360" controls=""></video>
<h1>HTML5 Video Streaming Demo</h1>
  <p>A demonstration of native HTML5 video capabilities with JavaScript controls and ImageKit video optimization.</p>

  <!-- Basic Video Example -->
  <section id="basic">
    <h2>Basic Video with Controls</h2>
    <p>The simplest implementation using the native <code>&lt;video&gt;</code> element with browser controls.</p>

    <video class="demo-video" src="https://ik.imagekit.io/ikmedia/example_video.mp4" width="640" height="360" controls=""></video>
  </section>

  <!-- Video with Poster -->
  <section id="poster">
    <h2>Video with Poster Thumbnail</h2>
    <p>Display an image before the video loads using ImageKit's automatic thumbnail generation.</p>

    <video class="demo-video" src="https://ik.imagekit.io/ikmedia/example_video.mp4" width="640" height="360" controls="" poster="https://ik.imagekit.io/ikmedia/example_video.mp4/ik-thumbnail.jpg?tr=so-5,w-640,h-360"></video>
  </section>

  <!-- Autoplay Example -->
  <section id="autoplay">
    <h2>Autoplay (Muted)</h2>
    <p>Browsers require videos to be muted for autoplay to work. Perfect for hero banners and background videos.</p>

    <video class="demo-video" src="https://ik.imagekit.io/ikmedia/example_video.mp4" width="640" height="360" autoplay="" muted="" loop="" playsinline=""></video>
  </section>

  <!-- Custom Video Player -->
  <section id="custom">
    <h2>Custom JavaScript Video Player</h2>
    <p>A fully custom video player built with vanilla JavaScript using the HTML5 Video API.</p>

    <div class="video-container">
      <video id="custom-video" src="https://ik.imagekit.io/ikmedia/example_video.mp4"></video>
      <div class="controls">
        <button id="playPause">Play</button>
        <div class="progress-bar" id="progressBar">
          <div class="progress" id="progress"></div>
        </div>
        <div class="volume-control">
          <span>Vol</span>
          <input type="range" id="volume" min="0" max="1" step="0.1" value="1">
        </div>
        <span class="time" id="time">0:00 / 0:00</span>
      </div>
    </div>
  </section>
