Пример кода на С++ CLR для чтения архивных значений из базы Honeywell Experion R300 и сохранения их в MS SQL.

Оригинальное API предполагает использование VB Script или С++, в которых нет "синтаксического сахара" :).

Для сборки нужна .NET сборка библиотеки Getopt - https://www.nuget.org/packages/Gnu.Getopt/

Список тэгов читается из текстового файла. Читаются часовые архивы параметра PV.

В Visul Studio нужно настроить свойства проекта в соответствии с главой "Setting up Microsoft Visual Studio for Network API applications" руководства Application Development Guide EP-DSXX16.
