# Проект "Определение уровня английского для фильмов"

## Описание проекта:

Необходимо определить, какой уровень английского языка представлен в фильме. Уровень английского языка определяется в соответствии с уровнем Oxford CEFR. Определение уровня осуществляется на основе субтитров к фильму. 

Предоставленный датасет содержит 241 фильм с субтитрами и их уровням английского языка.Из соображений безопасности первоначальный датасет и субтитры не были загружены на GitHub.

Поскольку датасет относительно небольшой, было принято решение о его расширении. В конечном счете, объем выборки составил около 500 фильмов. Однако, стоит учесть, что порой оценки экспертов касательно уровня английского языка отдельного фильма могут не совпадать. Тем не менее, взяв во внимание, что на большей выборке модель может нивелировать погрешности, расширенную выборку решено было оставить.

## План работы:

1. Предобработка данных
2. Выбор метрики
3. Создание модели
4. Анализ результатов
5. Сохранение модели

## Решенные задачи:

1. Создана модель, которая на основе субтитров к фильму определяет уровень английского, необходимого на для его просмотра. Метрики качества моделей были f1-micro и f1-macro, которых удалось достичь 0.7857 и 0.7684 соответственно;
2. Реализовано веб-приложение, с помощью которого пользователь может загрузить субтитры и получить в ответ уровень английского языка, необходимого для просмотра запрашиваемого фильма.

## Изображения веб-приложения:

<img width="400" alt="Снимок экрана 2023-05-19 в 14 07 30" src="https://github.com/Midle68/movies_english_level/assets/88423574/398043a0-653a-4221-81ee-0fe190705132"><img width="400" alt="Снимок экрана 2023-05-19 в 14 08 37" src="https://github.com/Midle68/movies_english_level/assets/88423574/f359a8cb-315c-4aca-b77e-e66ea6b750cf">

## Используемые библиотеки:

`NLTK`, `Numpy`, `pandas`, `PyPDF2`, `pysrt`, `re`, `sklearn`
