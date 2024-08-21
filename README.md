# Веб-приложение для страницы продукта

## Обзор

Этот проект включает создание веб-страницы на основе предоставленного шаблона Bootstrap и инструкций. В результате получится простое веб-приложение на Flask, которое будет отображать контент, основанный на Bootstrap.

### Задания

1. **Настройка кнопки**: Измените кнопку «Купить» на карточке товара, чтобы она была полностью залита зеленым цветом, используя документацию по кнопкам Bootstrap.

2. **Добавление формы**: Рядом с карточкой товара добавьте форму с полями «Имя» и «Email», а также кнопку «Отправить», используя документацию по формам Bootstrap.

3. **Раздел FAQ**: Под карточкой товара и формой добавьте раздел FAQ, занимающий всю ширину страницы, с тремя кнопками:
   - Как купить?
   - Как доставить?
   - Какая гарантия?

   Каждая кнопка должна открывать сворачивающийся блок с текстом-заполнителем, используя компонент collapse Bootstrap.

4. **Добавление таблицы (Дополнительно)**: Под разделом FAQ добавьте таблицу на всю ширину с колонками: номер, название товара, цена, количество, итоговая сумма и статус заказа. Используйте документацию по таблицам и alert-ам Bootstrap для стилизации:
   - Новый — Синий
   - Обработка — Желтый
   - Обработан — Зеленый
   - Отмена — Красный

## Запуск приложения

### Требования

- Python 3.7 или выше
- Poetry (для управления зависимостями)

### Настройка

1. **Клонируйте репозиторий**

```sh
git clone git@github.com:RomanPecheritsa/BootstrapProto.git
cd BootstrapProto
```

2. **Установите зависимости**

   Убедитесь, что Poetry установлен. Если нет, установите его, следуя инструкциям на [сайте Poetry](https://python-poetry.org/docs/#installation)


   Установите зависимости проекта:

```sh
poetry install
```

3. **Запустите приложение**

   Активируйте виртуальное окружение, созданное Poetry, и запустите приложение Flask:


```sh
poetry shell
poetry run python app.py
```

Приложение будет доступно по адресу http://127.0.0.1:8000/

## Дополнительные заметки

* Убедитесь, что файл index.html находится в директории templates вашего приложения Flask.
* Проверьте, что все внешние CSS и JavaScript файлы, необходимые для Bootstrap, правильно подключены в вашем index.html.
