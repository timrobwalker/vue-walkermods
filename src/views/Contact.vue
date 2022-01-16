<template>
  <div class="contact">
    <h1>Contact</h1>
    <div class="container">
        <p>And so here we are. The beginning of it all. Fill in the form and we can start getting your bespoke console underway. 
           Payment is done through a separate portal (PayPal) but a ecommerce option will be implemented via this page at a later date.
        </p>
    </div>
    <div class="container">
            <div class="col col-md-6">
                <input type="text" class="form-control" placeholder="First Name">
            </div>
            <div class="col-md-6">
                <input type="text" class="form-control" placeholder="Last Name">
            </div>
            <div class="col-md-8">
                <input type="text" class="form-control" placeholder="Email Address">
            </div>
            <div class="col-md-12">
                <input type="text" class="form-control" placeholder="Home Address">
            </div>
            <div class="col-md-8">
                <input type="text" class="form-control" placeholder="County">
            </div>
            <div class="col-md-4">
                <input type="text" class="form-control" placeholder="Postcode">
            </div>
            <label for="buildSelect">What would you like built?</label>
            <div class="col-10">
                <select class="form-control" id="buildSelect">
                    <option>Gameboy Advance</option>
                    <option>Accessories</option>
                    <option>Gameboy Pocket</option>
                    <option>Gameboy Color</option>
                    <option>Other</option>
                </select>
            </div>
            <label for="additional">Additional notes, including specific specs to your console. Or just say hello!</label>
            <div class="col-12">
                <textarea class="form-control" id="additional" rows="5"></textarea>
            </div>
            <button type="submit" class="btn btn-primary">Submit</button>
    </div>
</div>

</template>

<style scoped>
  h1 {
      margin: 10px auto;
  }

  .container {
      display: flex;
      flex-wrap: wrap;
  }

  label {
      text-align: left;
  }

  button {
      margin: 5px 0;
  }

</style>