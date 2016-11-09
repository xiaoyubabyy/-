#创建（笔记）库的流程
```
- 创建一个文件夹
- 建立一个后缀为.md的文件
- git init - 初始化
- git add .
- git commit -m""
- 在github中建立一个库，复制其中一句代码
- git push
- 根据提示再粘贴一句代码
- git push
- 创建成功
```
### git clone 命令


要想把 github 上的一个项目代码下载到本地有两种方式，一种就是普通下载（ download ）。但是，开发者
基本上会选择另外一种方式，就是 clone 。

```
git clone git@github.com:happypeter/digicity.git
```

clone 的特点就是不仅仅可以得到最新代码，而且可以得到整个改版历史。而普通下载只能得到最新版本。
