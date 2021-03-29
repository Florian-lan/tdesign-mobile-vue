# SearchField 搜索框

定义：用于用户输入搜索信息，并进行页面内容搜索

## 1. 组件类型

在TDesign中，只提供一种不同类型的搜索框

### 1.1. 基础搜索框

使用场景：常用于全局内容搜索，位于搜索内容上方

::: demo ./demos/index.vue
:::

## 2. 组件样式

### 2.1. 自定义 Icon 颜色

::: demo ./demos/iconColor.vue
:::

## Props

| 属性             | 类型    | 默认值  | 必传 | 说明                                         |
| ---------------- | ------- | ------- | ---- | -------------------------------------------- |
| autofocus        | Boolean | true    | N    | 是否自动聚焦                                 |
| iconColor        | String  | #888888 | N    | 图标颜色                                     |
| clearable        | Boolean | true    | N    | 是否启用清除图标，点击清除图标后会清空输入框 |
| placeholder      | String  | -       | N    | 占位提示文字                                 |
| cancelButtonText | String  | 取消    | N    | 取消按钮文字                                 |

## Events

| 事件名 | 说明                 | 回调参数          |
| ------ | -------------------- | ----------------- |
| change | 输入框内容变化时触发 | val: 当前输入的值 |
| clear  | 点击清除按钮后触发   | -                 |
| cancel | 点击取消按钮时触发   | -                 |