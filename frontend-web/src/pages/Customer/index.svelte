<script>
    $: test = 0
    $: test_name = ''
</script>

<h1>Customer Home Page</h1>

<input bind:value={test} Placeholder="Your Input" />

<a href={`/Customer/${test}`}>Let's GO id {test}</a>
