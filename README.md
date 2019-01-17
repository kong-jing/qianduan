
## 前端 学习的示例

<a href="http://kong-jing.github.io/qianduan" target="_blank">示例</a>


[下标的css](cssxiabiao.html)

[粒子效果的canvas](paticle.html)

[前端模拟排序动画js](sortanim.html)

### Markdown

```markdown
<html>
    <header>
        <style>
       ul {
    display: flex;
    position: absolute;
    width: 800px;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
}

li {
    position: relative;
    padding: 20px;
    font-size: 24px;
    color: #000;
    line-height: 1;
    transition: 0.2s all linear;
    cursor: pointer;
    list-style-type: none;
}

li::before {
    content: "";
    position: absolute;
    top: 0;
    left: 100%;
    width: 0;
    height: 100%;
    border-bottom: 2px solid #000;
    transition: 0.2s all linear;
}

li:hover::before {
    width: 100%;
    top: 0;
    left: 0;
    transition-delay: 0.1s;
    border-bottom-color: #000;
}

li:hover ~ li::before {
    left: 0;
}

li:active {
    background: #000;
    color: #fff;
}

        </style>
    </header>
    <body>
      
<ul>
        <li>不可思议的CSS</li>
        <li>导航栏</li>
        <li>光标下划线跟随</li>
        <li>PURE CSS</li>
        <li>Coco</li>
      </ul>
    </body>
</html>
```



