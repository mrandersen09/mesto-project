> **Название проекта**: _Место_
> Общее:

    - одностраничный лендинг, реализация в html5, css;
    - расширения: editorconfig; normalize.css; nojekyll;
    - шрифты: 'Inter', 'Inter Black', 'Inter Medium' в качестве альтернативы указаны Arial, Helvetica, sans-serif;
    - адаптивная верстка, заданы минимальная (320px) и максимальная (1280px) ширина страницы;
    - методология БЭМ: файловая структура NESTED;
    - кроссбраузерный код для opera, firefox, chrome, mozilla [https://autoprefixer.github.io/ru/];
    - код проверен валидатором [https://validator.w3.org/nu/#textarea]

---

> **Основное**:

- 3 основные зоны: header, content, footer + 1 дополнительная: popup;
- порядок отображения блоков в лендинге:
  - header;
  - places-grid;
  - footer;
  - popup (отображается при помощи display: flex; в модификаторе
    блока opened, базовое значение popup display: none;);
- контент выровнен по сетке (флексбокс);
- блоки places-grid и profile-and-name выровнены при помощи grid,
  остальное позиционирование задано во флексе;
- анимация ссылок задана превдоклассом hover, при наведении курсор меняется на pointer;
  адреса ссылок не прописаны;
- используются картинки в формате .jpg для крупных изображений и .svg для более мелких;

* [Ссылка на макет в Figma](https://www.figma.com/file/2cn9N9jSkmxD84oJik7xL7/JavaScript.-Sprint-4?node-id=0%3A1)
