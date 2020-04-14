<template>
  <header>
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
      <a
        class="navbar-brand"
        href="#"
      >NuxtJS</a>
        <div class="collapse navbar-collapse">
          <ul class="navbar-nav mr-auto">
            <li class="nav-item">
              <nuxt-link
                exact
                class="nav-link"
                to="/"
                active-class="active"
              >Home</nuxt-link>
            </li>
            <li class="nav-item">
              <nuxt-link
                class="nav-link"
                no-prefetch
                to="/users"
                active-class="active"
              >Users</nuxt-link>
            </li>
            <li class="nav-item">
              <nuxt-link no-prefetch to="/about" active-class="active" class="nav-link">About</nuxt-link>
            </li>

            <li class="nav-item">
              <nuxt-link no-prefetch to="/login" active-class="active" class="nav-link">Login</nuxt-link>
            </li>
          </ul>
        </div>
    </nav>
  </header>
</template>