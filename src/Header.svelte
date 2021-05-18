<script>

</script>

<div id="header">
  <img src='./img/netflix-logo.png' alt="netflix logo">
  <ul id="header-menu">
    <li>Home</li>
    <li>Series</li>
    <li>Peliculas</li>
    <li>Novedades</li>
    <li>Mi lista</li>
  </ul>
  <div class="search"><input type="text"></div>
</div>

<style>
  #header {
    position: absolute;
    left: 0;
    top: 0;
    height: 12vh;
    background-color: black;
    width: 100vw;
    display: flex;
    align-items: center;
    color: white;
    font-size: 24px;
  }

  #header img {
    width: 2rem;
    margin-left: 2rem;
  }

  li {
    text-decoration: none;
    list-style: none;
  }

  #header-menu {
    background-color: rgba(black, 0.8);
    z-index: 99;
  }

  #header-menu li:not(:nth-child(1)){
    display: none;
    cursor: pointer;
  }

  #header-menu:hover li{
    padding-left: 10px;
    cursor: pointer;
    display: block;

  }
</style>
