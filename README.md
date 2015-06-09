Mutemplate
=====

Mu通用模板，个人前端自动化模板，包含合并，压缩，发布等。

**作者** ： 小牧COOL

**QQ号** ： 895355044

**QQ群** ： 206683621

##涉及技术##

- Nodejs
- Sass
- grunt
- grunt-contrib-clean
- grunt-contrib-concat
- grunt-contrib-copy
- grunt-contrib-imagemin
- grunt-contrib-sass
- grunt-contrib-uglify
- grunt-contrib-watch
- grunt-css
- grunt-replace

##使用方法##

1. 监控sass文件修改,运行

        grunt w

2. 发布release版本,运行

      grunt

3. 部署到指定svn或git,修改 `Gruntfile.js` 里的路径后,运行

      grunt svn


##注意事项##

- `grunt-contrib-imagemin` 插件安装失败解决方法:

    - 更新至最新版[NPM 2.x.x](https://github.com/npm/npm)

    - 在其之前添加依赖模块 `npm install jpegtran-bin --save-dev`

      然后再运行 `npm install grunt-contrib-imagemin --save-dev`

##今日任务##

- [X] 完善package.json
- [X] 更改Gruntfile.js引用
- [X] 图片压缩插件
- [X] copy任务增加
- [X] 配置任务
- [X] 注意事项