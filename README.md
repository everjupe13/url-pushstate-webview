# Начало работы

Перед началом работы сборки необходимо установить зависимости

    yarn


# Структура

Найстройки webpack'a находятся в директории **build/**


# Команды сборки

Режим разработки **development**

    yarn run dev

***

Билд для **production**

    yarn run build


#### IMPORTANT ⚠️

## HTML

Для картинок устанавливать относительные пути **scr="./assets/img/.."**

## SCSS

Для всех путей в scss свойствах использовать относительные пути именно для самого файла, где оно прописано

## JS

В **build/webpack.base.conf.js** свойство **optimization.minimize** отвечает за минификацию
