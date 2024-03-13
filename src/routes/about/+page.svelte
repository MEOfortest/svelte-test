<h1>А вот и я :)</h1>

<img src="./img/myphoto.jpg" width="80%" alt="me" /> 
<img src="../img/scheme.webp" width="600px" alt="she" /> 

<p>Я многое узнал за время обучения в Коде Будущего! Я научился много новому и теперь многое умею</p>

<p>Например, я могу сделать простенькую анимацию:</p>

    <div class="text-block"> ПРОГРАММИСТ </div>

    <div class="text-block"> ГЕЙМ-ДИЗАЙНЕР </div>

    <div class="text-block"> ХУДОЖНИК </div>

    <div class="text-block"> ДИРЕКТОР </div>

<ul>
    <li>Ещё</li>
    <li>научился</li>
    <li>делать</li>
    <li>списки</li>
</ul>

<p class="chemistry">И писать разные химические формулы:</p>
<p class="chemistry">H<sub>2</sub> + CuO &rarr; Cu + H<sub>2</sub>O</p>
<p class="chemistry">K<sub>2</sub>O + N<sub>2</sub>O<sub>5</sub> &rarr; KNO<sub>3</sub></p>
<p class="chemistry">HGo &rarr; Cu + HG + O<sub>2</sub></p>
<p class="chemistry">KClO<sub>3</sub> &rarr; KCl + O<sub>2</sub>O</p>

<p>Также умею создавать таблицы:</p>
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
 p, ul {
    font-style: oblique;
    font-size: 30px;
    color: blue;
 }

 table {
    border-top: 3px solid grey;
    border-bottom: 3px solid grey;
    border-collapse: collapse;
    width: 500px;
    table-layout: fixed;
 }

 td, th {
    font-style: italic;
    font-size: 25px;
    color: purple;
    border: 1px solid grey;
    padding: 10px;
 }

 .chemistry {
    font-style: italic;
    font-size: 30px;
    color: orange;
 }

 .text-block {
    margin: 20px 20px 70px 50px;
    font-size: 40px;
    text-align: center;
    background-color: olive;
    width: 21vw;
    color: red;
    border: 2px solid blue;
    animation: myAnim 3s linear alternate infinite;
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