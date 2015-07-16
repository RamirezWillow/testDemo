### 开发日志

* 20150629 tr 设置了border无效
* 解决方案：table设置 border-collapse 为collapse, border-collapse属性设置表格的边框是否被合并为一个单一的边框，还是象在标准的 HTML 中那样分开显示。

* 20150712 给canvas标签添加控制宽高的样式后，绘制出来的宽高会异常；
* 解决方案： 不用样式控制宽高，使用属性控制之。

* 20150714 canvas context.translate 改动后会将设置保存在内存中（下次获取 该元素的context位置还是translate后的）
* 解决方案： 使用完后将位置变回去， es： context(100, 100); afater used: context(-100, -100);


### 设计本项目代码的笔试题：

* 2014面试题大全（141101 更新）：
  
  [2014年最新前端开发面试题](http://clisvoi.blog.163.com/blog/static/2014980502014327104119515/)
  [腾讯面试](http://www.w3cfuns.com/article-5598237-1-1.html)
  [跳槽必看](http://developer.51cto.com/art/201202/314618.htm)
  [常见问题](http://www.csdn.net/article/2012-10-18/2810902-Front-end-Developer-Interview-Questions)

* 150302(更新)
  [简历模板](https://github.com/hacke2/ResumeSample)


* 我最近收藏的题库(150629更新)：
  [魅族前端面试题](http://weibo.com/p/1001603857375168721423)
  [人人面试题](http://www.w3cfuns.com/thread-5591957-1-1.html)
  [阿里前端面试题](http://www.w3cfuns.com/thread-5598563-2-1.html)
  [腾讯面试题](http://www.w3cfuns.com/article-5599657-1-1.html) 
  [年后跳槽那点事：乐视+金山+360面试之行](http://www.cnblogs.com/lvdabao/p/3660707.html)
  [阿里前端面试题上线](http://fatesinger.com/2722.html)
  [拉勾网js面试题](http://www.cnblogs.com/52cik/p/js-question-lg.html)
  [前端面试](http://www.cnblogs.com/allenxing/p/3724382.html)
  [Web开发笔试面试题 大全](http://mianshiti.diandian.com/)
  [前端开发面试题](http://segmentfault.com/a/1190000000465431)
  [2014最新面试题](http://www.html-js.com/article/1743)
  [2014最新前端面试题](https://github.com/markyun/My-blog/tree/master/Front-end-Developer-Questions)
  [百度面试](https://github.com/fex-team/interview-questions)
  [面试题](http://www.w3cfuns.com/forum.php?mod=forumdisplay&fid=51&filter=typeid&typeid=177)
  [前端工作面试问题](https://github.com/darcyclarke/Front-end-Developer-Interview-Questions/tree/master/Chinese)
  [前端开发面试题](http://segmentfault.com/a/1190000000465431)
  [5个经典的前端面试问题](http://ourjs.com/detail/5%E4%B8%AA%E7%BB%8F%E5%85%B8%E7%9A%84%E5%89%8D%E7%AB%AF%E9%9D%A2%E8%AF%95%E9%97%AE%E9%A2%98)
  [最全前端面试问题及答案总结](http://segmentfault.com/a/1190000002562454)
  [如何面试一名前端开发工程师？](http://www.html-js.com/article/Large-search-front-team-column%202961)
  [世上最全面试题](https://github.com/hawx1993/Front-end-Interview-questions)