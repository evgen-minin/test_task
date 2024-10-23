# Число с максимальной суммой цифр

## Описание

Данная программа на Python принимает целые числа от пользователя и находит число с максимальной суммой цифр. Ввод чисел продолжается до тех пор, пока не будет введён 0. После этого программа выводит число, сумма цифр которого максимальна.

## Как работает программа

1. Пользователь вводит целые числа в консоли.
2. Программа обрабатывает каждое введённое число, вычисляя сумму его цифр.
3. Если введённое число имеет большую сумму цифр, чем ранее введённые числа, оно запоминается.
4. Когда пользователь вводит 0, программа завершает работу и выводит число с наибольшей суммой цифр.

## Как запустить

1. Убедитесь, что у вас установлен Python 3. Для этого введите в терминале:

    ```bash
    python3 --version
    ```

2. Скачайте или скопируйте файл с программой на ваш компьютер.

3. Сделайте файл исполняемым (Linux/MacOS):

    ```bash
    chmod +x имя_файла.py
    ```

4. Запустите программу:

    ```bash
    ./имя_файла.py
    ```

    Или просто выполните через Python:

    ```bash
    python3 имя_файла.py
    ```

## Функции

### `sum_of_digits(number: int) -> int`

Эта функция принимает целое число и возвращает сумму его цифр. Например, для числа `123` функция вернёт `6` (1 + 2 + 3).

### `find_number_with_max_digit_sum() -> None`

Основная функция программы. Принимает целые числа от пользователя до тех пор, пока не введён 0. После этого выводит число с наибольшей суммой цифр.

## Требования

- Python 3.x
- Утилита для выполнения скриптов (например, терминал или командная строка)




