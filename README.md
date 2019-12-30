# Библиотека серверны ф-ций 
## Установка
`npm i fmihel-server-lib -D`
## Набор ф-ций 
|name|result|notes|
|-----|-----|-----|
|routerPaths(...)|array| список маршрутов |
|defArg(name)|boolean|Возвращает признак установлен или нет аргумент в командной сроке. К примеру для `npm webpack --prod`, `defArg('prod')` или `defArg('--prod')` -> **true**|
