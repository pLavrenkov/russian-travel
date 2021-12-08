# Проект: Путешествие по России

### Описание проекта
***

Автор: **Павел Лавренков**

Это учебный проект Яндекс.Практику по специальности "Вэб-разработчик", спринт 3. Основная задача работы: формирование адаптивной верски с использованием разных технологий.

Проект посвящен передвижению по России с указанием достопримечательностей.

В проект использованы следующие **технологии** веб-разработки:

* проект выполнен по методологии **БЭМ**;

* размещение блоков через **grid** и **flex** позиционирование;

* использован псевдоблок **::before**;

* применены методы адаптивной верстки, включая **медиазапросы**, функция **calc()** и другие.

Проект использует медиа запросы со следующими точками перелома:

* 1279px;

* 1023px;

* 767px.

Максимальная ширина экрана: **1280px**.

Не удалось воспользоваться свойством CSS **aspect-ratio** в блоке **cover__background** для сохранения масштабирования блока при изменеии , так как валидатор ЯндексюПрактикум его не пропустил, хотя само свойство в Chrome работало. Сохранил отдельную ветку с aspect-ratio.

Проект размещен в **GitHab Pages** [здесь](https://plavrenkov.github.io/russian-travel/).
