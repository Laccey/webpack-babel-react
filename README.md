## 热加载 webpack-dev-server（目标文件夹中是看不到编译后的文件的,实时编译后的文件都保存到了内存当中）
- 修改webpack.config.js文件
- - path: path.resolve(__dirname, '/')
- 修改index.html文件
- - <script src="bundle.js"></script>

## 手动刷新（此bundle.js文件可以查看编译后的文件）
- 修改webpack.config.js文件
- - path: path.resolve(__dirname, 'dist')
- 修改index.html文件
- - <script src="dist/bundle.js"></script>

