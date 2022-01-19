# __Научиться учиться__

_Проект рассказывает и показывает, какие современные и эффективные подходы к обучению Вы можете использовать в своей жизни!_

## __Демо__

__[https://dhatura.github.io/how-to-learn/](https://dhatura.github.io/how-to-learn/)__

<br />

## __Функциональность/Технологии__:

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

 <br />

## __Планы по доработке проекта:__

 * Создать якорные ссылки для логотипов блока resouces;
 * В блоке kaufman иначе реализовать треугольник для более красивой анимации;
 * Добавить вендорные префиксы для реализации кроссбраузерности.

<br />

## __Инструкция по развёртыванию:__

* Запустите index.html из папки с проектом
