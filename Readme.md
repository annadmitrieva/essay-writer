#Генератор сочинений
Перед вами крик отчаяния, вызванный подготовкой к написанию сочинения на ЕГЭ. Примеры работы программы в папке samples.
##Установка
1. git clone https://github.com/Omrigan/essay-writer (или скачать zip-архив с кодом)
2. pip3 install -r requirements.txt
3. python3 essay.py --help

##Использование
Программа принимает в качестве аргумента текстовый файл на русском языке, в котором содержится исходный текст, а последняя строка - фамилия и инициалы автора
Также можно повысить "эмоциональность" текста, передав дополнительный аргумент -e, который принимает число от 0 до 1, обозначающее будущую эмоциональность вашего сочинения

## Используемые разделы знаний
1. Теория формальных языков (спасибо В. В. Мерзлякову)
2. Методика написания сочинений (спасибо Л. В. Никитенко)
3. Аргументы к сочинениям (спасибо русским и зарубежным писателям)
4. Python3 и библиотеки pymorph2 и plumbum.

##Лицензия
Каждый, кто успешно сдаст сочинение, сгенерированное данной программой, обязуется купить автору кружку пива.
Свободно для любого использования (включая копированние, изменение, использование в коммерческих целях)