<script>
    let count = 0;
    function increment() {
        count += 1;
    }
</script>

<button onclick={increment}>
    現在、クリック回数：{count}
</button>