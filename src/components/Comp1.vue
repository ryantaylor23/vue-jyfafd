<template>
   <body>
    <header>
      <div class="jumbotron text-center" style="margin-bottom: 0; background-image: url(https://cdn.pixabay.com/photo/2017/02/10/03/12/winter-2054297_1280.jpg)">
        <h1 class="heading">Gem World</h1>
      </div>
    </header>

      <nav class="container-fluid navbar navbar-expand-sm bg-secondary navbar-dark">
        <a class="navbar-brand" href="#home">Home</a>
        <div class="navbar" id="navbar">
          <ul class="navbar-nav">
            <li class="nav-item">
              <a class="nav-link" href="#gems">Gems</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#products">Products</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#about">About Us</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#contact ">Contact Us</a>
            </li>
          </ul>
        </div>
      </nav>
</template>

<script>
export default {
  name: 'Comp1',
  props: {},
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.heading {
  color: black;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b98d;
}
</style>
