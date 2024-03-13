<svelte:head>

<title>Новости</title>
</svelte:head>
<div class="container">
    <h1>Новости в IT-технологиях</h1>
    <div class="blogposts">
        {#each blocks as page}
            <div class="post">
                <h2>{page.title}</h2>
                <p>{page.body}</p>
                <p class="readmore">
                    <a class="link" href={`/news/divs/${page.id}`}>
                    Подробнее...
                    </a>
                </p>
            </div>
        {/each}
    </div>
</div>

<script>
    import {blocks} from "./blocks";
</script>

<style>
    .container {
        margin: 100 px auto;
        max-width: 1250px;
        padding: 0 20px;
    }

    .blogposts {
        display: grid;
        grid-template-columns: 1fr 1fr;
        grid-gap: 30px;
    }

    .post {
        border: 1px solid purple;
        padding: 10px;
        box-shadow: 0 0 10px #eee;
    }

    .link {
        color: rgb(10,10,139);
    }
</style>