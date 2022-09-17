---
title: Elements
published: 2022-08-28
image: https://placeimg.com/768/384/nature/grayscale
---

## Contents

- [Contents](#contents)
- [Headings](#headings)
  - [Heading](#heading)
    - [Heading](#heading-1)
      - [Heading](#heading-2)
        - [Heading](#heading-3)
- [Paragraphs](#paragraphs)
- [Lists](#lists)
  - [Definition List (dl)](#definition-list-dl)
  - [Ordered List (ol)](#ordered-list-ol)
  - [Unordered List (ul)](#unordered-list-ul)
  - [Checkbox List (ul)](#checkbox-list-ul)
- [Table](#table)
- [Code](#code)
- [Misc](#misc)
- [YouTube Components](#youtube-components)

---

## Headings

### Heading

#### Heading

##### Heading

###### Heading

[scrollToTop](#contents)

---

## Paragraphs

**_The_** _quick_ <u>brown</u> [fox](https://www.foxnews.com/) `jumps` ~~over~~ the lazy **dog**.

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

> In solitude, where we are least alone.

[scrollToTop](#contents)

---

## Lists

### Definition List (dl)

<dl>
    <dt>Definition List Title</dt>
    <dd>This is a definition list division.</dd>
</dl>

### Ordered List (ol)

1. List Item 1
2. List Item 2
3. List Item 3

### Unordered List (ul)

- List Item 1
- List Item 2
- List Item 3

### Checkbox List (ul)

- [ ] List Item 1 unchecked
- [x] List Item 2 checked
- [x] List Item 3 checked

## Table

| Table Header 1 | Table Header 2 | Table Header 3 |
| -------------- | -------------- | -------------- |
| Division 1     | Division 2     | Division 3     |
| Division 1     | Division 2     | Division 3     |
| Division 1     | Division 2     | Division 3     |

| Table Header 1 | Table Header 2 | Table Header 3 |
| :------------- | :------------: | -------------: |
| Division 1     |   Division 2   |     Division 3 |
| Division 1     |   Division 2   |     Division 3 |
| Division 1     |   Division 2   |     Division 3 |

[scrollToTop](#contents)

## Image

![Alt text](https://via.placeholder.com/768x384.webp?text=Sample "Image title")

[scrollToTop](#top)

## Code

This is an array `[1, 2, 3]{:js}` of numbers 1 through 3.

The name of the function is `getStringLength{:.entity.name.function}`.

```ts title="examples/index.ts"
for (let x in [0]) console.log(x)
```

```js showLineNumbers
// Example JavaScript

const x = 7
function returnSeven() {
  return x
}
```

```ts {1-6}
interface IdLabel {
  id: number /* some fields */
}
interface NameLabel {
  name: string /* other fields */
}
type NameOrId<T extends number | string> = T extends number ? IdLabel : NameLabel
// This comment should not be included

// ---cut---
function createLabel<T extends number | string>(idOrName: T): NameOrId<T> {
  throw 'unimplemented'
}

let a = createLabel('typescript')
```

## Misc

<sup>Lorem</sup> <sub>ipsum</sub> <cite>dolor sit amet</cite>, <acronym title="Consectetur Adipiscing Elit">consectetur adipiscing elit</acronym>, <abbr title="Aliqua">sed do eiusmod tempor incididunt ut labore et dolore magna aliqua</abbr>. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

<kbd>←</kbd> <kbd>→</kbd> <kbd>A</kbd> <kbd>B</kbd>！

[scrollToTop](#contents)
