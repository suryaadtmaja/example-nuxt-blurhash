<template>
  <div class="container">
    <div style="height: 300px; width: 400px">
      <div>
        <nuxt-blur-image
          width="400"
          height="300"
          src="https://images.unsplash.com/photo-1417325384643-aac51acc9e5d?q=75&fm=jpg&w=1080&fit=max"
          hash="LFC$yHwc8^$yIAS$%M%00KxukYIp"
        />
      </div>
      <!-- <div>
        <nuxt-blurhash
          width="400"
          height="300"
          hash="LFC$yHwc8^$yIAS$%M%00KxukYIp"
        />
      </div> -->
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont,
    "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
