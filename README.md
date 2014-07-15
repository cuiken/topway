Top way

## 规范
* ```style.css```，```style-metronic.css```，```style-non-responsive.css``` ，```plugins目录``` 为项目全局基础架构，尽量避免修改。

* ```custom.css``` 存放项目公共样式。

* *css* 目录下 *page* 目录存放页面级样式文件。文件名称需和 ```html``` 文件名称保持一致。

* 每个 ```html``` 页面理论上包含一个 *根类名* 或 *根ID* ,每个页面级样式理论上以 *根类名*开始。如：

***

有login.html 如需要定义样式 ，可 修改``` <body class="login"> ``` ，page 目录下新建一个 *login.css* ， *login.css* 里选择器都以 ``` .login ``` 开头进行路径的选择

***

***template.html*** 为模板文件，复制套用，方便新页面创建。