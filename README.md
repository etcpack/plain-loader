<p align='center'>
    <a href='https://ectpack.github.io/api' target='_blank'>
        <img src='./logo.png'>
    </a>
</p>

# plain-loader
📦 普通文本引入loader，导入的文本应该是一个plain文件

## Issues
使用的时候遇到任何问题或有好的建议，请点击进入[issue](https://github.com/etcpack/plain-loader/issues)！

## How to use?

```
npm install --save-dev @etcpack/plain-loader
```

然后在```etcpack.config.js```的```loader```配置项中添加，例如：

```js
loader: [{
    test: /\.txt$/,
    handler: ['@etcpack/plain-loader']
}]
```

开源协议
---------------------------------------
[MIT](https://github.com/etcpack/plain-loader/blob/master/LICENSE)

Copyright (c) 2021 [hai2007](https://hai2007.gitee.io/sweethome/) 走一步，再走一步。
