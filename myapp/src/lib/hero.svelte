<script>
  import svelteLogo from '../assets/svelte.svg'
</script>

<div class="hero-container container">
  <div>
    <a href="https://svelte.dev" target="_blank" rel="noreferrer"> 
      <img src={svelteLogo} class="logo svelte" alt="Svelte Logo" />
    </a>
  </div>
  <h1>Francesco Santini</h1>

  <div class="card">
    <a href="#about"><span class="material-symbols-outlined notranslate">
      expand_more
    </span>
    </a>
  </div>

  <p class="cta">
    Reach me on <a href="https://github.com/santeenee">GitHub</a>
  </p>
</div>

<style>
  .logo {
    height: 6em;
    padding: 1.5em;
    will-change: filter;
  }
  .logo:hover {
    filter: drop-shadow(0 0 2em #646cffaa);
  }
  .logo.svelte:hover {
    filter: drop-shadow(0 0 2em #ff3e00aa);
  }
  .cta {
    color: #888;
  }
</style>