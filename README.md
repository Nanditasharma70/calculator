# calculator
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Calculator</title>
    <link rel="stylesheet" href="style.css">
    <script src="script.js" defer></script>
</head>
<body>
    <div id="calculator">
        <div class="calculator-grid">
        <div class="output">
        <div data-previous-operand class="previous-operand"></div>
            <div data-current-operand class="current-operand"></div>
        </div>
        <input type="text" id="display" disabled/>
        <br>
        <button data-all-clear id="ac" class="operator">AC</button>
        <button data-delete id="de" class="operator">DE</button>
        <button data-operation id="." class="operator">.</button>
        <button data-operation id="/" class="operator">/</button>
        <br>
        <button data-number id="7" >7</button>
        <button  data-number id="8" >8</button>
        <button data-number id="9" >9</button>
        <button data-operation id="*" class="operator">*</button>
        <br>
        <button data-number id="4" >4</button>
        <button data-number id="5" >5</button>
        <button  data-numberid="6" >6</button>
        <button data-operation id="-" class="operator">-</button>
        <br>
        <button data-number id="1" >1</button>
        <button  data-number id="2" >2</button>
        <button  data-number   id="3" >3</button>
        <button data-number data-operation id="+" class="operator">+</button>
        <br>
        <button id="0" >0</button>
        <button id="00" >00</button>
        <button data-equals id="=" class="equal">=</button>
    </div>
</div>
</body>
</html>
