<script lang="ts">
  import { link } from "svelte-spa-router";
</script>

<nav class="navbar" role="navigation" aria-label="main navigation">
  <div class="container">
    <div class="navbar-brand">
      <a class="navbar-item" alt="#" href="https://bulma.io">
        <h1 class="title is-4 has-text-link">The Lake</h1>
      </a>
      <a
        role="button"
        class="navbar-burger burger"
        aria-label="menu"
        aria-expanded="false"
        data-target="navbarBasicExample"
        alt="#"
        href="/">
        <span aria-hidden="true" />
        <span aria-hidden="true" />
        <span aria-hidden="true" />
      </a>
    </div>

    <div id="navbarBasicExample" class="navbar-menu">

      <div class="navbar-end">
        <a class="navbar-item has-text-link" href="/home" use:link>Home</a>
        <a class="navbar-item has-text-link" href="/documentation" use:link>
          Shop
        </a>
        <a class="navbar-item has-text-link" href="/documentation" use:link>
          Collections
        </a>
        <a class="navbar-item has-text-link" href="/documentation" use:link>
          Blog
        </a>
        <a class="navbar-item has-text-link" href="/documentation" use:link>
          Pages
        </a>
        <div
          class="navbar-item has-text-link has-dropdown is-hoverable is-primary">
          <a class="navbar-link" href="/home" use:link>Elements</a>
          <div class="navbar-dropdown">
            <a class="navbar-item has-text-link" href="/home" use:link>Home</a>
            <a class="navbar-item has-text-link" href="/documentation" use:link>
              Documentation
            </a>
          </div>
        </div>
      </div>
    </div>
  </div>
</nav>
