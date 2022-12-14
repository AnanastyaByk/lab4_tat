# Тест-кейсы

*Веб-сайт: [Lamoda](https://www.lamoda.by/)*

### 1. Поиск необходимого товара по корректному запросу 

**Предварительные условия:**
- Открыт сайт [Lamoda](https://www.lamoda.by/);

**Шаги теста:**

| Шаг теста | Действие | Ожидаемый результат |
| :----------: | ---------------------------- | ----------------------------- |
| 1 | Ввести в поле поиска запрос "Rita Bravuro ботильоны”. | Открывается страница с вариантами товаров по запросу “Rita Bravuro ботильоны”. |


### 2. Поиск по некорректному запросу 

**Предварительные условия:**
- Открыт сайт [Lamoda](https://www.lamoda.by/);

**Шаги теста:**

| Шаг теста | Действие | Ожидаемый результат |
| :----------: | ---------------------------- | ----------------------------- |
| 1 | Ввести в поле поиска запрос "Rite Bravoru”. | Открывается страница, на которой отображается: “Ничего не нашли по запросу "Rite Bravoru” и предлагают изменить поисковой запрос или посмотреть рекомендации. |


### 3. Добавление товара в Избранное 

**Предварительные условия:**
- Открыта страница товара [Ботильоны Rita Bravuro](https://www.lamoda.by/p/rtlacc573701/shoes-ritabravuro-botilony/);

**Шаги теста:**

| Шаг теста | Действие | Ожидаемый результат |
| :----------: | ---------------------------- | ----------------------------- |
| 1 | Рядом с кнопкой “Добавить в корзину” нажать на иконку в виде сердца. | У иконки исчезает контур и добавляется красная заливка. На странице “Избранное” появляется товар [Ботильоны Rita Bravuro](https://www.lamoda.by/p/rtlacc573701/shoes-ritabravuro-botilony/). |


### 4. Удаление товара из Избранное

**Предварительные условия:**
- Открыта страница [Избранное](https://www.lamoda.by/wishlist/);
- На страницу Избранное добавлен только товар [Ботильоны Rita Bravuro](https://www.lamoda.by/p/rtlacc573701/shoes-ritabravuro-botilony/);

**Шаги теста:**

| Шаг теста | Действие | Ожидаемый результат |
| :----------: | ---------------------------- | ----------------------------- |
| 1 | Навести на блок с товаром. | Сверху справа появляется иконка "Сердце", залитая красным цветом. |
| 2 | Нажать на иконку "Сердце". | Товар [Ботильоны Rita Bravuro](https://www.lamoda.by/p/rtlacc573701/shoes-ritabravuro-botilony/) исчезает со страницы Избранное. Появляется надпись "В избранном нет товаров", кнопка "Перейти в каталог". |


### 5. Выбрать размер товара

**Предварительные условия:**
- Открыта страница с товаром [Ботильоны Rita Bravuro](https://www.lamoda.by/p/rtlacc573701/shoes-ritabravuro-botilony/);

**Шаги теста:**

| Шаг теста | Действие | Ожидаемый результат |
| :----------: | ---------------------------- | ----------------------------- |
| 1 | Нажать на поле с текстом “Выберите размер”. | Раскрылось выпадающее окно с информацией о размерах. Если какого-то размера нет в наличие, он выделяется более светлым цветом. |
| 2 | Выбрать размер 38 RUS. | Закрылось выпадающее окно. Надпись на выпадающем меню изменилось на выбранный размер 38 RUS. |


### 6. Добавление товара в пустую корзину

**Предварительные условия:**
- Открыта страница с товаром [Ботильоны Rita Bravuro](https://www.lamoda.by/p/rtlacc573701/shoes-ritabravuro-botilony/);
- Выбран размер - 38 RUS;
- В корзине нет никаких товаров;

**Шаги теста:**

| Шаг теста | Действие | Ожидаемый результат |
| :----------: | ---------------------------- | ----------------------------- |
| 1 | Нажать на кнопку "Добавить в корзину". | Появляется окно, в котором отображено: Товар добавлен в корзину, изображение товара, краткая информация о нём: Ботильоны Rita Bravuro, Размер: 38 , количество и цена; рекомендованные товары и две кнопки “Продолжить покупки” и “Перейти в корзину”.  Вместо надписи “Корзина” сверху справа появляется количество товаров, которые находятся в корзине. |


### 7. Изменить количество товаров в корзине

**Предварительные условия:**
- Открыта страница [Корзины](https://www.lamoda.by/checkout/cart/);
- В корзину добавлен товар [Ботильоны Rita Bravuro](https://www.lamoda.by/p/rtlacc573701/shoes-ritabravuro-botilony/);

**Шаги теста:**

| Шаг теста | Действие | Ожидаемый результат |
| :----------: | ---------------------------- | ----------------------------- |
| 1 | Навести на блок с товаром. | Появляется иконка “+”. |
| 2 | Нажать на иконку “+”. | Иконка при наведении загорается голубым цветом. Количество товаров увеличилось на 1. Цена увеличилась вдвое. Рядом с количеством товаров справа появилась иконка “-”. |


### 8. Удаление товара из корзины 

**Предварительные условия:**
- Открыта страница [Корзины](https://www.lamoda.by/checkout/cart/);
- В корзину добавлен один товар [Ботильоны Rita Bravuro](https://www.lamoda.by/p/rtlacc573701/shoes-ritabravuro-botilony/);

**Шаги теста:**

| Шаг теста | Действие | Ожидаемый результат |
| :----------: | ---------------------------- | ----------------------------- |
| 1 | Навести на блок с товаром. | Появляется иконка мусорки и надпись “Удалить”. |
| 2 | Нажать на иконку мусорки или надпись “Удалить”. | Блок с товаров исчез. Появилась информация, что в корзине нет товаров и кнопка “Перейти в каталог”. |


### 9. Посмотреть отзывы о товаре

**Предварительные условия:**
- Открыта страница [Ботинки D.Moro](https://www.lamoda.by/p/rtlaca431901/shoes-dmoro-botinki/);

**Шаги теста:**

| Шаг теста | Действие | Ожидаемый результат |
| :----------: | ---------------------------- | ----------------------------- |
| 1 | Нажать на надпись “Отзывы” под изображениями товара. | Снизу появляется информация с рейтингом товара в виде надписи "4.3" и соответствующим количеством закрашенных звезд, фотографиями купленного товара, кнопкой "Написать отзыв", а также под этой информацией появляются сами отзывы. |


### 10. Сортировка товара по цене

**Предварительные условия:**
- Открыта страница [Ботильоны](https://www.lamoda.by/c/15/shoes-women/?sitelink=topmenuW&l=3);

**Шаги теста:**

| Шаг теста | Действие | Ожидаемый результат |
| :----------: | ---------------------------- | ----------------------------- |
| 1 | Нажать на выпадающий список “Цена”. | Появилось поле с полосой прокрутки и полями диапазона для цены: Мин.цена и Макс.цена. |
| 2 | Ввести в поле Макс.цена “100”. | Автоматически настрически настраивается полоса прокрутки в соответствии с введённой информацией. |
| 3 | Нажать на кнопку “Применить” | На странице появились товары, цена которых соответствует выбранному диапазону. |
