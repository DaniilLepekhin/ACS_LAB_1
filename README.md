# Архитектура вычислительных систем. Лабораторная 1.   
## Лепёхин Даниил. ИС-841  
### Задание: Написать bash-скрипт, который выводит на экран характеристики ПК.  

AWK - утилита предназначенная для простых, механических и вычислительных манипуляций над данными.
AWK утилита позволяет не писать утомительные программы для несложных операций.

В задании для нахождения характеристик ПК использовались следующие утилиты командной строки:  
  1) date - для вывода даты и времены;  
  2) whoami - для вывода имени учетной записи;  
  3) hostname - для вывода доменного имени ПК;  
  4) lscpu - для вывода информации о процессоре;  
  5) free - для вывода информации о памяти;  
  6) df -h - для вывода информации о жестком диске ( -h используется для вывода размера в гигабайтах);  
  7) ifconfig - для вывода информации о сетевых интерфейсах  

Для вывода текста в консоль использовалась команда echo
