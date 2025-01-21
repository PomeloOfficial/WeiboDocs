## 背景图片

“背景图片链接”与“顶部卡片背景图片链接”，分别对应全站背景和顶部资料卡背景图片。可以填入外部链接，也可以直接替换主题目录下<code>images/bg.jpg</code>、<code>images/cardBg.jpg</code>两个文件。

## 资料卡设置

你可以填写自己的昵称、一句话简介、认证信息、微博等级、居住地、生日。也可以在“查看更多指向链接”内，填入侧边资料卡“查看更多”的指向链接。

你还可以设置顶部资料卡两个按钮对应的指向。第一个橙色按钮在鼠标放上时会显示一个二维码；第二个橙色按钮则可点击并跳转。你可以设置按钮文字、二维码图片、点击跳转链接等。二维码图片也可直接替换主题目录下<code>images/qrcode.jpg</code>。

> 如想把第一个按钮也换成点击跳转，或把第二个按钮换成显示二维码，可自行修改主题<code>header.php</code>文件。

### “☰”菜单配置
“☰”菜单展开后会显示一列按钮，参照下方代码在主题设置页的“资料卡“☰”菜单展开按钮配置”框内填写即可。

添加单个按钮的标准代码如下：

```html
<li><a href="链接">链接文字</a></li>
```

比如，你可以使用以下代码添加一个邮箱联系方式：

```html
<li><a href="mailto:example@example.com">邮箱</a></li>
```

当然，依样画葫芦再添加几行，就能添加其他按钮。比如：

```html
<li><a href="mailto:example@example.com">邮箱</a></li>
<li><a href="https://space.bilibili.com/2">Bilibili</a></li>
<li><a href="https://github.com/GitHub">GitHub</a></li>
<li><a href="https://gitee.com/Gitee">Gitee</a></li>
```

另外，如果想在按钮上添加图标，可以使用以下格式的代码：

```html
<li><a href="链接"><i>图标代码</i>链接文字</a></li>
```

比如：

```html
<li><a href="mailto:example@example.com"><i class="fa fa-envelope-o" aria-hidden="true"></i>邮箱</a></li>
```

> 建议添加 1-5 个按钮即可，不建议添加过多按钮。

图标方面，主题内置了 [Font Awesome](https://fontawesome.com) V4 及 V5、V6 免费版。如果你尚不了解如何使用图标代码，参见[关于图标](fa.md)。

> “资料卡“☰”菜单展开按钮配置”设置框，拖动右下角小三角可以调整文本框大小。