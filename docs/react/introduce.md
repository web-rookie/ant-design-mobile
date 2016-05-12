---
order: 0
chinese: Ant Mobile of React
---

Ant Mobile 是 Ant Design 的 Mobile 版本，服务于蚂蚁大中台无线业务。

<div class="pic-plus">
  <img width="150" src="https://t.alipayobjects.com/images/rmsweb/T11aVgXc4eXXXXXXXX.svg">
  <span>+</span>
  <img width="160" src="https://t.alipayobjects.com/images/rmsweb/T16xRhXkxbXXXXXXXX.svg">
</div>

<style>
.pic-plus > * {
  display: inline-block!important;
  vertical-align: middle;
}
.pic-plus span {
  font-size: 30px;
  color: #aaa;
  margin: 0 20px;
}
</style>


## 特性

- 基于 Ant Design 视觉规范。
- 基于 npm + webpack + babel 的工作流，支持 ES next。

## 示例

```jsx
import { Button } from 'antm';
ReactDOM.render(<Button>按钮</Button>, mountNode);
```
引入样式：

```jsx
import 'antm/dist/antm.css'; // or 'antm/dist/antm.less'
```

按需加载可通过此写法 `import Button from 'antm/lib/button'` 或使用插件 [babel-plugin-antd](https://github.com/ant-design/babel-plugin-antd)（此插件支持 js 和 css 同时按需加载）。

## 版本

- 稳定版：[![npm package](http://web.npm.alibaba-inc.com/badge/v/@alipay/antm.svg?style=flat-square)](http://web.npm.alibaba-inc.com/package/@alipay/antm)
- 开发版：[![npm package](http://web.npm.alibaba-inc.com/badge/v/@alipay/antm.svg?style=flat-square)](http://web.npm.alibaba-inc.com/package/@alipay/antm)

## 浏览器支持

ios & android4.0+

## 链接

- [首页](http://beta.antm.alipay.net/#/)
- [React 模块](http://react-component.github.io/)
- [React 代码规范](https://github.com/react-component/react-component.github.io/blob/master/docs/zh-cn/component-code-style.md)
- [组件设计原则](https://github.com/react-component/react-component.github.io/blob/master/docs/zh-cn/component-design.md)

## 谁在使用

- 蚂蚁金服

## 欢迎参与

有任何建议或意见您可以进行发个issue [提问](http://gitlab.alipay-inc.com/react-ui/ant-mobile/issues)。