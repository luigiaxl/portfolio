<template>
  <div class="banner-container h-full bg-blue-400 min-h-full flex items-center">
    <div class="flex-1 flex flex-wrap justify-between items-center py-4 bg-gray-800">
      <div class="flex-1 flex justify-end mr-4">
        <div class="image-container rounded-full overflow-hidden">
          <img src="../../assets/me.png" alt="">
        </div>
      </div>

      <div class="info-container flex-1 flex flex-col items-start text-white">
        <div>Luigi Axl Wagas</div>
        <div class="text-gray-500">Web Stack Developer</div>
        <div class="text-gray-500">HTML, CSS, JS, PHP, ETC...</div>
        <div class="text-gray-500 text-sm">
          <Icon :icon="['fas', 'envelope']" /> luigi.axl.wagas@gmail.com
        </div>
        <div>
          <a
            href="https://twitter.com/luigi_axl"
            target="_blank"
            class="no-underline text-gray-500 mr-2"
          >
            <Icon :icon="['fab', 'twitter']" />
          </a>
          <a
            href="https://github.com/luigiaxl"
            target="_blank"
            class="no-underline text-gray-500 mr-2"
          >
            <Icon :icon="['fab', 'github']" />
          </a>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
</script>

<style scoped>
  .banner-container {
    background-image: url('/code_screenshot.png');
    background-size: cover;
  }

  .image-container {
    width: 100px;
    height: 100px;
  }

  .info-container {
    min-width: 210px;
  }
</style>