<template>
  <div id="app">
    <header>
      <div class="title">PConsole</div>
    </header>
    <div class="content">
      <router-view></router-view>
    </div>
  </div>
</template>

<script>
export default {
  name: 'app'
}
</script>