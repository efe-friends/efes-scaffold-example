# efes-scaffold-example
[![Built with Gulp](http://img.shields.io/badge/built%20with-gulp.js-red.svg)](http://gulpjs.com/)

efes scaffold example

##运行
下载或克隆下来后，先运行 npm install 安装npm插件，再运行gulp开启gulp任务。

## 目录

#### fonts
字体文件目录
#### images
图片资源目录
#### libs
第三方类库
#### scripts
js脚本文件目录
#### styles
css样式文件目录
#### src
开发目录：放置在此目录下的文件(除了jade目录)必须在concatfile.json中配置，才能生成至对应的发布目录中。此目录下的文件，不能直接使用。
##### src/coffee
coffee文件开发目录。需要在concatfile.json中配置合并、发布的路径。如非特殊需要，合并、发布目录为scripts
##### src/es6
es6文件开发目录。需要在concatfile.json中配置合并、发布的路径。如非特殊需要，合并、发布目录为scripts
##### src/js
js文件开发目录。需要在concatfile.json中配置合并、发布的路径。如非特殊需要，合并、发布目录为scripts
##### src/less
less文件开发目录
###### src/less/includes
作为引用的less文件开发目录，如：header.less, footer.less等。
###### src/less/publishs
作为发布，合并的less文件开发目录。需要在concatfile.json中配置合并、发布的路径。如非特殊需要，合并、发布目录为styles
##### src/css
css文件开发目录.需要在concatfile.json中配置合并、发布的路径。如非特殊需要，合并、发布目录为styles
##### src/jade
jade文件开发目录
###### src/jade/includes
作为引用的jade文件开发目录，如：header.jade, footer.jade等
###### src/jade/publishs
需要发布到根目录下的jade文件开发目录

#### .csslintrc
csslint检测规则
#### .eslintrc
eslint检测规则
#### .efesconfig
efes配置文件
#### concatfile.json
合并、发布配置文件
#### gulpfile.js
gulp配置文件
#### package.json
npm配置文件

## gulp任务
1、编译coffee文件<br/>
2、编译es6文件<br/>
3、编译less文件<br/>
4、编译jade文件<br/>
5、按concatfile.json中的配置合并、发布js、css文件<br/>
6、监控src目录下所有文件，自动执行编译、合并、自动刷新


