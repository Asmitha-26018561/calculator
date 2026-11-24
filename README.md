# Ex.No:06 JavaScript Calculator
## Date:23.10.26
## AIM

To design and develop a simple calculator using HTML, CSS, and JavaScript to perform basic arithmetic operations such as addition, subtraction, multiplication, and division.

## ALGORITHM

1. Create an HTML page to design the calculator interface.
2. Create a display field to show the numbers and calculation results.
3. Create buttons for digits from 0 to 9 and arithmetic operators.
4. Use CSS to arrange and style the calculator buttons and display.
5. Write JavaScript functions to handle button clicks.
6. Store the entered numbers and operators in the calculator display.
7. Use JavaScript to evaluate the arithmetic expression.
8. Display the calculated result on the calculator screen.
9. Provide a clear button to reset the calculator.
10. Test the calculator with different arithmetic operations.

## PROGRAM
<html>
    <head>
        <title> CALCULATOR</title>
        <style>
            .calc{
                height: 600px;
                width: 500px;
                border-radius: 10px;
                border-color:rgb(0, 174, 255);
                border: 10px solid rgb(63, 140, 222);
                background-image:url(bg7.webp);
                background-repeat: no-repeat;
                background-size: cover;
             }
            body{
                display: flex;
                justify-content: center;
                align-items: center;
                height: 600px;
                background-image: url(bg6.jpg);
                background-repeat: no-repeat;
                background-size: cover;

            }
            h1{
                text-align: center;
                text-transform: capitalize;
                text-shadow: 5px;
                text-decoration-color:black;
            }
            .calculator{
                width: 400px;
                height: 30px;
                text-align: right;
                font-size: 20px;
                margin: 30px auto;
                
                padding: 20px;
                margin-bottom: 30px;
                border: 4px solid;
                border-color: blueviolet;
                margin-right: 20px;
                margin-left: 50px;
                
            }
            .row input[type="button"]{
                width: 80px;
                height: 75px;
                margin: 2px;
                font-size: 18px;
                border: 2px solid;
                border-color: blueviolet;
                
            
            }
            .row{
                display: flex;
                justify-content: center;
                gap: 8px;
                margin-bottom: 8px;
            }
            .row input[value="="]{
                background-color: green;
            }
            .row input[value="C"]{
                background-color: red;
            }
        </style>
    
    </head>
    <body>
        <div class="calc">
            <h1>SIMPLE CALCULATOR</h1>
            <input type="text"class="calculator" id="cal">
            <div class="row">
                <input type="button" value="1" onclick="cal.value += '1'">
                <input type="button" value="2" onclick="cal.value += '2'">
                <input type="button" value="3" onclick="cal.value += '3'">
                <input type="button" value="+" onclick="cal.value += '+'">

            </div>
            <div class="row">
                <input type="button" value="4" onclick="cal.value += '4'">
                <input type="button" value="5" onclick="cal.value += '5'">
                <input type="button" value="6" onclick="cal.value += '6'">
                <input type="button" value="-" onclick="cal.value += '-'">

            </div>
             <div class="row">
                <input type="button" value="7" onclick="cal.value += '7'">
                <input type="button" value="8" onclick="cal.value += '8'">
                <input type="button" value="9" onclick="cal.value += '9'">
                <input type="button" value="*" onclick="cal.value += '*'">

            </div>
             <div class="row">
                <input type="button" value="0" onclick="cal.value += '0'">
                <input type="button" value="=" onclick="cal.value = eval(cal.value)">
                <input type="button" value="C" onclick="cal.value = ''">
                <input type="button" value="/" onclick="cal.value = '/'">

            </div>
        </div>
    </body>
</html>



## OUTPUT
![alt text](../exp6.png)


## RESULT

Thus, a JavaScript-based calculator was successfully designed and developed to perform basic arithmetic operations using HTML, CSS, and JavaScript.

## RESULT

Thus, a JavaScript-based calculator was successfully designed and developed to perform basic arithmetic operations using HTML, CSS, and JavaScript.
