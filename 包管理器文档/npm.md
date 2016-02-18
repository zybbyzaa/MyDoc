##  Npm包管理器使用参考

1.  安装

        sudo npm install npm -g(需要nodejs环境)
2.  初始化

        npm init => 生成package.json文件
3.  安装模块

        npm install | i 模块名
        -g：全局安装
4.  package.json文件

        {
            "name": “项目名”,
            "version": “版本号”,
            "description": "项目描述",
            “scripts”: {
                "脚本名": "运行命令"
            },
            "author": "作者信息“,
            "license": "许可证",
            "homepage": "项目主页",
            "dependencies": {       //项目依赖模块
                ”模块名“: "模块版本"
            },
            "devDependencies": {  //开发过程中的依赖模块
                ”模块名“: "模块版本"
            },
            "main": "主文件",
            "repository": {
                "type": "git",
                "url": "git仓库路径"
            },
           "bugs": {
                "url": "git仓库issues页"
            }
        }