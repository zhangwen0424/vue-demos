<!--
 * @Date: 2020-06-10 19:52:41
 * @LastEditors: zhangwen
 * @LastEditTime: 2020-06-10 20:13:06
 * @FilePath: /vue-demos/1.简单的todolist/README.md
--> 
## vue简单的todolist
![项目截图](https://raw.githubusercontent.com/zhangwen0424/vue-demos/master/images/todolist.png)

用到的知识有：
- v-for
- v-bind
- v-on
- v-model
- component
- 父组件子组件通信
    - 1.子组件绑定事件中$emit（父组件事件名称） 
    - 2.父组件监听调用事件v-on:(父组件事件名称)="父组件menthods方法"