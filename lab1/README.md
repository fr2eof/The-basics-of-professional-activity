# Лабораторная работа №1 

1. Создать приведенное в варианте дерево каталогов и файлов с содержимым. В качестве корня дерева использовать каталог lab0 своего домашнего каталога. Для создания и навигации по дереву использовать команды: mkdir, echo, cat, touch, ls, pwd, cd, more, cp, rm, rmdir, mv.
![alt text](taskText.png)
 
2. Установить согласно заданию права на файлы и каталоги при помощи команды chmod, используя различные способы указания прав.
•	cherubi4: права 551
•	cherrim: rw-r-----
•	roserade: ---r--r--
•	butterfree: владелец должен читать и записывать файл; группа-владелец должна записывать файл; остальные пользователи должны не иметь никаких прав
•	golem: права 400
•	masquerain: права 305
•	hariyama: r-----r--
•	murkrow1: права 660
•	ninjask2: права 004
•	patrat9: -wx--x--x
•	metang: rw----r--
•	meganium: владелец должен читать и записывать файл; группа-владелец должна записывать файл; остальные пользователи должны не иметь никаких прав
•	blastoise: rwx-wxrwx
•	electivire: r-----r--
•	sunflora: права 064
•	pelipper: r-x-w-r--
•	pidgey5: владелец должен не иметь никаких прав; группа-владелец должна читать файл; остальные пользователи должны читать и записывать файл
•	purrloin2: владелец должен читать директорию и переходить в нее; группа-владелец должна только переходить в директорию; остальные пользователи должны записывать директорию и переходить в нее
•	electabuzz: права 644
•	venomoth: права 770
•	weepinbell: права 600
•	kirlia: права 444
•	bellsprout: rw--w----
•	ledyba: владелец должен читать и записывать файл; группа-владелец должна читать файл; остальные пользователи должны не иметь никаких прав

3. Скопировать часть дерева и создать ссылки внутри дерева согласно заданию при помощи команд cp и ln, а также комманды cat и перенаправления ввода-вывода.
•	создать символическую ссылку c именем Copy_48 на директорию cherubi4 в каталоге lab0
•	скопировать файл pidgey5 в директорию lab0/purrloin2/venomoth
•	скопировать содержимое файла pidgey5 в новый файл lab0/purrloin2/weepinbellpidgey
•	cоздать символическую ссылку для файла ninjask2 с именем lab0/patrat9/sunfloraninjask
•	cоздать жесткую ссылку для файла pidgey5 с именем lab0/purrloin2/bellsproutpidgey
•	скопировать рекурсивно директорию patrat9 в директорию lab0/patrat9/pelipper
•	объеденить содержимое файлов lab0/purrloin2/weepinbell, lab0/cherubi4/cherrim, в новый файл lab0/pidgey5_19

4. Используя команды cat, wc, ls, head, tail, echo, sort, grep выполнить в соответствии с вариантом задания поиск и фильтрацию файлов, каталогов и содержащихся в них данных.
•	Подсчитать количество строк содержимого файлов: cherrim, roserade, butterfree, golem, hariyama, отсортировать вывод по уменьшению количества, подавить вывод ошибок доступа
•	Вывести рекурсивно список имен и атрибутов файлов в директории lab0, начинающихся на символ 'b', список отсортировать по возрастанию даты изменения записи о файле, подавить вывод ошибок доступа
•	Рекурсивно вывести содержимое файлов с номерами строк из директории lab0, имя которых начинается на 'm', строки отсортировать по имени a->z, ошибки доступа перенаправить в файл в директории /tmp
•	Подсчитать количество символов содержимого файлов: butterfree, golem, hariyama, metang, meganium, electivire, sunflora, electabuzz, weepinbell, kirlia, результат записать в файл в директории /tmp, ошибки доступа перенаправить в файл в директории /tmp
•	Вывести три первых элемента рекурсивного списка имен и атрибутов файлов в директории lab0, заканчивающихся на символ '2', список отсортировать по убыванию размера, подавить вывод ошибок доступа
•	Вывести рекурсивно список имен и атрибутов файлов в директории cherubi4, список отсортировать по убыванию даты доступа к файлу, подавить вывод ошибок доступа

5. Выполнить удаление файлов и каталогов при помощи команд rm и rmdir согласно варианту задания.
•	Удалить файл ninjask2
•	Удалить файл lab0/purrloin2/ledyba
•	удалить символические ссылки lab0/patrat9/sunfloraninja*
•	удалить жесткие ссылки lab0/purrloin2/bellsproutpidg*
•	Удалить директорию lab0/cherubi4/masquerain
•	Удалить директорию cherubi4
 
