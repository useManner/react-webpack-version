# react-webpack-version


手动从零搭建 webpack 版本的架子


// 注意的问题
	mini-css-extract-plugin 和 style-loader 有冲突所以要把style-loader去掉

//需要安装的包
// webpack webpack-cil
// html-webpack-plugin  处理html文件
// clean-webpack-plugin 处理上一次打包
// less less-loder  css预处理器  
// style-loader
// css-loader
// postcss-loader autoprefixer 自动添加前缀
// mini-css-extract-plugin 把css文件打包生成单独文件
// css-minimizer-webpack-plugin 这个插件使用 cssnano 优化和压缩 CSS。
// webpack-merge 使用此插件来合并配置
// react react-dom
// @babel/preset-env  	//        -------- 需要用到 bable 来转译
// @babel/preset-react 	//        -------- 需要用到 bable 来转译
// @babel/core 			//        -------- 需要用到 bable 来转译
// @babel/polyfill  	//        -------- 需要用到 bable 来转译
// babel-loader // webpack配置babel  转译jsx文件的
// webpack-dev-server

yarn add react react-dom

yarn add babel-loader @babel/preset-env @babel/preset-react @babel/core @babel/polyfil html-webpack-plugin mini-css-extract-plugin css-minimizer-webpack-plugin less less-loder style-loader css-loader webpack-merge clean-webpack-plugin webpack webpack-cli -D
