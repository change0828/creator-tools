
先简单说明一下，算法是我在闪影中实现的，因为cocos坐标系和闪影坐标系不一样，为了保证完全一致，我就花了点时间在cocos里又实现了一次（同一种代码，同一种味道，实行两遍，心不是一般的累）。。。

使用方法：
首先在层级管理器上建一个空node

![image](https://forum.cocos.com/uploads/default/original/3X/9/f/9f4b42eec1a1b0a0edc06dfc11699d7e6cdd52e6.png)

然后将下好的js文件拖到属性检查器上

![image](https://forum.cocos.com/uploads/default/original/3X/e/7/e766df2135c04517304da5d512a93d986caa4718.png)

最后运行，完事（接下来随便点就行了）。

![image](https://forum.cocos.com/uploads/default/original/3X/4/b/4b04990b3bfcb9227706c997c24b091da7b1c7ac.gif)

简单吧，而且因为没用啥高级的东西，所以不管是creator的哪个版本，都应该能运行。只是，要特别说一下，算法是四方向的，因为我做的地图是没边界的，所以搜索的时候，是达到一定的搜索上限才停止，这个你们自己看吧，代码也没几行，想改的话，也就是改两个判断就行了。
