# Android
Android开发的日常积累   长期更新中...

http://blog.csdn.net/c15522627353/article/details/52452490   解决华为p8青春版等手机导航栏遮挡应用内容的问题

https://git.embedded.rwth-aachen.de/rtandroid/downloads/raspberry-pi/  rtandroid 玩转树莓派

https://androidappsapk.co/apkdownloader/   goole play app下载链接

https://www.youtube.com/watch?v=SI2oFBkc6EA  rtandroid视频教程

https://github.com/android-notes/SwissArmyKnife   界面的调试工具

https://github.com/kaushikgopal/RxJava-Android-Samples  rxjava demo

https://my.oschina.net/oldfeel/blog/349605   Vysor  AirDroid   远程手机

https://github.com/blindmonk/Android/blob/master/README.md 别人总结的android开发大全(真的很全)

http://chapter2.zhuishushenqi.com/chapter/{url}  追书神器接口,网页小说格式转换

archi
bottomsheet sample   从下面弹出来的dialog
cheesesquare      比较好的  tabtool  就是头的那个
DAILY  同上
demo  一个下拉不断动画的漂亮recycleview动画在md里面   配置低 卡
draggable panel 下拉动画视屏
dylan 计步
effectiveandroidui 和draggable panel  一样 的效果
fabloading 京剧
fast_v2 融云的小demo
floating action button 
fragmentation
geeknews  (里面有个干货集中营  挺有意思)
https://github.com/lawloretienne/TinderStack 卡片
gensignature 获取微信签名工具
listview sample (listview gridview recycleview)
livedemo直播
material view pager 一个风格漂亮的viewpager
material - animations 风格漂亮的界面动画跳转
mpandroidchart example 折线图
okgo 
搜图神器  一个搜图片的app 
sealtalk 嗨豹 融合做的微信
searchmenuanim 搜索动画 放大镜变形
shapeimage 边框 圆角 iamgeview
simplenews  新闻
testselection  6.0代码
ultra pull to refresh 刷新动画  线条的那种
微视界 
wcl-permission-demo 权限 不点击授权进不去
掌刀  一个dota的咨询类app


androidstudio  jar包

task makeJar(type: Copy) {
    delete 'build/libs/mysdk.jar'
    from('build/intermediates/bundles/release/')
    into('build/libs/')
    include('classes.jar')
    rename ('classes.jar', 'mysdk.jar')
}

makeJar.dependsOn(build)


http://www.cnblogs.com/lr393993507/p/5543049.html   手机摇一摇
