# AutoGo
智慧树网课平台自动刷课插件（自动答题+自动切换下一节视频）可添加到谷歌浏览器作为插件使用

起因：
    学校需要完成在智慧树平台上网课的学习，但是由于某些视频实在不太感兴趣，但还是必须得看啊，播放过程中会弹出题目选择。不点击视频无法继续播放，这就很尴尬了。于是就产生了编写一个脚本辅助我们完成这个枯燥的过程的想法，让我们腾出有限的时间去做自己想做的事情。

目标：
1.弹出题目自动答题（答对）
2.自动切换下一节视频

实现：
1.弹出的多选题/单选题，全自动匹配正确答案（百分百正确，其中多选题采用智能算法计算出所有可能出现的结果）
2.本节视频播放结束自动切换下一个视频直到本课程学习完毕
3.进入视频播放页面自动启动本插件

步骤：
本服务运行依赖谷歌浏览器（下载地址：https://www.google.cn/chrome/）

有两种方式开启本服务

一、熟悉谷歌浏览器F12调试工具的直接复制JS代码到浏览器调试工具console中，这种方式不需要安装本插件。复制顺序依次为：probably.js => automatic_problem_solving.js => automatic_switch_video.js

二、选择本插件安装到谷歌浏览器中，点击浏览器右上角更多展开 => 更多工具 => 扩展程序 => 打开右上角开发者模式 => 加载已解压的扩展程序 => 选择AutoGo文件夹 => 启用完成  

注：进入智慧树平台播放学习视频会自动启动本插件

亮点：穿插弹出的题目百分百答对

帮助到您的话给点个Star鼓励下！！！
