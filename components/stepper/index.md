---
category: Components
chinese: 步进器
type: 表单
english: Stepper
---

步进器可以以常数为幅度来增减当前数值。

## 何时使用

 - 步进器是一个两段控件，其中一段默认显示减号，另一端默认显示加号。
 - 当想要对数值进行小幅度调整时，可以使用步进器；当用户需要大幅度调整数值的时候，不建议使用步进器

## API

属性如下

| 成员        | 说明           | 类型               | 默认值       |
|-------------|----------------|--------------------|--------------|
| min     | 最小值   | Number | -Infinity        |
| max     | 最大值       | Number      | Infinity           |
| value     | 当前值       | Number      |            |
| step     | 每次改变步数，可以为小数  | Number or String      |  1      |
| defaultValue     | 初始值       | Number      |            |
| onChange     | 变化回调       | Function      |            |
| disabled     | 禁用       | Boolean      |      false      |
| size    | 步进器大小，可取small，large  | String      |      small      |