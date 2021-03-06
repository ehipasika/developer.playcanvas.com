---
title: 设置
template: usermanual-page.tmpl.html
position: 3
---

从设置控制板可以调整项目和应用的基础特征。

## 项目设置

### 命名和描述

你可以在这里修改项目的描述。目前暂时不提供修改项目名称的功能。

#### 项目图片

指定一个方形的 720x720 分辨率图片做为项目的封面。这张图不仅用于个人识别，也用于在发布应用中呈现。如果将应用发布至社交网络，也会引用这张图片。

如果希望您的项目在 PlayCanvas 的社区获得推荐，准备一张图片是必须的。

#### 隐私设置

隐私设置只允许管理员授予了权限的用户进行操作。

<div class="alert alert-info">
只有高级版用户才可以将项目设置为私有
</div>

## 应用设置

#### 分辨率

设定最终发布版本的呈现分辨率。最终的分辨率除了设置的数值之外，还由填充模式和分辨率模式设置而定。

#### 填充模式

填充模式决定了画布如何填充浏览器窗口。

* 保持纵横比 - 画布将会扩展并填满窗口，但是保持设定的纵横比。
* 填满窗口 - 画布将会拉伸并填充整个浏览器窗口。
* 无 - 画布将会完全按照设定的宽度和高度分辨率渲染。

#### 分辨率模式

分辨率模式决定了画布当发生尺寸变化后应该如何应对。

* 锁定 - 分辨率将会一直按照设定的宽度和高度保持。
* 自动 - 分辨率将会和画布的尺寸保持一致，不会超出画布。

#### 开启3D物理学

默认情况下，我们并不在发布项目中包含物理引擎，因为物理引擎占据一定的发布容量。不过如果你使用了任何的物理学组件的话（刚体或碰撞体）系统将会自动启用这个参数。当然你也可以手动开启或关闭。

