# 前端脚手架搭建指南
> 脚手架是可重用的前端应用开发模型

&emsp;&emsp;作为一名前端开发人员，脚手架是前端架构的一部分，脚手架致力于提供一致的模板框架，自动化的开发构建流程，使得团队能够遵循统一的开发规范，高效地完成产品和项目研发。

脚手架应该具备以下特点：
+ 配置最简化：初始脚手架后，无需配置或者使用极少配置就可以运行脚手架
+ 一致性：脚手架在不同终端、不同时间运行后结果都一致
+ 自动化：相关任务都应该通过自动化命令或脚本完成
+ 关注分离：所有与开发无关的任务都应该自动化，使我们可以关注开发本身

&emsp;&emsp;常见的脚手架工具有很多，很多框架或库譬如[express](http://expressjs.com/zh-cn)、[VueJS](https://vuejs.org.cn/)都提供了快速生成基本项目目录结构的脚手架。[Yeoman](http://yeoman.io/)作为近些年流行的脚手架工具，也形成了良好的生态圈，很多高质量的**generator**更是提供了强大的扩展功能和完善的构建脚本。

&emsp;&emsp;下面将分几部分介绍如何搭建前端脚手架工具
