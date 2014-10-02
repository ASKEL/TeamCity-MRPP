TeamCity-MRPP
=============

A set of Meta-runners for TeamCity

# MRPP_PHP_PhpDocumentor

Пакет для генерации и публикации в проекте документации - [phpDocumentor](http://www.phpdoc.org/)

По умолчанию, настроено на сборку данных из папки "src"

Необходимо настроить вывод артефакта сборки phpDoc

* Переходим Administration->Root project
* Жмем "Build Report Tabs"
* В диалоге вводим: 
	* Наименование "phpDoc"
	* Параметр "phpdoc.zip!/index.html"