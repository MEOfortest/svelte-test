<nav>
    <div class="nav-container">
        <a href="/" class="nav-logo" title="Back to Homepage">Павел Красин</a>
        <div class="nav-links">
            {#if nav.isShow}
            <a href={nav.href} class="link">{nav.title}</a>
            {/if}
        </div>
    </div>
</nav>

<div class="container">
    <!--Pages will be injected below-->
    <slot></slot>
</div>

<script>
    const nav = [
        {
         title: "Обо мне",
         href: "/about",
         isShow: true,
        },
        {
         title: "Блог",
         href: "/blog",
         isShow: true,
        },
        {
         title: "Портфолио",
         href: "/project",
         isShow: true,
        },
        {
         title: "Конакты",
         href: "/contacts",
         isShow: true,
        },
        {
         title: "temp",
         href: "/temp",
         isShow: false,
        },
    ]
</script>

<style>
    .container {
        max-width: 1400px;
        margin: 50px auto;
    }
</style>