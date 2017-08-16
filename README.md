![项目截图](https://github.com/lvyidan/musicplayer-by-react/raw/master/photo/show.png)



# musicplayer-by-react
这是一个基于react的音乐播放器，可以控制音乐的播放进度和音量，也可以打开音乐列表切割
简单，清新

这个小项目一个用到了三个组件，分别是header.js/progress.js/musicList.js
它们的作用是分别用于显示头部logo、控制播放进度以及获取音乐列表

每个js有对应的css，用于修饰样式

各个组件之间的通信就是利用react的props属性，然后改变每个组件的states，触发渲染组件ui

音乐播放的功能是通过jQuery的插件jplayer实现的，它可以实时地为组件提供音乐播放的进度、音量、播放/停止等状态


