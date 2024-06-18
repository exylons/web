---
title: Markdown Syntax Preview
description: Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
pubDate: 2024-06-10
updatedDate: 2024-06-10
hero: "~/assets/heros/test.png"
heroAlt: "Stelle and Clara together on Honkai Star Rail"
---

# Table of Contents

# Markdown Syntax

## Paragraphs

Lorem ipsum dolor sit amet, consectetur adipiscing elit 🤣, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Id donec ultrices tincidunt arcu non sodales neque sodales. Adipiscing diam donec adipiscing tristique risus nec feugiat in.

## Line Break

> This is an auto line break

Lorem ipsum dolor sit amet,
consectetur adipiscing elit 🤣,
sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
Id donec ultrices tincidunt arcu non sodales neque sodales.
Adipiscing diam donec adipiscing tristique risus nec feugiat in.

## Emphasis

### Bold

I Love **Astro!**

### Italic

I am a _Web Developer_.

### Bold and Italic

Thou **_SHALL_** not touch.

## Blockquotes

> Blockquotes can also be nested...
>
> > ...by using additional greater-than signs right next to each other...
> >
> > > ...or with spaces between arrows.

## Lists

### Unordered

- Create a list by starting a line with `+`, `-`, or `*`
- Sub-lists are made by indenting 2 spaces:
  - Marker character change forces new list start:
    - Ac tristique libero volutpat at
    - Facilisis in pretium nisl aliquet
    - Nulla volutpat aliquam velit
- Very easy!

### Ordered

1. Lorem ipsum dolor sit amet
2. Consectetur adipiscing elit
3. Integer molestie lorem at massa

Start numbering with offset: (doesn't work sadly)

57. foo
1. bar

## Code

> Syntax highlighting by [`Rehype Pretty Code`](https://rehype-pretty-code.netlify.app/ "Rehype Pretty Code's documentation")

### Inline Code

This is an array `[1, 2, 3]` of numbers 1 through 3.

### Code Block

```
Sample text here...
```

### Code Block with Title

```bash title="Terminal"
pnpm build
```

### Code Block with Title and Highlighting

```jsx title="Counter.tsx" showLineNumbers {4}
import { createSignal } from 'solid-js'

export default function Counter() {
  const [count, setCount] = createSignal(0)

  const add = () => setCount((i) => i + 1)

  return (
    <div class='flex gap-x-4'>
      <button type='button' onClick={add}>
        the count is {count()}
      </button>
    </div>
  )
}
```

## Horizontal Rules

---

## Link

[YouTube](https://youtube.com)

[Google]

[google]: https://google.com

### Adding Titles

[YouTube](https://youtube.com 'Go to YouTube')

## Image

Image compressed by `sharp`

Local image

![Stelle and Clara together on Honkai Star Rail](../../assets/heros/test.png)

Remote image

![March 7th from Honkai Star Rail](https://www.pockettactics.com/wp-content/sites/pockettactics/2024/01/honkai-star-rail-march-7th.jpg)