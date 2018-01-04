## 处理文本溢出
#### 单行省略号
```css
.singel-line-ellipsis {
    overflow: hidden;
    text-overflow:ellipsis;
    white-space: nowrap;
}
```
#### 多行文本溢出
```css
.multi-line-ellipsis {
    display: -webkit-box;
    -webkit-box-orient: vertical;
    -webkit-line-clamp: 3;
    overflow: hidden;
}
```

## css添加效果
#### 高亮a标签
```css
.highlight-pointer {
    -webkit-tap-highlight-color: rgba(0,0,0,.08);
}
```
