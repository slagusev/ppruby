# Пакет ppRuby

<img src="https://raw.github.com/shikhalev/ppruby/master/img/logo.png" align="right">

Пакет `ppRuby` предоставляет доступ к Ruby API для языка Free Pascal.
Использовать его можно для двух основных задач:
* Написание библиотек расширения для Ruby;
* Встраивание Ruby в программы на Free Pascal / Lazarus в качестве скриптового
  языка.

В первом случае понадобится только `ruby.pas` скомпилированный в статическом
режиме (см. ниже). Во втором будет лучше (хотя и необязательно) использовать
прочие модули пакета, которые предоставляют разнообразные утилиты для удобной
работы, а также механизм конвертации pascal-объектов в Ruby, автоматически
транслирующий published-свойства.

## Введение

### Режимы условной компиляции

#### Статическая компиляция

#### Динамическая компиляция

## Модуль `Ruby`

## `RbTools` и `RbObjects`