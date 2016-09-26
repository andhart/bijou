#宝石

在2kb漂亮的CSS框架（压缩和gzip）

例子：http：/ / / / andhart.github.io宝石

如果你想贡献自己的想法或者看到roadplan，还有Trello：http：／／trello.com / B / 2gklk2lg

浏览器支持：检查并在最新的Firefox，Safari和Chrome，IE9的测试。

###导航:

```html
<div class='navbar fixed'>
   <div class='container'>
      <h4 class='pull-left'>Bijou</h4>
   </div>
</div>
```

or a navbar with navigation:

```html
<div class='navbar fixed'>
   <div class='container'>
      <h4 class='pull-left'>Bijou</h4>
      <ul class='pull-right'>
         <li><a href='#'>链接</a></li>
         <li><a href='#'>链接</a></li>
         <li><a href='#'>链接</a></li>
      </ul>
   </div>
</div>

```

添加一个固定的类导航栏让它固定到屏幕顶端（确保你也加边距：50px如果你的身体使它固定）。

***

###表:

```html
<table class='table'>
   <thead>
      <tr>
         <th>测试</th>
         <th>测试</th>
         <th>测试</th>
         <th>测试</th>
      </tr>
    </thead>
    <tbody>
       <tr>
         <td>测试</td>
         <td>测试</td>
         <td>测试</td>
         <td>测试</td>
       </tr>
    </tbody>
</table>
```

This will style just a plain table. If you want it striped, add the `table-striped` class, or if you want it bordered, the `table-bordered` class.
这只是一个普通的表。如果你想要它tiáo wén，添加 `表tiáo wén` 类，或如果你想要它pí lín，`类表格边框`
***


###按钮

```html
<button class='button danger large'>测试</button>
<button class='button primary large'>测试</button>
<button class='button success large'>测试</button>

<button class='button danger small'>测试</button>
<button class='button primary small'>测试</button>
<button class='button success small'>测试</button>
```

大的按钮 `大`类，虽然小有`小`类。很容易，不是吗？

***

###警报

```html
<div class='alert primary'><p>测试</p></div>
<div class='alert success'><p>测试</p></div>
<div class='alert danger'><p>测试</p></div>
```

***

###网格

宝石具有敏感的12列网格。

例如，以下将创造一一柱和一九柱跨度跨度：
```html
<div class='row'>
   <div class='span one'>一</div><div class='span nine'>九</div>
</div>
```

