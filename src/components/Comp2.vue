<template>
  <img
    class="img-fluid mt-5"
    alt="Crystal-Picture"
    src="https://cdn.pixabay.com/photo/2023/01/04/19/06/ai-generated-7697456_1280.jpg"
  />

  <div class="container-fixed" style="margin-top: 50px">
    <div class="container mt-5" id="gems">
      <h2 class="text-center">Gems for Sale!</h2>

      <div class="row mt-4">
        <div class="col-sm-4">
          <h2 class="img-responsive text-center">Amethyst</h2>
          <img
            class="img-fluid"
            alt="Amethyst-Picture"
            src="https://cdn.pixabay.com/photo/2018/04/17/17/28/amethyst-3328166_1280.jpg"
          />
        </div>

        <div class="col-sm-4">
          <h2 class="img-responsive text-center">Emerald</h2>
          <img
            class="img-fluid"
            alt="Emerald-Picture"
            src="https://cdn.pixabay.com/photo/2017/06/15/11/43/necklace-2405165_1280.jpg"
          />
        </div>

        <div class="col-sm-4">
          <h2 class="img-responsive text-center">Diamond</h2>
          <img
            class="img-fluid"
            alt="Diamond-Picture"
            src="https://cdn.pixabay.com/photo/2013/06/08/19/15/diamond-123338_1280.jpg"
          />
        </div>
      </div>
    </div>

    <div class="container-fluid mt-5" id="products">
      <h2 class="text-center">Check out our Pricing and Healing Property!</h2>
      <table class="table table-bordered table-secondary mt-4">
        <thead class="h3">
          <tr>
            <th>Gem</th>
            <th>Price-Per-Gram</th>
            <th>Healing Property</th>
            <th>Order</th>
          </tr>
        </thead>
        <tbody class="h4">
          <tr>
            <td>Amethyst</td>
            <td>$9.99</td>
            <td>Calming</td>
            <td>#</td>
          </tr>
          <tr>
            <td>Emerald</td>
            <td>$7.50</td>
            <td>Heart Healing</td>
            <td>#</td>
          </tr>
          <tr>
            <td>Diamond</td>
            <td>$12.50</td>
            <td>Cleansing</td>
            <td>#</td>
          </tr>
        </tbody>
      </table>
    </div>
  </div>
</template>

<style scoped>
.img-fluid {
  max-height: 750px; /* Maintain aspect ratio */
  display: block; /* Remove extra space below the image */
  margin: 0 auto; /* Center the image */
}
</style>

<script>
export default {
  name: 'Comp2',
  props: {},
};
</script>
