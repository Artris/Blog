<template>
  <div id="app">
  {{ message }}
  </div>
</template>

<script>
console.log($site.themeConfig)
export default{
    data() { return {
          message: "Hello Vue!"
      }
    }
  }
</script>
