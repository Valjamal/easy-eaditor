# easy-eaditor
Здравствуйте, мой проект нзыается Easy Eitor.
Это приложение было создано блягодаря множеству встроенных библиотек(os, QApplication, QWidget, QFileDialog, QLabel, QPushButton, QListWidget, QHBoxLayout, QVBoxLayout, PyQt5.QtCore, QPixmap)

from PIL import Image
from PIL.ImageQt import ImageQt
from PIL import ImageFilter
from PIL.ImageFilter import (
    BLUR, CONTOUR, DETAIL, EDGE_ENHANCE, EDGE_ENHANCE_MORE,
    EMBOSS, FIND_EDGES, SMOOTH, SMOOTH_MORE, SHARPEN,
    GaussianBlur, UnsharpMask
)

Это библиотеки из PIL

Язык программирования: Python
Мой проект имеет более 100 строк

Когда приложение запускается, пояляется окно, в котором имеются кнопки:
Папка
Лево
Право
Зеркало
Резкость
Ч/б (чёрно-белый)
Нажимая на Папку, Вы должны выбрать любую папку с фотографиями, которые вы хотите отредактировать.
Далее Вы редактируете её, как хотите по кнопкам.
Полученное изображение сохранится в папку Modified.
Спасибо за пользование!
