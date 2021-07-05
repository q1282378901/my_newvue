<template>
  <div id="app" :title="titles">
    <router-view />
  </div>
</template>

<script>
export default {
  name: "App",
  titles: "1",
};
</script>
