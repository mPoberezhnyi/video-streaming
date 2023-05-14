<template>
  <header>
    <div class="wrapper">
      <h1>Video streaming</h1>
    </div>
  </header>

  <main>
    <video class="video" controls>
      <source
        src="http://commondatastorage.googleapis.com/gtv-videos-bucket/sample/ElephantsDream.mp4"
      />
    </video>
  </main>
</template>

<style>
.video {
  width: 720px;
}
</style>
