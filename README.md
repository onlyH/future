# future
前端性能优化

### 常用的css-sprites工具

#### [go！png](http://alloyteam.github.io/gopng/ "go！png")  http://alloyteam.github.io/gopng/
##### 所显示的代码是pc端的，如果移动端要除以2。

#### [fis3](http://fis.baidu.com "fis3")  http://fis.baidu.com

####  [grunt](http://gruntjs.com "grunt")  http://gruntjs.com

### 媒体查询功能的使用--响应式  
#### <picture></picture>方法的使用


### 视频播放形式：
1，video标签播放
优点：不需要下载额外的资源（eg：flash需要下载.swf辅助插件），控制简单有较为完整的api。
缺点：每个浏览器的外观都不一样，如果要统一需要自己来写UI实现。


2，flash播放器播放
优点：兼容性好，只要有flash player 播放器插件，都可以进行播放
缺点：1，需要下载额外的swf播放文件才可以播放，浏览器必须有flash player插件（容易被浏览器后置）。2，flash player版本的碎片化，不同的版本对浏览器的支持是不一样的，操作权限也不一样。3，UI定制需要as

3，flash和html5两种方案相结合，组成一个完整的方案，比如：
（1）flowplayer功能简洁，使用方便
 [flowplayer](http://flowplayer.org/player/ "flowplayer")  http://flowplayer.org/player/
 
 （2）video功能强大，使用复杂
 [video](http://video.com "video")  http://video.com
 
 #### 让播放器第一时间加载出来
 目标：缩短从用户进入页面到播放视频第一帧的时间
 1，把初始化的播放器的代码的执行顺序提前。
 2，把播放器播放时所需要的资源提前。
 
 









