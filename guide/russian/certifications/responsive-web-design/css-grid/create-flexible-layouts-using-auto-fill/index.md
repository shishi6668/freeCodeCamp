---
title: Create Flexible Layouts Using auto-fill
localeTitle: Создание гибких макетов с использованием автозаполнения
---
## Создание гибких макетов с использованием автозаполнения

Эта задача будет объясняться предыдущей задачей, добавляя значение **автозаполнения** к функции _повтора_ . Это приведет к тому, что число divs будет расширяться в зависимости от размера окна просмотра, а не ранее указанного значения столбца. В приведенном ниже разделе « **Before** » указано значение «3» **таблицы-сетки-шаблона** .

_Имейте в виду, что следующие фрагменты кода - это только примеры, а не точная запись из учебного плана FreeCodeCamp._

### До

```css
    grid-template-columns: repeat(3, minmax(50px, 2fr)); 
```

### После

```css
    grid-template-columns: repeat(auto-fill, minmax(50px, 2fr)); 
```

* * *

### Ресурсы

Вы можете обратиться к **разделу Синтаксис** следующей страницы, чтобы увидеть значение **автозаполнения** : [Сеть разработчиков Mozilla](https://developer.mozilla.org/en-US/docs/Web/CSS/repeat)