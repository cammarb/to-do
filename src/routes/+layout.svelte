<script>
    import "../app.css";
</script>

<nav class="px-2 sm:px-4 py-2.5 sticky w-full z-20 top-0 left-0 border-b bg-white border-gray-200 text-neutral-900
 dark:bg-neutral-900 dark:border-gray-600 dark:text-neutral-200">
  <div class="logo">
    <a href="/">
        <img src="%sveltekit.assets%/favicon.png" alt="To-Do website logo">
    </a>
  </div>
  <div class="nav-items">

  </div>
</nav>
  

<div class="container px-4 py-3">
    <slot />
</div>