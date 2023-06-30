<template class="main">
    <nav class="navbar navbar-expand-lg">
          <div class="container-fluid">
            <img src="https://i.postimg.cc/653rLJmj/1686573555689-thumbnail.jpg" class="logo-img">
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavDropdown" aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
              <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse bg-black" id="navbarNavDropdown">
                <ul class="navbar-nav">
                  <li class="nav-item dropdown">
                    <a class="nav-link dropdown-toggle bg-black" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                      Dropdown link
                    </a>
                    <ul class="dropdown-menu bg-black">
                      <li><router-link class="dropdown-item" to="/product">Products </router-link></li>
                      <li><router-link class="dropdown-item" to="./contact.html">Contact page</router-link></li>
                      <li><router-link class="dropdown-item" to="./about.html">About</router-link></li>
                      <li><router-link class="dropdown-item" to="./admin.html">Admin Page</router-link></li>
                    </ul>
                  </li>
                </ul>
              </div>
            </div>
          </nav>
</template>
<style>
.main {
    background-color: black;
}
.logo-img {
    height: 80px;
    aspect-ratio:6/7;
    object-fit: contain;
}
.navbar-toggler {
    background-color: wheat!important;
}
.nav-link {
    color: wheat !important;
}
a {
    color: wheat !important;
}

</style>