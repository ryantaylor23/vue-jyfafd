<template>
  <div class="container mt-5">
    <h1 class="text-center" id="contact">Please Contact Us! <br>We would love to hear about 
      your Gem finds!
    </h1>
      <form>
        <div class="mb-3 mt-3">
          <label for="email">Email:</label>
          <input type="email" class="form-control" id="email" placeholder="name@outlook.com" name="email">
        </div>
        <div class="mb-3">
          <label for="find">Gem Find:</label>
          <input type="find" class="form-control" id="find" placeholder="Ruby" name="find">
        </div>
        <button type="submit" class="btn btn-secondary">Submit</button>
      </form>
  </div>
  </body>
</template>

<style scoped>
h1 {
  color: white; 
}
label {
  font-size: 25px;
  color: white;
}
</style>


<script>
export default {
  name: 'Comp4',
  props: {},
};
</script>
