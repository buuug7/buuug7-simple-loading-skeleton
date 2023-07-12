# simple loading skeleton

简单的加载骨架

## 安装

推荐从[dcloud 插件市场](https://ext.dcloud.net.cn/plugin?id=611) 安装.

## 使用

- 该插件遵循 easycom 规范, 不用显式导入就可以使用 `<buuug7-simple-loading-skeleton />`

```html
<!-- 单行 -->
<view style="width: 100%" v-if="loading">
  <buuug7-simple-loading-skeleton />
</view>

<!-- 多行 -->
<view style="width: 100%" v-if="loading">
  <buuug7-simple-loading-skeleton />
  <buuug7-simple-loading-skeleton />
  <buuug7-simple-loading-skeleton />
</view>
```

## 属性
