# Шаблон Hugo для генерации одно страничного index.html 

Применение: конвертация html to pdf 

## Зависимости

https://wkhtmltopdf.org/downloads.html

## Использование

$ hugo
$ wkhtmltopdf --enable-local-file-access --outline-depth 2 --enable-internal-links ./public/index.html ./all-content.pdf