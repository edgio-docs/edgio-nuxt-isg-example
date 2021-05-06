<template>
  <div class="container">
    <div>
      <Logo />
      <h1 class="title">nuxt-isg-example</h1>
      <p style="max-width: 1024px; margin: 16px 0; font-size: 20px">
        To see ISG in action, go to one of the following links. You'll see a
        loading screen the first time, but if you wait a few seconds and reload,
        you won't see the loading screen on subsequent requests because the page
        will have been statically rendered and cached behind the scenes.
      </p>
      <div class="links">
        <a href="/products/1" class="button--green"> Product #1 </a>
        <a href="/products/2" class="button--green"> Product #2 </a>
        <a href="/products/3" class="button--green"> Product #3 </a>
        <a href="/products/4" class="button--green"> Product #4 </a>
        <a href="/products/5" class="button--green"> Product #5 </a>
      </div>
    </div>
  </div>
</template>

<script>
export default {}
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
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
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
