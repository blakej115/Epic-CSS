<template>
  <header class="header">
    <div class="logo">
      <a href="#">
        <img src="../assets/images/logo.svg" alt="Epic CSS">
      </a>
    </div>
    <nav class="nav">
      <button class="menu" data-epic="menu">Menu</button>
      <ul>
        <li>
          <NuxtLink to="/">Home</NuxtLink>
        </li>
        <li>
          <NuxtLink to="/documentation/get-started">Get Started</NuxtLink>
        </li>
        <li>
          <NuxtLink to="/documentation">Documentation</NuxtLink>
        </li>
        <li>
          <NuxtLink to="/examples">Examples</NuxtLink>
        </li>
        <li>
          <a href="https://github.com/blakej115/Epic-CSS" target="_blank">
            <i class="fa-brands fa-github"></i>
          </a>
        </li>
      </ul>
    </nav>
  </header>
</template>