<template>
  <header>
    <nav class="navbar navbar-light bg-light shadow-sm">
      <div class="container-fluid">
        <a class="navbar-brand">
            <router-link to="/">
              <img alt="WalkerMods" class="logo" src="../assets/logo.png">
              </router-link>
                 WalkerMods
        </a>
        <div>
        <a class="p-2 text-dark"><router-link to="/">Home</router-link></a>
        <a class="p-2 text-dark"><router-link to="/About">About</router-link></a>
        <a class="p-2 text-dark"><router-link to="/Contact">Contact</router-link></a>
        </div>
      </div>
    </nav>
        
        

      
  </header>
</template>

<style scoped>
  .logo {
    height: 60px;
  }

  p {
     font-size: 30px;
    }

  nav {
     margin-left: auto;
     display: flex;
    }

     a {
     text-decoration: none;
     color: black;
    }
</style>

// For all active links
<style>
  

</style>