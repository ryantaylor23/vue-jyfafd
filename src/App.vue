<template>
 <!DOCTYPE html>
 <html lang="en"> 
  <head>
    <title>Gem World</title>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <link
      rel="stylesheet"
      href="https://cdn.jsdelivr.net/npm/bootstrap@4.6.2/dist/css/bootstrap.min.css"
    />
    <script src="https://cdn.jsdelivr.net/npm/jquery@3.7.1/dist/jquery.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.6.2/dist/js/bootstrap.bundle.min.js"></script>
    <style></style>
  </head>
  <div id="app">
    <Comp1 />
    <Comp2 />
    <Comp3 />
    <Comp4 />
    <Comp5 />
  </div>
</template>

<script>
import Comp1 from './components/Comp1.vue';
import Comp2 from './components/Comp2.vue';
import Comp3 from './components/Comp3.vue';
import Comp4 from './components/Comp4.vue';
import Comp5 from './components/Comp5.vue';

export default {
  name: 'App',
  components: {
    Comp1,
    Comp2,
    Comp3,
    Comp4,
    Comp5,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: white;
  background-color: #91A3B0;
}
</style>
