<script>
    export let name;
    const icons = [
        {
            name: "check-mark",
            path: "tick.jpg",
        },
        {
            name: "delete",
            path: "bin.jpg",
        },
    ];
    let icon = icons.find((item) => item.name === name);
</script>
    