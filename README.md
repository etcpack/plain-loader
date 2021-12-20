<p align='center'>
    <a href='https://etcpack.github.io/api' target='_blank'>
        <img src='./logo.png'>
    </a>
</p>

# plain-loader
📦 普通文本引入loader，导入的文本应该是一个plain文件

<p>
  <a href="https://hai2007.gitee.io/npm-downloads?interval=7&packages=@etcpack/plain-loader"><img src="https://img.shields.io/npm/dm/@etcpack/plain-loader.svg" alt="downloads"></a>
  <a href="https://www.npmjs.com/package/@etcpack/plain-loader"><img src="https://img.shields.io/npm/v/@etcpack/plain-loader.svg" alt="Version"></a>
  <a href="https://github.com/etcpack/plain-loader/blob/master/LICENSE"><img src="https://img.shields.io/npm/l/@etcpack/plain-loader.svg" alt="License"></a>
  <a href="https://github.com/etcpack/plain-loader" target='_blank'><img alt="GitHub repo stars" src="https://img.shields.io/github/stars/etcpack/plain-loader?style=social"></a>
</p>

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
