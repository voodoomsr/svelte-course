<script>
  let name = 'Svelte';
  let src = 'http://picsum.com/200/200';
  let string = 'some <strong>bold</strong> text'
</script>


<img {src} alt='Some text {name}' />
<h1>Hello {name.toUpperCase()}</h1>
<p>{@html string}</p>
<style>
  h1 {
    color: red;
  }
</style>