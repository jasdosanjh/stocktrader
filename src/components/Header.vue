<template>
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <router-link to="/" class="navbar-brand" href="#">Stock Trader</router-link>
    
    <div class="collapse navbar-collapse">
      <ul class="navbar-nav mr-auto">
          <router-link to="/portfolio" activeClass="active" tag="li"><a>Portfolio</a></router-link>
          <router-link to="/stocks" activeClass="active" tag="li"><a>Stocks</a></router-link>
      </ul>
      <ul class="navbar-nav navbar-right">
        <li class="nav-item"><a class="nav-link" href="#">End Day</a></li>
        <li class="nav-item dropdown">
        <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">Save & Load <span class="caret"></span></a>
        <div class="dropdown-menu" aria-labelledby="navbarDropdown">
          <a class="dropdown-item" href="#">Save Data</a>
          <a class="dropdown-item" href="#">Load Data</a>
        </div>
      </li>
      </ul>
      </form>
    </div>
  </nav>
</template>

<style>
    li {
        padding: 0 10px;
    }
    a {
        color: black;
    }

    a:hover {
        color: black;
        text-decoration: none;
    }
</style>