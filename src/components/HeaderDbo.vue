<template>
  <div class="wrapper">
    <div class="header-wrapper">
      <div class="logo-container">
        <img id="logo" height="70" width="310" src="@/assets/logo3.svg" alt="DBO">
      </div>
      <div class="nav">
        <ul class="nav-list">
          <li><a href="about">about</a></li>
          <li id="last-li"><a href="not about">about</a></li>
        </ul>
      </div>
      <div id="socials">
      </div>
    </div>
  </div>
</template>

<script>

</script>

<style scoped>


.header-wrapper {
  background-color: #111111; 
  display: flex;
  justify-content: space-between;
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
}

li {
  display: inline;
  padding-right: 0.3rem;
  align-self: center;
}

</style>



