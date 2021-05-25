<template>
  <div id="app">
    <div class="h-screen flex flex-col">
      <Header/>
      <div class="flex flex-1 overflow-hidden">
        <SideBar/>
        <MainBody/>
      </div>
    </div>
  </div>
</template>

<script>
import Header from './components/Header.vue';
import MainBody from './components/MainBody.vue';
import SideBar from './components/SideBar.vue';

export default {
  name: 'App',
  components: {
    Header,
    MainBody,
    SideBar
  }
}
</script>

<style>
</style>
