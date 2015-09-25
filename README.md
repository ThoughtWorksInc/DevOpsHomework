###作业内容
-----
假设现在有一个项目，需要准备开发环境和产品环境。
对于开发环境来说，需要:

-  必要的环境去运行单元测试，启动应用测试，如Java项目，需要有jdk环境，Ruby项目，需要有对应依赖的
ruby版本；

对于产品环境，需要:
- 准备应用运行所以依赖的软件/库，比如可能需要Apache/Nginx/Tomcat运行在应用前
- 对应用进行自动化部署，比如用`ansible/chef/puppet/shell`等工具将应用部署到产品环境

对于例子项目，可以用自己熟悉的项目，Java/Ruby/Python等都可以。

###验收要求
----
1. 两份Vagratfile,和对应的provision的脚本(最好不要inline)
2. 运行`vagrant provision`命令可以正确的准备好开发环境和部署产品环境，如产品环境部署完后，可以在宿主机通过`http://localhost:8080/`访问该例子应用
3. 给出github repo的link也可以

###有用的链接
----
1. [vagrant](https://vagrantup.com)
2. [vagrant虚拟机下载地址](https://vagrantup.com)
3. [java应用的例子](https://github.com/spring-projects/spring-mvc-showcase)
4. [rails应用的例子](https://github.com/jehughes/rails4-example)
