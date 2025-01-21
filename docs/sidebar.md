## 导航栏配置

主题V3.0版本对导航栏的配置更加个性化，可选择多项功能的开关和自由配置。

### 导航栏左侧菜单

导航栏左侧可设置多个按钮，参照下方代码在主题设置页的“导航栏左侧菜单配置”框内填写即可。

添加单个按钮的标准代码如下：

```html
<li><a href="链接"><i>图标代码</i>链接文字</a></li>
```

比如，你可以使用以下代码添加网站首页：

```html
<li><a href="https://example.com(这里换成你的首页网址)"><i class="fa fa-home" aria-hidden="true"></i>首页</a></li>
```

当然，依样画葫芦再添加几行，就能添加其他按钮。比如：

```html
<li><a href="https://example.com"><i class="fa fa-home" aria-hidden="true"></i>首页</a></li>
<li><a href="https://example.com/category1.html"><i class="fa fa-folder" aria-hidden="true"></i>分类1</a></li>
<li><a href="https://example.com/links.html"><i class="fa fa-user" aria-hidden="true"></i>友链</a></li>
<li><a href="https://example.com/contact.html"><i class="fa fa-envelope-o" aria-hidden="true"></i>联系</a></li>
```

另外，如果不需要按钮上的图标，直接使用以下格式的代码即可：

```html
<li><a href="链接">链接文字</a></li>
```

> 建议添加 1-5 个按钮即可，不建议添加过多按钮。

图标方面，主题内置了 [Font Awesome](https://fontawesome.com) V4及V5、V6 免费版。如果你尚不了解如何使用图标代码，参见[关于图标](fa.md)。

### 导航栏右侧搜索框与按钮

“是否显示搜索框”选项，默认为“是”，在导航栏右侧展示一个全站搜索框。如不需要，可选择关闭。

“是否显示登录按钮”选项，默认为“是”，在导航栏右侧展示一个“Sign in”（登录）按钮。若检测到用户已登录，则展示“Logout”（登出）、“Admin”（后台）两个按钮。如不需要，可选择关闭。

“是否显示注册按钮”选项，默认为“否”。如选择“是”，则在顶部导航栏展示“Sign up”（注册）按钮。

> 用户已登录状态下，不显示注册按钮；若关闭显示登录按钮，则无论该项选择“是”或“否”，注册按钮都不显示。

> 如想更改各个按钮上的文字（如把“Sign in”换成中文的“登录”），可自行修改主题<code>header.php<code>文件。