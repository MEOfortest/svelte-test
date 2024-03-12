<!--
<h1>А вот и я :)</h1>

<img src="pictures/myphoto.jpg" width="80%" alt="me" /> картинка почему-то не отображается
-->
<p>Я многое узнал за время обучения в Коде Будущего! Я научился много новому и теперь многое умею</p>

<p>Например, я могу сделать простенькую анимацию:</p>

    <div class="text-block"> ВРАЧ </div>

    <div class="text-block"> СТРОИТЕЛЬ </div>

    <div class="text-block"> ПОЛИЦЕЙСКИЙ </div>

    <div class="text-block"> МЕНЕДЖЕР </div>

<ul>
    <li>Ещё</li>
    <li>научился</li>
    <li>делать</li>
    <li>списки</li>
</ul>

<p>И писать разные химические формулы:</p>
<p>H<sub>2</sub> + CuO &rarr; Cu + H<sub>2</sub>O</p>
<p>H<sub>2</sub> + CuO &rarr; Cu + H<sub>2</sub>O</p>

<p>Пример таблицы со структурой</p>
<table>
    <thead>
        <tr>
            <th>Заголовок1</th>
            <th>Заголовок2</th>
            <th>Заголовок3</th>
        </tr>
    </thead>
    <tfoot>
        <tr>
            <td>Сумма1</td>
            <td>Сумма2</td>
            <td>Сумма3</td>
        </tr>
    </tfoot>
    <tbody>
        <tr>
            <td>Ячейка1</td>
            <td>Ячейка2</td>
            <td>Ячейка3</td>
        </tr>
        <tr>
            <td>Ячейка1</td>
            <td>Ячейка2</td>
            <td>Ячейка3</td>
        </tr>
        <tr>
            <td>Ячейка1</td>
            <td>Ячейка2</td>
            <td>Ячейка3</td>
        </tr>
    </tbody>
</table>

<style>
 p, ul, td {
    font-style: oblique;
    font-size: 30px;
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