# StudyNotes-GitHub-README.md
学习笔记之--怎么编辑github上的README



# h5-study
html5学习
#GitHub上README.md排版样式教程 
#####来源于[http://blog.csdn.net/u012067966/article/details/50736647](http://blog.csdn.net/u012067966/article/details/50736647)
README文件后缀名为md。md是markdown的缩写，markdown是一种编辑博客的语言。
 ##二级标题  
###三级标题  
####四级标题  
#####五级标题  
######六级标题  

------------------------------------------------------------


###一.显示文本
####普通文本
直接输入的文字就是普通文本。需要注意的是要换行的时候不能直接通过回车来换行，需要使用<br>(或者<br/>)。也就是html里面的标签。<br>
例如：<br>
这是一段普通的文本，
直接回车不能换行，<br>
要使用\<br>
####单行文本
使用两个Tab符实现单行文本。<br>
例如：<br>
    这是一个单行的文本框,只要两个Tab再输入文字即可 
####多行文本
多行文本和单行文本异曲同工，只要在每行行首加两个Tab<br>
例如：<br>
    这是一个有多行的文本框  
    你可以写入代码等,每行文字只要输入两个Tab再输入文字即可  
    这里你可以输入一段代码  
####部分文字的高亮
如果你想使一段话中部分文字高亮显示，来起到突出强调的作用，那么可以把它用 `  ` 包围起来。注意这不是单引号，而是Tab上方，数字1左边的按键（注意使用英文输入法）。<br>
例如：Thank `You` . Please `Call` Me `Coder`
####文字超链接
给一段文字加入超链接的格式是这样的 [ 要显示的文字 ]( 链接的地址 )。比如：<br>
[百度](http://www.baidu.com)

----------------------------------------------------------------------------------------

###二.插入符号
####圆点符
编辑的时候使用的是星号 *<br>
例如：
* 别名：隔壁老王  
* 英文名：Jelly  <br>
此外还有二级圆点和三级圆点。就是多加一个Tab。<br>
例如：
     * 脚本语言  
        * Python 

####缩进
>数据结构
>>树  
>>>二叉树  
>>>>平衡二叉树  
>>>>>满二叉树

--------------------------------------------

###三.插入图片
####来源于网络的图片
即 叹号! + 方括号[ ] + 括号( ) 其中叹号里是图片的URL。<br>
如果不加叹号! ,就会变成普通文本baidu了。<br>
    ![](http://www.baidu.com/img/bdlogo.gif)  
 
 ----------------------------------------------------
 alarmclock  
==  
alarmclock  
-  
alarmclock  
  
*single asterisks*  
  
**double asterisks**  
  
***tripple asterisks***  
  
- - -  
* * *  
  
这是一个普通段落：  
  
protected void onCreate(Bundle savedInstanceState) {  
super.onCreate(savedInstanceState);  
setContentView(R.layout.activity_main);  
iniView();   
}  
  
![github](/res/drawable-hdpi/ic_launcher.png) 
