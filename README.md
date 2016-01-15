# FakeQQMail

###QQ邮箱山寨版，主要是参照样式

####使用jade进行模板编辑，less进行CSS设计，gulp进行jade和less的源文件监控，输出目标文件
####效果还是出来了，有些小细节比如tab的边角还有些不完美，不影响效果。
####使用方法：
####命令行 cd 到根目录
####npm install gulp -g 全局安装gulp
####npm install  安装项目内部的组件依赖
####直接打开index.html文件浏览即可
####备注：如果需要自行编辑，可以
####1）命令行运行gulp，监控less更改生成css
####2）命令行运行 jade index.jade -o ./pages/ -P -w，监控jade文件更改生成html 

----
####下面是截屏效果图

![原始图片](https://github.com/wu0792/FakeQQMail/blob/master/screen_shot/real.png?raw=true)

![原始图片](https://github.com/wu0792/FakeQQMail/blob/master/screen_shot/fake.png?raw=true)


####看得出来哪个是正版哪个是盗版吗？：)