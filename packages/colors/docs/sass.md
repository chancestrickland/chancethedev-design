# Sass API

| Mark | Description                                                |
| ---- | ---------------------------------------------------------- |
| ✅   | Public functions, mixins, placeholders, and variables      |
| ❌   | Private items - not supported outside package's build      |
| ⚠️   | Deprecated items - may not be available in future releases |

<!-- toc -->

- [@chancethedev/colors](#chancethedevcolors)
  - [✅chancethedev--colors [mixin]](#chancethedev--colors-mixin)

<!-- tocstop -->

## @chancethedev/colors

### ✅chancethedev--colors [mixin]

Define color variables

<details>
<summary>Source code</summary>
```scss
@mixin chancethedev--colors() {
  $chancethedev--black-100: #1f1f1f !default !global;
  $chancethedev--white-0: #ffffff !default !global;
  $chancethedev--green-10: #c9e5b9 !default !global;
  $chancethedev--green-20: #a9d18f !default !global;
  $chancethedev--green-30: #79bd4f !default !global;
  $chancethedev--green-40: #5b8e3b !default !global;
  $chancethedev--green-50: #3d5f28 !default !global;
  $chancethedev--green-60: #1e2f14 !default !global;
  $chancethedev--blue-10: #bbd1da !default !global;
  $chancethedev--blue-20: #8fb4c1 !default !global;
  $chancethedev--blue-30: #558ca3 !default !global;
  $chancethedev--blue-40: #40697a !default !global;
  $chancethedev--blue-50: #2b4652 !default !global;
  $chancethedev--blue-60: #152329 !default !global;
  $chancethedev--red-10: #f1beb0 !default !global;
  $chancethedev--red-20: #e59383 !default !global;
  $chancethedev--red-30: #dc5c3a !default !global;
  $chancethedev--red-40: #a5452c !default !global;
  $chancethedev--red-50: #6e2e1d !default !global;
  $chancethedev--red-60: #37170e !default !global;
  $chancethedev--yellow-10: #f7deac !default !global;
  $chancethedev--yellow-20: #fcca7a !default !global;
  $chancethedev--yellow-30: #eaac2f !default !global;
  $chancethedev--yellow-40: #b08123 !default !global;
  $chancethedev--yellow-50: #755618 !default !global;
  $chancethedev--yellow-60: #3a2b0c !default !global;
  $chancethedev--gray-10: #efefef !default !global;
  $chancethedev--gray-20: #c8c8c8 !default !global;
  $chancethedev--gray-30: #9e9e9e !default !global;
  $chancethedev--gray-40: #757575 !default !global;
  $chancethedev--gray-50: #585858 !default !global;
  $chancethedev--gray-60: #3b3b3b !default !global;
  $black-100: #1f1f1f !default !global;
  $white-0: #ffffff !default !global;
  $green-10: #c9e5b9 !default !global;
  $green-20: #a9d18f !default !global;
  $green-30: #79bd4f !default !global;
  $green-40: #5b8e3b !default !global;
  $green-50: #3d5f28 !default !global;
  $green-60: #1e2f14 !default !global;
  $blue-10: #bbd1da !default !global;
  $blue-20: #8fb4c1 !default !global;
  $blue-30: #558ca3 !default !global;
  $blue-40: #40697a !default !global;
  $blue-50: #2b4652 !default !global;
  $blue-60: #152329 !default !global;
  $red-10: #f1beb0 !default !global;
  $red-20: #e59383 !default !global;
  $red-30: #dc5c3a !default !global;
  $red-40: #a5452c !default !global;
  $red-50: #6e2e1d !default !global;
  $red-60: #37170e !default !global;
  $yellow-10: #f7deac !default !global;
  $yellow-20: #fcca7a !default !global;
  $yellow-30: #eaac2f !default !global;
  $yellow-40: #b08123 !default !global;
  $yellow-50: #755618 !default !global;
  $yellow-60: #3a2b0c !default !global;
  $gray-10: #efefef !default !global;
  $gray-20: #c8c8c8 !default !global;
  $gray-30: #9e9e9e !default !global;
  $gray-40: #757575 !default !global;
  $gray-50: #585858 !default !global;
  $gray-60: #3b3b3b !default !global;
  $chancethedev--colors: (
    'black': (
      100: #1f1f1f,
    ),
    'white': (
      0: #ffffff,
    ),
    'green': (
      10: #c9e5b9,
      20: #a9d18f,
      30: #79bd4f,
      40: #5b8e3b,
      50: #3d5f28,
      60: #1e2f14,
    ),
    'blue': (
      10: #bbd1da,
      20: #8fb4c1,
      30: #558ca3,
      40: #40697a,
      50: #2b4652,
      60: #152329,
    ),
    'red': (
      10: #f1beb0,
      20: #e59383,
      30: #dc5c3a,
      40: #a5452c,
      50: #6e2e1d,
      60: #37170e,
    ),
    'yellow': (
      10: #f7deac,
      20: #fcca7a,
      30: #eaac2f,
      40: #b08123,
      50: #755618,
      60: #3a2b0c,
    ),
    'gray': (
      10: #efefef,
      20: #c8c8c8,
      30: #9e9e9e,
      40: #757575,
      50: #585858,
      60: #3b3b3b,
    ),
  ) !default !global;
}
```
</details>

- **Group**: [@chancethedev/colors](#chancethedevcolors)
