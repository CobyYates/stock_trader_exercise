<template>
<div>
  <nav class="navbar navbar-default">
      <div class="container-fluid">
          <div class="navbar-header">
                <router-link to="/" class="navbar-brand">Stock Trader</router-link> 
          </div>
 
  <div class="collapse navbar-collapse">
    <ul class="nav navbar-nav">
        <router-link to="/portfolio" activeClass="active" tag="li"><a>Portfolio</a></router-link>
        <router-link to="/stocks" activeClass="active" tag="li"><a>Stocks</a></router-link>
    </ul>
   <ul class="nav navbar-nav navbar-right">
       <li><a href="#">End Day</a></li>
       <li class="dropdown">
        <a 
            class="nav-link dropdown-toggle" 
            href="#" 
            id="navbarDropdown" 
            role="button" 
            data-toggle="dropdown" 
            aria-haspopup="true" 
            aria-expanded="false">
          Save & Load
        </a>
        <div class="dropdown-menu" aria-labelledby="navbarDropdown">
          <a class="dropdown-item" href="#">Save Data</a>
          <a class="dropdown-item" href="#">Load Data</a>
        </div>
      </li>
   </ul>
  </div>
  </div>
</nav>
</div>
  
</template>

<script>
export default {

}
</script>

<style>

</style>