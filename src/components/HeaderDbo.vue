<template>
  <div class="wrapper">
    <div class="header-wrapper">
      <div class="logo-container">
        <img id="logo" height="70" width="310" src="@/assets/logo3.svg" alt="DBO">
      </div>
      <div class="nav">
        <ul class="nav-list">
          <li><a href="https://instagram.com">art</a></li>
          <li><a href="https://soundcloud.com" id="last-element">music</a></li>
          <li><a href="stuff">about</a></li>
        </ul>
      </div>
      <div id="socials">
      </div>
    </div>
  </div>
  <div>

  </div>
</template>


<script>

</script>

<style scoped>

.header-wrapper {
  background-color: #001820; 
  display: flex;
  justify-content: space-between;
}

.header-wrapper {
  border-bottom: 3px solid #89223D;
}

#logo {
  padding-left: 2rem;
}

.nav {
  display: flex;
}

ul.nav-list {
  list-style-type: none;
  display: flex;
  justify-content: center;
  justify-items: center;
  font-family: dm-sans;
  padding-left: 2rem;
}

li {
  display: inline;
  padding-right: 0.3rem;
  align-self: center;
}

a {
  color: #22896E;
}

a:link {
  text-decoration: none;
}


a:hover,a#last-element:hover {
  color: #89223D;
}

a:visited {
  color: #22896E;
}

</style>



