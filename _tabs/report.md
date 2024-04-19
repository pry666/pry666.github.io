---
icon: fas fa-file
order: 5
---
## 实验技术总结与反思
#### 本次实验选取的是Jekyll中的Chirpy主题，因为看上去比较简洁明了。在Home主页中，有一系列的博客，根据创作时间排序，因为要测试archives的功能，所以特意将其中两个博客创作时间设置为2023年，这样在archives的页面中就有分别了。

#### 在博客页面代码中，在正文的上方设置了类似于title、catagories、tags的信息使得在categories和tags的信息使得categories和tags的页面生效，同时用户也能根据这个分类定位相应的博客而不需要在主页进行寻找了。

#### 在博客正文中采用的是markdown语言，中间也使用了一些类似于内联公式（rightarrow）还有图片插入等的方式写博客

#### 因为在模板中，侧边栏没有report这一栏，所以我也通过修改_config.yml的代码来添加。

#### 遇到的难题和解决方案：

#### 首先是在本地的部署上，因为使用的是jekyll框架，所以本地要安装ruby等进行支持，之后在本地进行修改。在修改过程中，在修改_config.yml的时候发现没有及时生效，后来查阅才得知修改_config.yml时候需要重新运行bundle的命令才能生效。

#### 其次，在图片插入等方面也遇到了一定的问题，有时候是因为md的格式问题，有时候是路径问题，我也根据终端的一些报错来查看相应的问题并解决。

#### 在部署到github上时候也出现了问题，github.io界面不出来，后来发现是因为仓库名字问题，必须要username和github的账户名一致才行，后来修改后解决了这个问题。

#### 总结：
#### 通过本次实验我熟悉了jekyll框架和ruby语言，也了解了_config.yml的原理，在一开始碰到了许多问题，但是等到一次次都解决之后就能够更加熟练的搭建博客了。