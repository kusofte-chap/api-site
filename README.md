### dttio 文件编辑使用说明

#### 1.ditto是什么？

 ditto专为使用Github Pages来托管其代码文档的人设计，也可以部署到自己的服务上，ditto中的docs全是markdown文件。

#### 2.简单说怎么维护你的文档  
 所有的文件都是markdown文件格式, 更新、新增的文件放到目录下`docs/`目录下，同时更新`sidebar.md`中文件链接地址。

 例如新增文件`newApi.md`只需在`sidebar.md`中添加链接即可：
  
  ```javascript
  ## 目录

    1. [前言](#README)
    2. [文档第一部分](#docs/a)
    3. [文档第二部分](#docs/b)
    4. [文档第三部分](#docs/c)
    5. [新的API文档](#docs/newApi)

  ```

#### 3.编辑文档  
+ 点击页面`edit`按钮可以直接进入github编辑页面修改文旦
+ 在本地编辑好推送到远程仓库的`gh-pages分支`  
  

#### 4.关于markdown
  需要了解基本的markdown<a href='http://www.markdown.cn/' target='_blank'>语法</a>，内容不多只有十几个语法推荐使用<a href='https://typora.io/' target='_blank'>Typora</a> 编辑器。
