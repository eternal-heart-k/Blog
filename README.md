# Blog

## Error

### 1.ERROR Cannot find module 'hexo' from "..."
```
$ npm install hexo --no-optional
if it doesn't work
try
$ npm uninstall hexo-cli -g
$ npm install hexo-cli -g
```
## Problem

### 1.加载图片不出来
#### 正确的引用图片方式是使用下列的标签插件而不是 markdown ：
```
{% asset_img example.jpg This is an example image %}
```

