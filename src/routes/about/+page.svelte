<h1>А вот и я :)</h1>

<img src="pictures/myphoto.jpg" alt="me" />

<p>Я многое узнал за время обучения в Коде Будущего! Я научился много новому и теперь многое умею</p>

<p>Например, я могу сделать простенькую анимацию:</p>

    <div class="text-block"> ВРАЧ </div>

    <div class="text-block"> СТРОИТЕЛЬ </div>

    <div class="text-block"> ПОЛИЦЕЙСКИЙ </div>

    <div class="text-block"> МЕНЕДЖЕР </div>

<style>
 p {
    font-style: oblique;
    font-size: 20px;
    color: blue;
 }

 .text-block {
    margin: 20px 20px 70px 50px;
    font-size: 40px;
    text-align: center;
    background-color: olive;
    width: 21vw;
    color: red;
    animation: myAnim 2s linear alternate infinite;
}

@keyframes myAnim {
    from {
        margin-left: 600px;
    }

    to {
        margin-bottom: 150px;
    }
}
</style>