<template>
  <div class="container">
    <nav
      class="navbar is-full"
      role="navigation"
      aria-label="main navigation"
      style="background-color: #fff8f8"
    >
      <div class="navbar-brand">
        <div>
          <img src="../assets/icons/Syntech.png" height="110" width="110" />
        </div>
        <a
          class="navbar-item is-size-1 has-text-weight-bold"
          style="color: #002661"
          >SYNTECH</a
        >
        <a
          role="button"
          class="navbar-burger"
          aria-label="menu"
          aria-expanded="false"
          data-target="mainNavbar"
        >
          <span aria-hidden="true"></span>
          <span aria-hidden="true"></span>
          <span aria-hidden="true"></span>
        </a>
      </div>

      <div
        id="mainNavbar"
        class="navbar-menu is-full is-size-8 has-text-weight-semibold"
      >
        <div class="navbar-end">
          <div class="navbar-item is-hoverable">
            <a class="navbar-item"> Home </a>
          </div>

          <div class="navbar-item is-hoverable">
            <a class="navbar-item"> Events </a>
          </div>

          <div class="navbar-item is-hoverable">
            <a class="navbar-item"> Blog </a>
          </div>

          <div class="navbar-item is-hoverable">
            <a class="navbar-item"> About Us </a>
          </div>
        </div>
      </div>
    </nav>
  </div>
</template>
