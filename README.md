# PythonCalculator

# Slava is here

# Что нужно пофиксить? Списком внизу:

1. Записывать НОВЫЕ результаты в НОВУЮ строчку.

2. Облагородить вывод результатов в файл. Как пример, показывать сам пример, который нам предложил ввести пользователь и через знак "=" выводить результат на экран.

3. Организовать прекращение работы калькулятора. Как минимум при решении комплексных чисел этого нет

4. Сделать round при выводе результатов работы с float. Больно глаза режет

# Что поправили? Списком внизу:

1. Исправлена запись в файл results.txt для комплексных чисел:

    1.1) Все новые результаты теперь пишутся на следующей строчке;

    1.2) В файл сначала записывается исходные данные (каждое комплексное число в скобочках и знак операции между ними)

    1.3) При отрицательном значении мнимой части в файл записывалось РАНЬШЕ так: "-210.0" (без пробела). ТЕПЕРЬ: "- 210.0" (с пробелом).