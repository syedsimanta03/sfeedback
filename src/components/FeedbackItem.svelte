<script>
import Card from "./Card.svelte";


  export let item
</script>


<Card>
  <div class="num-display">{item.rating}</div>
  <div class="close">X</div>
  <div class="text-display">{item.text}</div>
</Card>
