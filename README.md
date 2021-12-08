# Pole-foundation

Дизайн система тестируем молекулы и атомы

## Установка

Прописать в консоли

```bash
npm i --save-dev pole-foundation
```

## Использование

```scss
@import '~pole-foundation/scss';

/*
** Молекулы
*/
.text {
  &-largetitle {
    font-weight: variables.$font-b;
    font-size: variables.$font-s1;
    line-height: variables.$font-lh1;
  }
}
/*
** Атомы
*/
//font weight
$font-b: 700;
//font size
$font-s1: 36px;
//font line-height
$font-lh1: 44px;

```

## Классы(молекулы) собираются из атомов(variables)
Пример
```html
<h1 class="text-largetitle>
  Hello
</h1>
```

## Использование variables
Пример
```scss
@use '~pole-foundation/scss/variables/code' as variables;

.test {
  color: $сolor-default-text-primary;

  &:hover {
    color: $сolor-default-text-black_hover;
  }
}
```