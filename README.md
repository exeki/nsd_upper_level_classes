# nsd_upper_level_classes

Первоначальная версия реализована Алексеем Шороховым, guthub: https://github.com/Xokyopo

Проект предоставляет собой библиотеку, содержащую подобие классов, из которых состоит 
верхнеуровневый API NSD при работе со скриптовыми сценариями. 
Библиотека собрана при помощи рефлексии и на основании опыта работы с NSD. 
Классы не содержат реализации, большое количество классов превращено в интерфейсы или абстрактные классы. Классы не содержат приватных методов.
Библиотека используется для написания скриптов в IDE (для автодополнения) и не предназначена для запуска в IDE и/или компиляции, 
написанные с ней скрипты возможно запустить только к среде NSD (консоль, ДПС и тд).