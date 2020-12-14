<!-------------------- Heading ---------------------------->
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6  

<!------------------- Text formatting --------------------->

<!-- normal text  -->
Normal Text
<!-- italic text  -->
*italic text*

_also italic text_
<!-- bold text  -->
**bold text**

__also bold text__

<!-- strike through text  -->
~strikethrough text~

~~also strikethrough text~~

<!---------------------- Horizontal Rule  ------------------------>
Some text

---

some other text
___

<!-------------------------- Blockquotes ------------------------->

> This is some blockquote text. This is some blockquote text. This is some blockquote text. This is some blockquote text. This is some blockquote text. This is some blockquote text. This is some blockquote text.

> Some other blockquote. Some other blockquote.

<!-------------------------- Links ------------------------->
[Mail me](mailto:avenshafeez@yahoo.com)

[Mail me](mailto:avenshafeez@yahoo.com "click here to mail me")

<!------------------------------ Lists  ------------------------------>

<!-- unordered list  -->
- List-Item 1
- List-Item 2
  - Nested List-item 2.1
  - Nested List item 2.2
- List-Item 3

Let's create another List

* item-1
* item-2
  * item 2.1
  * item 2.2
* item-3

<!-- ordered list  -->
1. ordered list-item-1
1. ordered list-item-2
  - unordered list-item-2.1
  - unordered list-item-2.2
1. ordered list-item-3

<!------------------------------ Images  ---------------------------->
![x_icon_png_picture](./x_icon.png)

![x_icon_png_picture](./x_icon.png "x icon")


<!----------------------- Github specific styles  ----------------------->

<!-- code blocks  -->

```javascript
  function sum(int a, int b){
    let res = a + b;
    return res;
  }
```

```bash
  npm --version
  npm init
  npm start
```

```bash
  git config --global user.name "Firstname Lastname"
  git config --global user.email "user@example.com"
  git init
  git add .
  git commit -m "commit message"
  git push -U origin main https://github.com/id/repo
```

<!-- table  -->

| Name | E-mail |
| --- | --- |
| Nusrat Imroz | nusrat@outlook.com |
| Abrar Towhid | abrar@gmail.com |

<!-- task list  -->

* [x] done task 1
* [x] done task 2
* [ ] undone task 3
* [x] done task 4

<!-- html element test   -->

<ul>
  <li>item 1</li>
  <li>item 2</li>
  <li>item 3</li>
</ul>


<div style="height: 200px; width: 500px; background: #ffd; margin: 0 auto; color: #f00; font-weight: bold; text-align: center; padding: 10%;">Hello World!</div>


<!-- collapsible  -->

## collapsible markdown?

<details><summary>Click Me!</summary>

#### yes. even hide the code blocks

```python
  def sum(a, b):
    return a+b
```

</details>
