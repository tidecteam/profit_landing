<script>
  import downBtn from '../assets/down_button.svg'
  export let section;
</script>

<a class="down bounce" href={`#${section}`}>
  <img class="down_button" src={downBtn} alt="">
</a>