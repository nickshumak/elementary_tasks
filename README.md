# elementary_tasks
Python

SoftServe Academy 
Dp-128 TAQC

 Elementary Tasks
Общие требования
 -	При передаче некорректных параметров на исполнение приложение не должно завершать работу сбоем.
 -	Запуск без параметров выводит инструкции по использованию программы.
 -	Параметры передаются в порядке, приведённом в описании задания.
Задания	
  
  1.	Шахматная доска
Вывести шахматную доску с заданными размерами высоты и ширины, по принципу:
*  *  *  *  *  *
  *  *  *  *  *  *
*  *  *  *  *  *
  *  *  *  *  *  *
Программа запускается через вызов главного класса с параметрами.
  
  2.	Анализ конвертов
Есть два конверта со сторонами (a,b) и (c,d) определить, можно ли один конверт вложить в другой. Программа должна обрабатывать ввод чисел с плавающей точкой. Программа спрашивает у пользователя размеры конвертов по одному параметру за раз. После каждого подсчёта программа спрашивает у пользователя хочет ли он продолжить. Если пользователь ответит “y” или “yes” (без учёта регистра), программа продолжает работу сначала, в противном случае – завершает выполнение.
  
  3.	Сортировка треугольников
Разработать консольную программу, выполняющую вывод треугольников в порядке убывания их площади. После добавления каждого нового треугольника программа спрашивает, хочет ли пользователь добавить ещё один. Если пользователь ответит “y” или “yes” (без учёта регистра), программа попросит ввести данные для ещё одного треугольника, в противном случае – выводит результат в консоль.

  •	Расчёт площади треугольника должен производится по формуле Герона.
•	Каждый треугольник определяется именем и длинами его сторон. 
Формат ввода (разделитель - запятая): 
<имя>, <длина стороны>, <длина стороны>, <длина стороны>
•	Приложение должно обрабатывать ввод чисел с плавающей точкой.
•	Ввод должен быть нечувствителен к регистру, пробелам, табам.
•	Вывод данных должен быть следующем примере:
============= Triangles list: ===============
[Triangle first]: 17.23 сm
[Triangle 22]: 13 cm
[Triangle 1]: 1.5 cm
  
  4.	Файловый парсер
Нужно написать программу, которая будет иметь два режима:
-	Считать количество вхождений строки в текстовом файле. 
-	Делать замену строки на другую в указанном файле
Программа должна принимать аргументы на вход при запуске:
-	<путь к файлу> <строка для подсчёта>
-	<путь к файлу> <строка для поиска> <строка для замены>
 
  5.	Число в пропись
Нужно преобразовать целое число в прописной вариант: 12 – двенадцать. Программа запускается через вызов главного класса с параметрами.
  
  6.	Счастливые билеты
Счастливые билеты.
Есть 2 способа подсчёта счастливых билетов:
- Московский — если на автобусном билете напечатано шестизначное число, и сумма первых трёх цифр равна сумме последних трёх, то этот билет считается счастливым.
- Ленинградский, или Питерский — если сумма чётных цифр билета равна сумме нечётных цифр билета, то билет считается счастливым.
Задача:
Номер билета - шестизначное число. Нужно написать консольное приложение, которое может посчитать количество счастливых билетов. Для выбора алгоритма подсчёта читается текстовый файл. Путь к текстовому файлу задаётся в консоли после запуска программы. Индикаторы алгоритмов:
- слово 'Moskow'
- слово 'Piter'
После задания всех необходимых параметров, программа в консоль должна вывести количество счастливых билетов для указанного способа подсчёта.

  7.	Числовая последовательность
Программа выводит ряд натуральных чисел через запятую, квадрат которых меньше заданного n. Программа запускается через вызов главного класса с параметрами.
  
  8.	Ряд Фибоначчи для диапазона
Программа позволяет вывести все числа Фибоначчи, которые находятся в указанном диапазоне. Диапазон задаётся двумя аргументами при вызове главного класса. Числа выводятся через запятую по возрастанию.


