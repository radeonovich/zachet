# zachet

## cmp
Побайтово сравнивает содержимое двух файлов. 
Пример
text1.txt:
a
b
a
c
text2.txt:
a
b
f
c
cmp text1.txt text2.txt
Программа укажет 3 строку, номер 1.
Флаг -b укажет номер стройки и номер первого отличающегося символа и выведет его в обоих файлах
Флаг -l укажет все отличающиеся байты
Флаг -n позволит указать количество байтов, после проверки которых сравнение прекратится

## comm
Сравнивает упорядоченное содержимое двух файлов и выводит результат в 3 столбца: в первом уникальные строки для первого файла, 
во втором уникальные строки для второго файла, в третьем общие строки.
Пример

A.txt:
Alex
Michael
Robert
Paul

B.txt:
