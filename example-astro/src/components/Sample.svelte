<script>
  export let text = "";
  let name = "";
</script>

<input bind:value={name} />

<p>{name}</p>
<p>{text}</p>
