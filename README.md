*/Необходимо с помощью цикла for вывести следующие 11 строк в консоль:
0 – это ноль
1 – нечетное число
2 – четное число
3 – нечетное число
…
10 – четное число/*

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <title>Homework</title>
</head>

<body>
    <!--
Обязательное задание.
Необходимо с помощью цикла for вывести следующие 11 строк в консоль:
0 – это ноль
1 – нечетное число
2 – четное число
3 – нечетное число
…
10 – четное число
-->
    <script>
        "use strict";

        /**
        * Функция проверки четности числа
        * @param {number} a - число для проверки
        * @return {boolean} - результат проверки 
         */
        function isEven(a) {
            return a % 2 === 0;
        }

        for (let i = 0; i < 11; i++) {
            if (i === 0) {
                console.log(`${i} - это ноль`);
            } else if (isEven(i)) {
                console.log(`${i} - четное число`);
            } else {
                console.log(`${i} - нечетное число`);
            }
        }
    </script>
</body>

</html>

Дан массив [1, 2, 3, 4, 5, 6, 7]
Сделайте из этого массива следующий [1, 2, 3, 6, 7]

var arr = [1, 2, 3, 4, 5, 6, 7];
 for (var i = 0; i <= arr.length; i++){
     document.write('-' +arr[i]);
 }

Необходимо вывести горку в консоль (используя цикл for), как показано на рисунке, только у вашей горки должно быть 20 рядов, а не 5:

x
xx
xxx
xxxx
xxxxx

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <title>Homework</title>
</head>

<body>
 
    <script>
        "use strict";

        for (let i = 0; i < 10; console.log(i), i++){
            /* здесь пусто */
        }

    </script>
</body>

</html>
