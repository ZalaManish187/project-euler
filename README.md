## Problems Solved:
- Problem 1: Multiples of 3 or 5
- Problem 2: Even Fibonacci numbers
- Code : <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <button onclick="fibo()">fibonacci series Sum</button>
    <p id="output"></p>
    <script>
        function fibo(){
          
            let result = " ";
            let a = 1;
            let b = 2;
            let sum = 0;

            while(a < 4000000){
                result += a + "<br>";
                if(a % 2 == 0){
                    sum += a;
                }
                
                let c = a + b;
                a = b;
                b = c;
            }
            document.getElementById("output").innerHTML = sum;
        }
    </script>
</body>
</html>
- Problem 3: Largest prime factor
- Problem 7: 10001st prime
