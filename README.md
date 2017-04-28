fis3-parser-dfy-node-sass
============================
> 将node-sass的版本从“3.13.0”更新为“^4.5.2”，以确保它在Node最新版本中运行良好

## 安装与使用 

全局安装

```bash
npm install fis3-parser-dfy-node-sass -g
```

## FIS3

```js
fis.match('*.scss', {
  rExt: '.css',
  parser: fis.plugin('dfy-node-sass', {
    // options...
  })
})
```


