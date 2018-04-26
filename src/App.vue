<template>
<div class="app-wrapper">
  <header class="header">Test</header>
	<div class='icon'></div>
    <div class='msg'>{{myMessage}}</div>
</div>
</template>
<script>
export default {
     data() { 
         return { 
             myMessage : 'My message goes here'
         }
     }
}
</script>
<style lang="scss" scoped>
   @import 'main.scss'
</style>