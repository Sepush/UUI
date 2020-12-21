# 介绍

~~English~~ | 简体中文

在近几年的前端技术发展中，诞生出了很多优秀的 UI 库，例如 [Ant Design](https://ant.design/)、[Element UI](https://element.eleme.io/)、[Blueprint](https://blueprintjs.com/) 等等，这些优秀的开源项目提供了大量的 UI 组件和实用功能，给前端网页开发带来了巨量的效率提升。一些组件库还提出了一整套设计规范，包括不限于设计原则、样式风格、色彩选用等，这些规范限制能让组件更加美观一致，在网页项目里使用一整套 UI 库，也能让整个页面更加的协调一致。

这样的 UI 库非常适合用在后台管理页面上，对于管理使用者来说，更重要的是能稳定高效执行一些操作，对于开发者来说，更重要的是提供大量复杂的数据操作和展示的功能，而不是有更独特漂亮的页面样式和风格；但是对于产品的落地页、用户使用界面等这一类页面，每个产品都希望拥有自己特色风格的界面，这种情况下会面临的一个问题就是，这些有着高度设计风格主张的框架所提供的 UI 组件很难被修改它们样式。

对于这样的问题，我们（[新小科技](https://xinxiao.tech/)）决定尝试开发一套便于风格样式自定义的 UI 组件库 —— UUI。

* 基于 React 的组件库，目前不考虑 Vue 版本；
* 强大的组件样式自定义功能 —— 相比于市面上的其他 UI 库，UUI 更多的考虑如何让开发者更方便地定制组件样式；
* UUI 功能和样式实现分离，UUI 内置了一套简约风格的样式，但是你也可以选择自己实现一套样式；
* UUI 不主张特定的某一类设计风格（例如谷歌家的 Material Design、微软家的 Fluent Design 和阿里家的 Ant Design），如果愿意的话，你可以自己实现以上设计风格的样式；
* 有一组开箱即用的组件；
* 基于 TypeScript 的类型安全性；
* 符合 WAI-ARIA 1.2 规范。

目前 **UUI 正处于频繁开发更新中**，接口和用法在将来可能会改变，目前暂时无法保证向后兼容。

我们也非常欢迎您加入到 UUI 的开发中，期待您的第一个 Pull Request。