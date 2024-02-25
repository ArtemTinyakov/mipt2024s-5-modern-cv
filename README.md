# mipt2024s-5-modern-cv

описание некоторых видов баркодов:
https://en.wikipedia.org/wiki/Barcode
https://tritonstore.com.au/barcode-types/
https://www.peaktech.com/blog/learn-about-the-different-types-of-barcodes/

# Участники

| участник              | данные | задача (кратко)                           |
| --------------------- | -------| ----------------------------------------- |
|Белков Алексей| |
|Белков Арсений| | data synthesis (image + markup) |
|Зайченкова Екатерина   |        | zone image dewrapper |
|Корчагин Сергей        |        | coarse zone detection (bbox) |
|Кулакова Анна| |
|Малеванный Всеволод| |
|Плохотнюк Всеволод     | |
|[Полевой Дмитрий](https://github.com/dvpsun/mipt2024s-5-modern-cv.git)|[я-облако](https://disk.yandex.ru/d/eOlAMqBw1xbWeg)        | координация, техэкспертиза                |
|Сабанцев Лев            | |
|[Тиняков Артём](https://github.com/ArtemTinyakov/mipt2024s-5-Tiniakov-A-D)| [photos](https://disk.yandex.ru/d/yKHmNgF8G0FKxg) | in zone instance segmentation |

# Домашние задания

## неделя 03 (21.02-27.02)
1. собрать еще 10 изображений и разметить их (уже должно быть у каждого по 30), картинки и разметку залить в индвидуальный git (папка data)
2. попробовать найти готовые датасеты с бар-кодами (и возможно с готовой разметкой?)
3. для разметки выбрали via, необходимо создать шаблон для разметки изображений (надеюсь сделает Сергей, у него опыт работы с via есть), для каждого изображения необходимо делать отдельный файл разметки
4. на этапе разметки необходимо понимать какой класс бар-кода перед нами, необходимо сформировать базу с описаниями бар-кодов (база будет общая и лежать тут, на гите, скорее всего будет пополняться)
5. каждый выбрал себе задачу, теперь необходимо посмотреть на существующие state-of-the-art решения, потрогать руками, попробовать позапускать, понять от чего можно отталкиваться

## неделя 02 (14.02-20.02)
1. собираем собственный набор данных - фотографируем самые разные штрихкоды в самых разных условиях
2. пробуем разметить 10-20 разных по сложности геометрии примеров из личных запасов
3. формируем мненние об иструментах ручной разметки ([LabelMe](https://github.com/labelmeai/labelme) и [VGG Image Annotator](https://www.robots.ox.ac.uk/~vgg/software/via/) или [LabelStudio](https://github.com/HumanSignal/label-studio))
4. выбираем себе индивидуальную задачу
5. изучаем доступные данные и готовые открытые SOTA решения (в первую очередь по выбранной задаче)
6. создаем на github хранилище (можно приватное) на семестр, с именем mipt2024s-5-lastname-f-s (в конце фамилия и инициалы) + добавляем в участники dvpsun + ссылку фиксируем в таблице участников и скидываем в личку преподавателю

## неделя 01 (07.02-13.02)
1. собираем собственный набор данных - фотографируем самые разные штрихкоды в самых разных условиях
2. думаем, как внутри может быть устроена система распознавания штрихкодов, как будет устроена система обучения такой распознавалки, какую часть вам интересно сделать
3. ищем готовые open source компоненты системы распознавания штрихкодов
4. ищем описания критериев оценки качества компонент системы распознавания штрихкодов 
5. ищем открытые наборы данных, оцениваем их пригодность для нашей разработки
6. находим в телеге по имени пользователя преподавателю и пишем ему приветственное сообщение (что это студент, 5 курс, ФИО, номер группы, id пользователя на github)
