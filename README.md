# Задание 2 — сверстать макет

В этом репозитории находятся материалы тестового задания по вёрстке для [14-й Школы разработки интерфейсов](https://academy.yandex.ru/events/frontend/shri_msk-2018-2) (осень 2018, Москва, Санкт-Петербург, Симферополь).

- [макеты](guide)
- [пример анимации открытия попапа](Animation.mp4)

### Попытка #1
Взять bootstrap темплату, похожую на макет и подобрать правильные характеристики шрифтам, блокам, и т.д.
Проблема: очень много сложного/ненужного css и разных тегов и классов, которые в случае изменения могут вообще никогда не совпасть с макетом или противоречить/пересекаться с другими характеристиками  => решила что нужно начать from scratch.

### Попытка #2
Осознала, что на макете указаны точные размеры каждого блока и все нужные характеристики, с этим стало намного удобнее работать и не надо делать “на глаз” ничего. Не использовала bootstrap, создавая каждый новый кусок с осознанием того какие нужны обертки и что писать в стилях css. По дороге почитала больше про margin, position, использование класса внутри класса, горизонтальные списки, таблицы, какие-то базовые вещи про то, сколько вложенных div должно быть.

Узнала, что есть display: flex; flex-wrap: wrap; и подобные штуки для того, чтобы правильно сдвигать объекты в случае изменения размера экрана. Вместе с этим использовала @media для разных размеров экрана и для смены элементов (например, выпадающее меню вместо navbar в случае узкого экрана телефона).
