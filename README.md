# Обучающие ноутбуки по Machine Learning

Привет! В этом репозитории ты найдешь материалы для изучения основ по Машинному обучению.

## Содержание

### Как работать с материалами

Практики и лабораторные построены таким образом, что материал перемешан с заданиями и выкладками кода, поэтому не забывайте выполнять по ходу ячейки с кодом (Shift+Enter), чтобы отображать иллюстрации! Задания представлены в виде мест, где нужно вместо комментария `#TODO` написать код или что-то обсудить/разобрать. Не бойтесь писать прямо в ноутбуке! Успехов, у вас все получится!

> FAQ - может ответ на вопрос найдется [здесь](FAQ.md)

### Базовые практики

- [00_Python.ipynb](notebooks/00_Python.ipynb) - ноутбук практики по самым-самым основам языка Python;
- [01_Numpy.ipynb](notebooks/01_Numpy.ipynb) - ноутбук по основным возможностям фреймворка `numpy` (работа с матрицами);
- [02_Matplotlib.ipynb](notebooks/02_Matplotlib.ipynb) - ноутбук по основным возможностям фреймворка `matplotlib` (визуализация данных);
- [03_Pandas.ipynb](notebooks/03_Pandas.ipynb) - ноутбук по основным возможностям фреймворка `pandas` (работа с табличными данными);
- [04_Seaborn.ipynb](notebooks/04_Seaborn.ipynb) - ноутбук по основным возможностям фреймворка `seaborn` (еще один фреймворк визуализации);

### Основные материалы

- [11_Regression.ipynb](notebooks/11_Regression.ipynb) - ноутбук практики по задаче регрессии;
> Познакомьтесь с понятием задачи определения регрессии, основами обучения моделей с помощью градиентного спуска, а также некоторыми особенностями модели линейной регрессии!
- [12L_Regression.ipynb](notebooks/12L_Regression.ipynb) - ноутбук лабораторной по задаче регрессии;
> Попробуйте себя в решении задачи определения цены дома! Первый раз работаете с настоящими данными? Не бойтесь - постараемся вместе разобраться с тем, что и как делать!

- [21_Classification.ipynb](notebooks/21_Classification.ipynb) - ноутбук практики по задаче классификации;
- [22_Classification.ipynb](notebooks/22_Classification.ipynb) - продолжение разбора задачи классификации;
> Другой задачей в обучении с учителем является задача классификации - давайте пробовать!
- [23L_Classification.ipynb](notebooks/23L_Classification.ipynb) - ноутбук лабораторной по задаче классификации;
> Вам нравятся цветочки? Давайте попробуем разобраться, где какой ирис!

- [31_RandomForest.ipynb](notebooks/31_RandomForest.ipynb) - знакомимся с моделью на основе деревьев;
- [32L_RandomForest.ipynb](notebooks/32L_RandomForest.ipynb) - решаем, кто выживет на Титанике;

- [41_GradientBoosting.ipynb](notebooks/41_GradientBoosting.ipynb) - стараемся разобраться с тем, как работает градиентный бустинг;
- [42L_GradientBoosting.ipynb](notebooks/42L_GradientBoosting.ipynb) - еще сильнее исследуем Титаник;

- [51L_NB_Text.ipynb](notebooks/51L_NB_Text.ipynb) - а что делать с текстом в ML;

## Инструменты

Одним из самых простых способов работы с материалами является использувание сервиса [Google Colab](https://colab.research.google.com/), в котором вы выбираете источник GitHub, вводите URL этой страницы или имя KaiL4eK и далее выбираете нужный ноутбук.

## Структура директорий

- [notebooks](notebooks) - директория с ноутбуками в последовательности рекомендованного изучения;
- [datasets](datasets) - директория с данными, которые использованы в ходе изучения;

## Ресурсы

### Python

- Адаптивный тренажер https://stepik.org/course/512 
- Курс по Python https://stepik.org/course/431 
- Курс по основам http://pythontutor.ru/ 
- Книга Head First Python https://yadi.sk/i/kl-028v2t-ZgpA 
- Книга A Byte of Python https://yadi.sk/i/mNLloJCrIpitTw
- Книга Dive into Python3: https://diveintopython3.net/
- Книга Майкла Доусона https://yadi.sk/i/59X2i1r1gA2Wkg 
- Платформы с задачками:
    - https://checkio.org/ 
    - https://www.codewars.com/ 

### ML

- Очень крутая статья https://eldf.ru/machine-learning-base-article 
- Курс от ODS: https://habr.com/ru/company/ods/blog/322626/ | https://mlcourse.ai/
- Некоторые полезные книжки: https://yadi.sk/d/uFG719fi1IM6HA?w=1
- Еще курсы по ML:
    - https://stepik.org/course/4852/syllabus
    - https://stepik.org/course/401/syllabus (Нейросети)
    - https://www.coursera.org/learn/machine-learning  (Andrew Ng)
    - https://www.coursera.org/specializations/deep-learning (Andrew Ng)
    - https://yandexdataschool.ru/ (Яндекс ШАД)

- ODS: https://ods.ai/ 
- arXiv: https://arxiv.org/ 
- TDS: https://towardsdatascience.com/
- Kaggle: https://www.kaggle.com/ 
- Reddit/ML: https://www.reddit.com/r/MachineLearning/ 

### CV

- Великолепный ресурс от автора Adrian Rosebrock: https://www.pyimagesearch.com/
- Книга по OpenCV версии 3 в оригинале: https://yadi.sk/i/BsAV1O0HPY2XjQ

### Полезные для начала соревнования Kaggle

- Задача предсказания выживших на Титанике (классификация): https://www.kaggle.com/c/titanic
- Предсказываем цену дома (регрессия): https://www.kaggle.com/c/house-prices-advanced-regression-techniques
- Определяем цифру, которая нарисована на картинке (классификация): https://www.kaggle.com/c/digit-recognizer
- Определяем ядовитые грибы: https://www.kaggle.com/uciml/mushroom-classification
- Пора уже разобраться, что изображено на картинке - кошка или собака: https://www.kaggle.com/c/dogs-vs-cats

### ML Additional Tools

- Дополнительная визуализация: https://www.scikit-yb.org/en/latest/index.html
- Фреймворк для простой реализации интерактивного web-представления: https://www.streamlit.io
- Платформа для работы с ноутбуками: https://colab.research.google.com/
