<template lang="html">
  <div class="container">
    <div class="row">
      <div class="col-sm-10">
        <h1>Ready to buy?</h1>
        <hr>
        <router-link to="/" class="btn btn-primary">
          Back Home
        </router-link>
        <br><br>
        <div class="row">
          <div class="col-sm-6">
            <div class="">
              <h4>You are buying:</h4>
              <ul>
                <li>Book Title: <em>Book Title</em></li>
                <li>Amount: <em>$Book Price</em></li>
              </ul>
            </div>
            <div class="">
              <h4>Use this info for testing:</h4>
              <ul>
                <li>Card Number: 4242424242424242</li>
                <li>CVC Code: any three digits</li>
                <li>Expiration: any date in the future</li>
              </ul>
            </div>
          </div>
          <div class="col-sm-6">
            <h3>One time payment</h3>
            <br>
            <form>
              <div class="form-group">
                <label>Credit Card Info</label>
                <input type="text"
                        class="form-control"
                        placeholder="XXXXXXXXXXXXXX"
                        required>
              </div>
              <div class="form-group">
                <input type="text"
                        class="form-control"
                        placeholder="CVC"
                        required>
              </div>
              <div class="form-group">
                <label>Card Expiration Date</label>
                <input type="text"
                        class="form-control"
                        placeholder="MM/YY"
                        required>
              </div>
              <button class="btn btn-primary btn-block">Submit</button>
            </form>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
};
</script>

<style lang="css">
</style>
