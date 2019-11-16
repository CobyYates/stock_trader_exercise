<template>
  <div class="col-sm-6 col-md-4">
    <div class="card text-white bg-dark mb-3" style="max-width: 18rem;">
      <div class="card-header">
          {{ stock.name }}
          <small>Price: {{ stock.price }}</small>
          </div>
      <div class="card-body">
        <div class="pull-left">
            <input 
                type="number"
                class="form-control"
                placeholder="Quantity"
                v-model="quantity">
        </div>
        <div class="pull-right">
            <button 
                class="btn btn-success">Buy</button>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
    props: ['stock'],
    data() {
        return {
            quantity: 0
        }
    }
};
</script>

<style></style>
