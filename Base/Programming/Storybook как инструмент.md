#programmin #frontend

> **Ключевая идея:**
> _«Storybook полезная библиотека для продуктовой разработки, которая позволяет создавать, тестировать, документировать компоненты. »_

## Что такое Storybook
Storybook это библиотека для **разработки**, **тестирования** и **документирования** UI компонентов. Все из чего можно создать пользовательский интерфейс, нужно хранить в storybook.

Внутри Storybook есть сущность, которая называетя историей, это все возможные состояния для компонента. 

Помимо дефолтных возможностей Storybook имеет ряд полезных библиотек:
- [Controls](https://storybook.js.org/addons/@storybook/addon-controls/) - позволяет менять пропсы компонента прямо из интерфейса Storybook
- [Action](https://storybook.js.org/addons/@storybook/addon-actions/) - позволяет взаимодействовать с интерактивными компонентами
- [Viewport](https://storybook.js.org/addons/@storybook/addon-viewport/) - проверка адаптивность компонента
- [Backgrounds](https://storybook.js.org/addons/@storybook/addon-backgrounds/) - позволяет поменять фон 
- [Docs](https://storybook.js.org/addons/@storybook/addon-docs/) - документация компонента
- [Accessibility](https://storybook.js.org/addons/@storybook/addon-a11y) - тестирование на доступность
- [Links](https://storybook.js.org/addons/@storybook/addon-links) - ссылки на компоненты

## Для чего нужен
- Переиспользовать компоненты
- Тестирование компонентов
- Разработчик не думает о UI, а интергрирует его в проект и накидывает логику на него (если надо)
- Упрощает интеграцию новых разработчиков, ему не надо гадать, как создать тот или иной компоненты, так как они уже готовы
- Для создания дизайн системы внутри компании
- Для создания документации, как использовать компоненты


## Проблемы
- Может возникнуть свалки компонентов, при отсутсвии правил написания историй 
- Как и любые тесты съедает время
- Нужен ревью компонентов, чтобы не переисползовать плохой код

## Лучший пример того как сделан storybook
[wix](https://www.wix-style-react.com/storybook/?path=/story/getting-started--about-wsr)

## Тестирование
- Скриншот тесты
- Доступность
- Тесты взаимодействия

## Заключение
- Все прелести библиотеки раскрываются на дистанции
- Важно не создавать мусорку

## Источники
**Текст:**
[Документация](https://storybook.js.org/docs/react/get-started/introduction)
[Component Driven User Interfaces](https://www.componentdriven.org)

**Видео:**
[Я ❤ Storybook - Семён Левенсон](https://www.youtube.com/watch?v=ZUo9Rv_--F4&t=31s)
