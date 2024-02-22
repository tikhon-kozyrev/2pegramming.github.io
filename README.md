# 2pegramming.github.io
main site

## Tips&Trics

### Add image with caption

```
{%
    include image.html
    url="https://systemdesign.one/consistency-patterns/strong-consistency.webp"
    description="some **description** with explanation of [image](http://google.com)"
    altdescription=""
%}
```

### Publish post

```
# in /questions/_posts/yyyy-mm-dd-post.md

---
published: true | false
---

```

### Images

Put image in to: `public/images/yyyy-mm-dd-post/` folder

Use `/public/images/yyyy-mm-dd-post/imgage.jpg` after


### ZA/UM texts

```
<details>
  <summary>Заумь</summary>
  <pre>

  ### Heading
  1. Foo
  2. Bar
     * Baz
     * Qux

  ### Some Javascript
  ```js
  function logSomething(something) {
    console.log('Something', something);
  }
  ```
  </pre>
</details>
```

