MARKDOWN CHEAT SHEET

Headers --------------------------- 
# Header 1 
## Header 2 
### Header 3

#  Styling --------------------------- 

 *Emphasize* _emphasize_ 
 **Strong** 
 __strong__ 
 ==Marked text.== 
 ~~Mistaken text.~~ 
 > Quoted text. 
 
 H~2~O is a liquid.
  2^10^ is 1024
  
#   Lists --------------------------- 
  - Item 
   * Item 
    + Item 
  
  1. Item 1 
  2. Item 2 
  3. Item 3 
  
  - [ ] Incomplete item 
  - [x] Complete item
  
#   Links --------------------------- 
  
  A [link](http://example.com). 
  
  An image: ![Alt](#) 
  
  
#   Code --------------------------- 
  Some `dung`
  
---
sidebar_position: 1
---

# Tiêu đề H1

Chữ thường **Nội dung chữ đậm**.

## Tiêu đề h2

Chữ thường **Nội dung chữ đậm**.

Chữ thường **Chữ đậm** with **[ Chữ đậm liên kết đường dẫn](https://docusaurus.new)**.

```shell
Shell cd my-website

npx docusaurus start
```

Chữ thường `tô màu chữ nhấn mạnh`.

Chữ thường `docs/link tô đậm.md` and edit some lines: the site **Chữ đậm** and displays your changes.

```js title="Tiêu đề file.js "
Nội dụng quote.nội dung có highlight
  themeConfig: {
    navbar: {
      items: [
        // highlight-start
        {
          type: 'highlight chữ nội dung',
        },
        // highlight-end
      ],
    },
  },
};
```

- `list tô màu` chữ thường `http://localhost:3000/docs/hello`
-  `list tô màu` chữ thường `http://localhost:3000/docs/hello`

:::caution

In development, you can only use one locale at a same time.

:::

```bash
npm run build
```

