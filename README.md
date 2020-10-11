使用说明
</br>
测试样例：
</br>
**输入**
```
导师：张三
2016级博士生：天一、王二、吴五
2015级硕士生：李四、王五、许六
2016级硕士生：刘一、李二、李三
2017级本科生：刘六、琪七、司四
//空一行
刘六：JAVA、数学建模
//空一行
李二：字节跳动、京东云
//空两行

导师：陈小
2016级博士生：郑中、宋大
```
![](https://img2020.cnblogs.com/blog/2145855/202010/2145855-20201012001933123-2106424555.png)


**输出**
![](https://img2020.cnblogs.com/blog/2145855/202010/2145855-20201012001805225-413406217.png)
![](https://img2020.cnblogs.com/blog/2145855/202010/2145855-20201012001819865-1639137128.png)



**注**：
</br>
1、请使用谷歌浏览器并输入关键词"导师："，"级博士生："，"级硕士生："，"级本科生："和"、"，其中同一位导师的多个同级学生之间用顿号隔开，**顿号**和**冒号**均仅支持**中文字符**。
</br>
2、当输入多个不同的导师所带的学生信息时，需要在上一个导师所带学生的技能树或经历后**空两行**，再输入下一个导师的相关信息。
</br>
3、点击"生成"按钮后，**需要滑动下拉到下面的页面查看所生成的学术家族树**，一个页面显示一位导师的学术家族树，当同时输入多个用例时，将生成多个对应的页面。
</br>
4、点击树的**根节点**后，将在页面上方弹出提示框，显示已输入的该学生所具备的技能和相关经历。点击提示框右下方的"OK"后，才可继续缩放其它节点；点击树的**非根节点**后，点击提示框右下方的"OK"，即可将其所有子节点收起。
</br>
5、**支持**导师和学生的英文名输入，**支持**只有导师姓名没有学生信息的情况，**不支持**仅输入学生信息没有输入导师姓名的情况。
