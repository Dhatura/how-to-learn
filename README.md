# __Научиться учиться__

_Проект создан при прохождении курса "Профессия Веб-разработчик" на [Яндекс Практикум](https://praktikum.yandex.ru "Начать учиться")_


Данный одностраничный сайт вмещает в себя следующие функциональность и технологии:

 * Реализована возможность отклика ссылки при наведении на нее указателя мыши, применена технология __псевдоклассов__:
```css
  .feynman__link:hover {
  opacity: .5;
  transition: opacity .3s ease-in-out;
}
```
 * Фоновые иллюстрации анимированы через __keyframes__:
```css
@keyframes rotation {
  from {
    transform: rotate(0deg);
  }
  to {
    transform: rotate(360deg);
  }
}
```
 * Использование тега __iframe__ позволило просматривать медиафайлы на странице проекта:
```html
<iframe src="https://www.youtube.com/embed/5MgBikgcWnY" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen class="video__iframe"></iframe>
```
 * Для удобного расположения стилей создана файловая структура __Nested БЭМ__;
 * При создании сетки использовалась __Flex__ технология.

Планы по доработке проекта:

 * Создать якорные ссылки для логотипов блока resouces;
 * В блоке kaufman иначе реализовать треугольник для более красивой анимации;
 * Добавить вендорные префиксы для реализации кроссбраузерности.

