<svelte:head>
<title>Павел Красин</title>
</svelte:head>

<div class="container">
    <div class="info">
        <div class="animate-background">
            <div class="container info-container">
                <div class="info-text">
                    <h1>
                        <p class="animate-text-1">Добро пожаловать на мой небольшой сайт!</p>
                    </h1>
                </div>
                <h2 class="subtitle">
                    Я учусь программированию и теперь я умею делать много разных вещей! А сейчас я пытаюсь создать сайт с помощью фреймворка Svelte Js. Можете посмотреть, что из этого получилось!</h2>
            </div>
        </div>
    </div>
</div>

<div class="background-div"></div>

<style>
    .info {
        text-align: center;
        position: relative;
    }

    .info-container {
        height: 100%;
        display: flex;
        flex-direction: column;
        justify-content: center;
        text-align: left;
        align-items: start;
    }

    .container {
        max-width: 1400px;
        margin: 50px 0 0 2.5rem;
    }

    .info h1 {
        font-size: 3rem;
        margin: 0;
    }

    .info h1 p {
        position: relative;
        font: inherit;
        margin: 0;
        text-align: left;
        line-height: 130%;
        width: fit-content;
        font-weight: 700;
        letter-spacing: -0.03em;
    }

    .info h2 {
        font-weight: 200;
        margin-top: 0.50rem;
    }
    
    .background-div {
        background-color: lightgray;
        width: 100%;
        height: 60vh;
        margin: -160px auto;
    }
</style>
