---
# try also 'default' to start simple
theme: seriph
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://source.unsplash.com/collection/94734566/1920x1080
# apply any windi css classes to the current slide
class: 'text-center'
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# some information about the slides, markdown enabled
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
---

# Slidev

はろーわーるど

---

# Page 2

<br>
マークダウンと同じ容量でブロックコードがかけるよ

```ts
console.log('Hello, World!')
```

---

# Page 3

<br>
{}で数字を指定するとブロックコードの行を強調できるよ


```ts {2,3}
function add(
  a: Ref<number> | number,
  b: Ref<number> | number
) {
  return computed(() => unref(a) + unref(b))
}
```

---

# Page 4

```ts {monaco}
const hoge = "{monaco}を記述するとテキストボックスになるよ"

console.log(hoge)
```

---

# Page 5

## 文字を赤くしたい

<style>
  h2{
    color: red;
  }
</style>

---

# Page 6

> Windi CSSも使えるよ `ここだけ青くしたい`

<style>
blockquote {
  code {
    @apply bg-blue-500 hover:bg-blue-700 text-white;
  }
}
</style>

---

# Page 7

<br>

## ルービックキューブのパターン数を知っていますか？

<!--
-->
『ルービックキューブ』の4325京2003兆2744億8985万6000通り
<!--
-->

---
