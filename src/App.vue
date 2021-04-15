<template>
    <nav>
      <div class="nav-wrapper brown darken-1">
        <div class="layout">
          <a href="#!" class="brand-logo">Logo</a>
          <ul class="right hide-on-med-and-down">
            <li><router-link to="/"><i class="material-icons right">view_module</i>Home</router-link></li>
            <li><router-link to="/search"><i class="material-icons left">search</i>Search movies</router-link></li>
          </ul>
        </div>
      </div>
    </nav>
    <router-view/>
</template>

<style lang="scss">
@import '~materialize-css/dist/css/materialize.min.css';

.nav-wrapper > .layout {
  padding: 0 20px;
}

</style>
