<template>
  <f7-page name="LoadingPage">
    <div class="loading-page">
      <h1 class="loading-page__title">Blink-To-Text</h1>
      <img
        class="loading-page__img"
        src="../static/images/blink.png"
        alt="eye_logo"
      />
      <f7-preloader
        class="loading-page__spinner"
        :size="35"
        color="white"
      ></f7-preloader>
      <h3 class="loading-page__loading-text">
        Practice Blinking Until Our App <br />finishes loading...
      </h3>
      <p class="loading-page__app-info">
        Created by KMIT<br />
      </p>
    </div>
  </f7-page>
</template>

<script>
export default {};
</script>
