```
роцесс - обстрак.термин. Под ним понимаетмя набор ресурсов задачи во время выполнения. 
1)Память
2) Дискриптор
3) Контекс выполнения
4) pid 
5) обработчики сигналов
6) один поток, как минимум.



Потоки имеют
1)обш.вир.память
2) каждый свой вирт.процессор
````
```
Stack - Адреса возврата из подпрограмм(Аргументы функций)
mmap - Разделяемая библиотека
неиспользованная память 
heap - Всякие локальные переменные и временные данные 
bss - Неинициализированные и статические переменные 
data - Иницициализированные и статические переменные 
text - исполняемые инструкции (код)
```
Стек - переполнение чего-то там.

Виртуальная файловая система /proc
Pid/maps - карта памяти
Pid/fd - откр.файловые дескрипторы
Pid/enivorm - переменые окружения 
Pid/exe - симлик на использ.файл 
Pid/cwd симлик на деректорию 
Pid/status  состояние процессора. 
