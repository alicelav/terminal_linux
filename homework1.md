1) Посмотреть где я:   pwd

2) Создать папку:   mkdir folder

3) Зайти в папку:   cd folder

4) Создать 3 папки:   mkdir folder1 folder2 folder3

5) Зайти в любую папку:   cd folder2

6) Создать 5 файлов (3 txt, 2 json):   touch file1.txt file2.txt file3.txt file4.json file5.json

7) Создать 3 папки:   mkdir folder1 folder2 folder3

8. Вывести список содержимого папки:   ls -la

9) + Открыть любой txt файл:   vim file1.txt

10) + написать туда что-нибудь, любой текст: hello world
                                             14.03.2022 
                                             today is sunny weather 
                                             goodbye

11) + сохранить и выйти: 
      Esc
      :qw
12) Выйти из папки на уровень выше:   cd ../

13) переместить любые 2 файла, которые вы создали, в любую другую папку:   mv folder2/file4.json folder2/file5.json folder1

14) скопировать любые 2 файла, которые вы создали, в любую другую папку:   cp folder2/file1.txt folder2/file2.txt folder1

15) Найти файл по имени:   find folder2/file5.json

16) просмотреть содержимое в реальном времени (команда grep) изучите как она работает:   tail -F file1.txt

17) вывести несколько первых строк из текстового файла:   head -n3 file1.txt  hello world
                                                                              14.03.2022
                                                                              today is sunny weather

18) вывести несколько последних строк из текстового файла:   tail -n3 file1.txt  14.03.2022
                                                                                 today is sunny weather 
                                                                                 goodbye

19) просмотреть содержимое длинного файла (команда less) изучите как она работает:   less long file1.txt
                                                                                     q

20) вывести дату и время:    date


Задание *

Отправить http запрос на сервер. http:// 162.55.220.72:5005/object_info_3?name=Vadim&age=32&salary=1000
Написать скрипт который выполнит автоматически пункты 3, 4, 5, 6, 7, 8, 13

Решение можно посмотреть [здесь](https://github.com/alicelav/terminal_linux/blob/main/homework2) и [здесь](https://github.com/alicelav/terminal_linux/blob/main/script_HW_1.sh)
