<template>
  <div class="contendor-video">
    <video controls class="video-styling">
      <source :src="videoUrl" type="video/mp4" />
    </video>
  </div>
</template>

<script>
export default {
  name: "IndexPage",
  data() {
    return {
      videoUrl:
        "https://ja-my-serverless-react-app-20-03-2023.s3.amazonaws.com/acceso-video/VIDEOEVENTO.mp4",
    };
  },
};
</script>

<style>
.contendor-video {
  width: 50%;
  margin: auto;
}

.video-styling {
  width: 100%;
  height: auto;
  background-color: #000;
  padding: 10px;
  margin: 10px 0;
}
</style>
