<template>
  <header class="header">
    <div class="logo">
      <a href="#">
        <h1>Epic CSS</h1>
      </a>
    </div>
    <nav class="nav">
      <button class="menu" data-epic="menu">Menu</button>
      <ul>
        <li>
          <NuxtLink to="/">Home</NuxtLink>
        </li>
        <li>
          <a href="#">Get Started</a>
        </li>
        <li>
          <a href="#">Documentation</a>
        </li>
        <li>
          <NuxtLink to="/examples">Examples</NuxtLink>
        </li>
        <li>
          <a href="#">Github</a>
        </li>
      </ul>
    </nav>
  </header>
</template>