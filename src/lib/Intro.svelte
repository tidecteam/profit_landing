<script>
  import profitLogo from '../assets/logo.png'
  import DownBtn from "./DownBtn.svelte"
</script>

<section id="intro" class="content intro">
  <div class="alinator">
    <img class="logo" src={profitLogo} alt="Profit Logo">
    <div class="presentation_text">
      <p>Bienvenido a Nuestra Comunidad</p>
      <p>⚒️ Estamos trabajando ⚒️</p>
    </div>
  </div>
  <DownBtn section={'who'}/>
</section>