---
sidebar_position: 1
---

#  Styling 

 *Emphasize* _emphasize_ 
 **Strong** 
 __strong__ 
 ==Marked text.== 
 ~~Mistaken text.~~ 
 > Đoạn trích dẫn. 
 
  2^10^ is 1024
  
# Lists
  
  - Item list
  - Item list
  - Item list
  
  - [ ] Incomplete item 
  - [x] Complete item
  
# Links 

  Các liên kết Markdown thông thường được hỗ trợ, sử dụng đường dẫn url hoặc đường dẫn tệp tương đối.
 ## Links

Regular Markdown links are supported, using url paths or relative file paths.

```md
Let's see how to [Create a page](/tutorial -basics/create-a-page).
```

```md
Let's see how to [Create a page](tutorial -basics/create-a-page.md).
```
**Result:** Let's see how to [Create a page](tutorial-basics/create-a-page.md).

## Images

Regular Markdown images are supported.

Add an image at `static/img/docusaurus.png` and display it in Markdown:

```md
![Docusaurus logo Alt](/img/docusaurus.png)
```

![Docusaurus logo Alt](/img/docusaurus.png)

```md
A sized image: ![Alt](img.jpg =60x50)
```
 

# Tiêu đề H1

Chữ thường **Nội dung chữ đậm**.

## Tiêu đề h2

Chữ thường **Nội dung chữ đậm**.

Chữ thường **Chữ đậm** with **[ Chữ đậm liên kết đường dẫn](https://docusaurus.new)**.

```shell
cd my-website shell

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
 //bash
npm run build

```

 ```js
  //js
  var foo = 'bar'; 
  ```
  
  ## Code Blocks

Markdown code blocks are supported with Syntax highlighting.

    ```jsx title="src/components/HelloDocusaurus.js"
    function HelloDocusaurus() {
        return (
            <h1>Hello, Docusaurus!</h1>
        )
    }
    ```

```jsx title="src/components/HelloDocusaurus.js"
function HelloDocusaurus() {
  return <h1>Hello, Docusaurus!</h1>;
}
```

## Admonitions

Docusaurus has a special syntax to create admonitions and callouts:

    :::tip My tip

    Use this awesome feature option

    :::

    :::danger Take care

    This action is dangerous

    :::

:::tip My tip

Use this awesome feature option

:::

:::danger Take care

This action is dangerous

:::

## MDX and React Components

[MDX](https://mdxjs.com/) can make your documentation more **interactive** and allows using any **React components inside Markdown**:

```jsx
export const Highlight = ({children, color}) => (
  <span
    style={{
      backgroundColor: color,
      borderRadius: '20px',
      color: '#fff',
      padding: '10px',
      cursor: 'pointer',
    }}
    onClick={() => {
      alert(`You clicked the color ${color} with label ${children}`)
    }}>
    {children}
  </span>
);

This is <Highlight color="#25c2a0">Docusaurus green</Highlight> !

This is <Highlight color="#1877F2">Facebook blue</Highlight> !
```

export const Highlight = ({children, color}) => (
  <span
    style={{
      backgroundColor: color,
      borderRadius: '20px',
      color: '#fff',
      padding: '10px',
      cursor: 'pointer',
    }}
    onClick={() => {
      alert(`You clicked the color ${color} with label ${children}`);
    }}>
    {children}
  </span>
);

This is <Highlight color="#25c2a0">Docusaurus green</Highlight> !

This is <Highlight color="#1877F2">Facebook blue</Highlight> !
  