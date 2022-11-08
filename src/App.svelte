<script>
  import Intro from './lib/Intro.svelte'
  import Mission from './lib/Mission.svelte'
  import Who from './lib/Who.svelte'
  import Footer from './lib/Footer.svelte'

  function hashHandler() {
    window.history.pushState({}, 'Page Title', '/');
  }

  window.addEventListener('hashchange', hashHandler, false);
</script>

<main>
  <Intro />
  <Who />
  <Mission />
  <Footer />
</main>
