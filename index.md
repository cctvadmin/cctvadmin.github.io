# 欢迎来到cctvadmin在Github上的博客  
  
  
  
  
你应该不会爱上这里，因为这里是空的
  
  
  
如果你不嫌麻烦，可以在[**这里**](weixin.png) 给我赞助  
  -----------------------------------------------------  
# 2020/2/22更新
### 解决了窗口切换问题，集成接口的实现,以及窗口出现延迟的线程等待动画，优化了string储存
* 为了解决加载事件，2020/02/22添加了窗口的等待事件，统一使用  
* new LoadingForm().showDialog_Loading()方法加载线程使用  
* 由于string的储存机制不满足存储需求，更新采用了StringBuilder  
* 在H5Class类中，存放了所有HTML的代码以及处理逻辑
* interfaceIMPL接口可以提供实现窗口加载事件，窗口加载禁止使用Form.Show()，可以通过其实现类interfaceImplClass的showForm(Form form)，hideForm(Form form)，indexShowForm(int index)  
## 后续
* 后续将陆续开放自定义HTML,CSS,SCSS,JS
* 招募开发团队：（<strong>*AmateurTeam*</strong>）,请看[http://www.adminznh.ren](http://www.adminznh.ren "CACode官博")<br><br>
 ----  
# 2020/2/24 19：20更新
### 关于页面大概已经做好，目前有BUG：页面自定义部分未加入生成的模板，再IndexLastForm生成的头部nav导航以及页脚均未写入AboutForm中相对应同名的StringBuffer  
* 面下大众开发，有任何疑问或建议可以[联系我](tencent://message/?Menu=yes&uin=2075383131&Service=300&sigT=45a1e5847943b64c6ff3990f8a9e644d2b31356cb0b4ac6b24663a3c8dd0f8aa12a595b1714f9d45 "打开临时会话")
* 团队新增四人[点击链接加入群聊[CACode网页生成器]:](https://jq.qq.com/?_wv=1027&k=5d6hNJT)
 ----  
# 2020/2/24 22:34新思路
#### 新思路:
* 将每一个窗口每一个任务为单独一个线程执行
----
  你可以给我致邮箱:[2075383131@qq.com](tencent://message/?Menu=yes&uin=2075383131&Service=300&sigT=45a1e5847943b64c6ff3990f8a9e644d2b31356cb0b4ac6b24663a3c8dd0f8aa12a595b1714f9d45)
  
  Github:[cctvadmin](https://github.com/cctvadmin/)
