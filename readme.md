## 前言
最近公司项目前端部分稍稍得空，且vue2.x轻量，简洁的特点，是我个人比较喜欢的类型，所以借此机会学习一下vue。
为方便自己和大家对vue的学习，在‘vue前期准备知识点’文件中，特地对vue开发需要前期准备的基础知识及注意点，一条条进行了总结，并且对难点写了demo。  

**vue的基础知识，在 “vue前期准备知识点” 目录中。**  
**项目实战(去哪网)，在 “travel” 目录下，项目有详细注释。**


### 技术栈
vue@2.4 + webpack + node + vue-router + vue-cli + stylus + iconfont + fastclick + vue-awesome-swiper ++ axios + better-scroll + vuex

### 项目运行(进入到travel项目运行)
**安装依赖**  
npm install  
**启动项目**   
npm run dev  
**打开项目**  
localhost:8080


### 项目搭建的过程
使用官方提供的 v-cli 来搭建项目
```
全局安装 vue-cli
$ npm install --global vue-cli  

创建一个基于 webpack 模板的新项目
$ vue init webpack travel  

安装依赖，走你
$ cd travel
$ npm run dev  //启动项目
```
端口: 8080

### 项目上传
```
1. 更新远程代码 ：git pull 
2. git add .
3. git commit -m "注释"
4. 提交本地代码 ：git push 
5. 此项目提交代码的主要步骤  
git checkout -b city-router    //创建并切换到city-router分支  
git add .   //添加city-router分支所有内容  
git commit -m  'city路由配置'  //注释  
git push --set-upstream origin city-router   //提交city-router分支内容  
git chekout master  //切换到主分支  
git merge city-router   // 合并刚才改的分支  
git push  // 再提交主分支  

git关于分支的其他操作可以参考：https://blog.csdn.net/top_code/article/details/51931916  
```
### 项目效果图
![travel效果图](./travel.gif)  

项目功能简单，但涵盖了vue大部分的知识点, 适合入门学习

### 交流
 qq：1537384546，欢迎一起进步加油。如果帮助到你了，还请star一下哦~，祝你越来越优秀！

 