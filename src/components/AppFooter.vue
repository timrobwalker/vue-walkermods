<template>
    <footer>
        <div class="row toprow">
            <div class="col-md-4">
                <p><b>Information</b></p>
                Delivery & Postage<br>
                Returns Policy<br>
                Terms & Conditions<br>
            </div>
            <div class="col-md-4">
                <p><b>Brands & Suppliers</b></p>
                <a href="http://www.deadpanrobot.co.uk/" title= "Deadpan Robot" target="_blank">Deadpan Robot</a><br>
                <a href="https://funnyplaying.com/" title="FunnyPlaying" target="_blank">FunnyPlaying</a><br>
                <a href="http://www.jellybellycustoms.com" title="Jellybelly Customs" target="_blank">Jellybelly Customs</a>
            </div>
            <div class="col-md-4">
                <p class="display">-</p>
                <a href="https://bennvenn.myshopify.com/" title="BennVenn" target="_blank">BennVenn</a><br>
                <a href="https://www.retromodding.com/" title="RetroModding" target="_blank">RetroModding</a><br>
                <a href="https://www.aliexpress.com/" title="AliExpress" target="_blank">AliExpress</a>
            </div>
        </div>
        <div class="row">
            <div class="col-6">
                <p class="copyright">WalkerMods &copy; {{ new Date().getFullYear() }}</p>
            </div>
            <div class="col-6">
              <a href="http://www.instagram.com/walkermods" title="WalkerMods Instagram" target="_blank">
                <i class="bi bi-instagram instagram"></i>
              </a>
              <a href="http://www.twitter.com/timrobwalker" title="Personal Twitter" target="_blank">
                <i class="bi bi-twitter twitter"></i>
              </a>
              <a href="https://reddit.com/r/GameboyMarketplace/" title="GameboyMarketPlace" target="_blank">
                <i class="bi bi-reddit reddit"></i>
              </a>
              <a title="Personal Facebook" target="_blank">
                <i class="bi bi-facebook facebook"></i>
              </a>
            </div>
            
        </div>
    </footer>
</template>

<style scoped>

footer {
    margin: 0 auto;
    width: 75vw;
}

.toprow {
    border-top: 1px solid #ccc;
    padding: 1.3rem 0 2.3rem 0;
}

.display {
    opacity: 0;
}

.instagram {
    color: red
}

.twitter {
    color: blue;
}

.reddit {
    color: orange;
}

.facebook {
    color: black
}

i:hover, a:hover {
    opacity: .6;
}

i {
    font-size: 4.5vw;
    margin-left: .7rem;
    text-shadow: 1px 1px 1px #ccc;
}

.copyright {
    font-size: 10px;
}

@media screen and (min-width: 900px) {
  i {
     font-size: 35px;
  }
}

p {
    font-size: 20px;
}

 a {
     text-decoration: none;
     color: black;
    }


</style>