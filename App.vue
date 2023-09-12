<script setup>

</script>

<template>
  <head>
    <title>My Portfolio</title>
    <link rel="icon" type="image/x-icon" href="">
  </head>
  <header>
    <div>
      <nav>
        <ul>
          <li class="title">My Portfolio</li>
          <li><RouterLink to="/">Home</RouterLink></li>
          <li><RouterLink to="/about">More</RouterLink></li>
          <!-- <li><RouterLink to="/contact">Contact</RouterLink></li> -->
        </ul> 
      </nav>
    </div>
  </header>
  <footer>
      &copy; 2023 My Portfolio
  </footer>
  <RouterView />
</template>

<style scoped>

.title{
  font-family: Bradley Hand, cursive;
  color: azure;
  text-align: center;
  display: block;
  padding: 20px 25px;
}

nav {
  font-family: Monospace, serif;
}

ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
  overflow: hidden;
  background-color: #333;
}

li {
  float: left;
}

li a {
  display: block;
  color: white;
  text-align: center;
  padding: 20px 25px;
  text-decoration: none;
}

li a:hover {
  background-color: #111;
}


footer{
  position: fixed;
  left: 0;
  bottom: 0;
  width: 100%;
  background-color: gray;
  color: white;
  text-align: center;
}


</style>
