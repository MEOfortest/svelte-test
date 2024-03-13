<div class="container">
    <a href="/news">Вернуться назад</a>
    <slot />
</div>

<style>
    .container {
        margin: 70px auto;
        width: 80%;
        padding: 0 20px;
    }

    a {
        border: 1px solid black;
        padding: 3px;
    }
</style>