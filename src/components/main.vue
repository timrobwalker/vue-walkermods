<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      Welcome to <b>WalkerMods</b> - a bespoke games console modification company based in the UK.<br>
      Owned by Timothy Walker and
      specialises in Nintendo consoles and accessories.
    </p>
  
    <h3>Favourites</h3>
      <div class="card-deck mb-3 text-center">
        <div class="card mb-4 shadow-sm">
          <div class="card-header">
            <h5>Gameboy Advance</h5>
          </div>
          <div class="card-body">
            <small class="text-muted">From</small><h1>£100</h1>
            <ul class="list-unstyled mt-3 mb-3">
              <li>Customizable buttons & shells</li>
              <li>AGS-101 & IPS screen installation</li>
              <li>Tempered glass lens with custom designs</li>
              <li>Rechargeable battery</li>
            </ul>
            <button type="button" class="btn btn-lg btn-block btn-outline-primary">Contact Me</button>
          </div>
        </div>
         <div class="card mb-4 shadow-sm">
          <div class="card-header">
            <h5>Controllers</h5>  
          </div>
          <div class="card-body">
            <small class="text-muted">From</small><h1>£45</h1>
            <ul class="list-unstyled mt-3 mb-3">
              <li>Reshelling</li>
              <li>D-Pad replacement</li>
              <li>Fixing joycon drift</li>
              <li>Including Gamecube & N64</li>
            </ul>
            <button type="button" class="btn btn-lg btn-block btn-primary">Let's Build</button>
          </div>
        </div>
         <div class="card mb-4 shadow-sm">
          <div class="card-header">
            <h5>Gameboy Pocket & Color</h5>
          </div>
          <div class="card-body">
            <small class="text-muted">From</small><h1>£90</h1>
            <ul class="list-unstyled mt-3 mb-3">
              <li>Customizable buttons & shells</li>
              <li>McWill, FreckleShack & IPS screen installation</li>
              <li>Scratch-resistant glass lenses</li>
              <li>"Touch" screen brightness</li>
            </ul>
            <button type="button" class="btn btn-lg btn-block btn-primary">Click To Start</button>
          </div>
        </div>
      </div>
      <p class="blurb">For examples of my work as well as more information about me and the business, <br>check out my About page. If you have an inquiry, 
        or just fancy a chat, drop me a line on my Contact page.</p>
  </div>
</template>

<script>
export default {
  name: 'main',
  props: {
    msg: String
  }
}
</script>


<style scoped>

.blurb {
   margin-bottom: 40px;

}

h3 {
  margin: 30px 0;
}

.card-header {
  padding: 1rem 1.5rem;

}

a {
  color: red;
}

.card-deck {
  display: flex;
  flex-flow: row wrap;
  margin: 0 auto;
  justify-content: center;
  max-width: 80%;
}

.card {
  margin: 0 auto;
}

ul {
  list-style-type: none;
  padding: 0;
}

a {
  color: #42b983;
}
</style>
