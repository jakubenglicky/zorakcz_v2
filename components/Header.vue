<template>
  <header>
    <nav class="click-dropdown">
      <div class="navbar-brand">
        <nuxt-link to="/"><img src="img/logo.png"></nuxt-link>
      </div>
      <button class="navbar-toggler open-drop"><span></span></button>
      <div class="navbar-content click-dropdown-content">
        <ul>
          <li>
            <nuxt-link class="close-drop" to="/">Úvod</nuxt-link>
          </li>
          <li>
            <a href="#projekty" class="close-drop">Realizované projekty</a>
          </li>
          <li>
            <a href="#o-nas" class="close-drop">O nás</a>
          </li>
          <li>
            <a href="#kontakt" class="close-drop">Kontakt</a>
          </li>
        </ul>
      </div>

    </nav>
  </header>
</template>
