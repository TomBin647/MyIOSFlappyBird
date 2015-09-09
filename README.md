# MyIOSFlappyBird
这个是基于sprityKit的游戏 


#cocos2d  Xcode 安装
在官网下载 https://github.com/cocos2d/cocos2d-objc Mac版本的包并解压文件

cd 到该目录下
执行脚本 ./install.sh

Cocos2D Template Installer (Cocos2D-v3.0.0)


>>> Installing project templates
...copying cocos2d files ✔
...copying cocos2d-ui files ✔
...downloading Chipmunk files, please wait... ✔
...copying Chipmunk files ✔
...copying ObjectAL files ✔
...copying CCBReader files ✔
...copying Xcode template files ✔

>>> Installing file templates
...copying CCNode file templates ✔

                                     

Templates installed successfully.
Have fun!

出现上面这个就说明你安装成功了，然后就可以开始你的项目了，Xcode → New → New Project → cocos2d v3.x，赶快试试吧！



#cocos2d-x Xcode 安装 及使用链接 
在官网下载 http://www.cocos.com/download/# cocos2d-3.8（目前是）的包   并解压

打开终端  cd到解压好的包文件目录中 

./setup.py
source ~/.bash_profile # may be ~/.bash_login or ~/.profile, depends on your environemnt
cocos new MyGame -p com.MyCompany.MyGame -l cpp -d ~/MyCompany

执行上面的代码

    MyGame: 你的项目的名字
    -p com.MyCompany.MyGame: android 的包名
    -l cpp: 项目所使用的编程语言, 有效值是 cpp 和 lua
    -d ~/MyCompany: 存放你项目的文件夹



http://www.cocos.com/doc/article/index?type=wiki&url=/doc/cocos-docs-master/manual/framework/native/wiki/how-to-start-a-new-cocos2d-x-game/zh.md
cocos2d-x 安装说明

