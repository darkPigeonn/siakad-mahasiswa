<template>
  <nav class="navbar navbar-expand-lg navbar-dark p-3 bg-danger" id="headerNav">
    <div class="container-fluid">
      <a class="navbar-brand d-block d-lg-none" href="#">
        <img src="/assets/img/logo.png" height="50" />
      </a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavDropdown" aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
  
      <div class=" collapse navbar-collapse" id="navbarNavDropdown">
        <ul class="navbar-nav mx-auto d-flex align-content-bottom">
          <li class="nav-item">
            <a class="nav-link mx-2 active" aria-current="page" href="#">Beranda</a>
          </li>
          <li class="nav-item">
            <a class="nav-link mx-2" href="#">Products</a>
          </li>
          <li class="nav-item d-none d-lg-block">
            <a class="nav-link mx-2" href="#">
              <img src="/assets/img/logo.png" height="50" />
            </a>
          </li>
          <li class="nav-item">
            <a class="nav-link mx-2" href="#">Pricing</a>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link mx-2 dropdown-toggle" href="#" id="navbarDropdownMenuLink" role="button" data-bs-toggle="dropdown" aria-expanded="false">
              Company
            </a>
            <ul class="dropdown-menu" aria-labelledby="navbarDropdownMenuLink">
              <li><a class="dropdown-item" href="#">Blog</a></li>
              <li><a class="dropdown-item" href="#">About Us</a></li>
              <li><a class="dropdown-item" href="#">Contact us</a></li>
            </ul>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>