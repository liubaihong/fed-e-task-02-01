### fed-e-task-02-01 作业
1. 简答题
    1. 谈谈你对工程化的初步认识，结合你之前遇到过的问题说出三个以上工程化能够解决问题或者带来的价值  
    答：1、想要使用ES6+新特性，但是兼容性有问题，工程化能将代码重新编译成兼容的代码  
        2、想要使用预处理器增强CSS的编程性，但是运行环境不支持，工程化能自动将其编译成css代码  
        3、可以使用模块化来提交项目的开发效率和可维护性  
        4、部署时自动压缩代码  
    
    2. 你认为脚手架除了为我们创建项目结构，还有什么更深的意义？  
    答：1、还可以增加公共项目配置文件，开发依赖，甚至业务代码，可以统一管理，增加开发效率和多人协作  
        2、在此基础上，可以搭建一个自动化工作流

2. 编程题
    1. 概述脚手架实现的过程，并使用 NodeJS 完成一个自定义的小型脚手架工具  
    答：创建目录并初始化 ==> 安装yeoman-generator ==> 创建generators/app/index.js入口文件 ==> 入口文件中引入yeoman-generator模块 ==> 导出一个继承自yeoman-generator的类 ==> 在导出的类中通过继承自父类的一些生命周期方法实现脚手架具体功能，例如：文件写入，模板复制等 ==> 通过npm link链接到全局  
    脚手架地址：https://github.com/liubaihong/generator-sample.git
	
	2. 尝试使用Gulp完成项目的自动化构建  
	答：仓库地址：https://github.com/liubaihong/my-gulp.git

    3. 尝试使用grunt完成项目的自动化构建  
	答：仓库地址：https://github.com/liubaihong/my-grunt.git

