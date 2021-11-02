<template>
<div class="main">
  <div class="container">
    <article class="">
      <h3>Order Summary</h3>
      <p>You can now listen to millions of songs, audiobooks, and podcasts on any device anywhere you like!</p>
    </article>

    <div class="plan">
      <article class="">
        <h5>Annual Plan</h5>
        <p>$59.99/year</p>

        <a href="#">Change</a>
      </article>
    </div>

    <div class="buttons">
      <button type="button" name="button">Proceed to Payment</button>
      <button type="button" name="button">Cancel Order</button>
    </div>
  </div>
</div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
h3 {
  font-family: 'Red Hat Display', sans-serif;
  font-weight: 900;
}
.main{
  display: flex;
  justify-content: center;
  align-items: center;
}
.container{
  width: 22rem;
  min-height: 33rem;
  border-radius: 4%;
  height: auto;
  background-color:	white;
}
</style>
