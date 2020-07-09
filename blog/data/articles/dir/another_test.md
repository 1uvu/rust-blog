# MarkDown 语法图音视数测试

1、文字居中：
左对齐：

2、插入图片及图片居中、定义大小

让图片靠左 显示

基本形式是：![这里放图片描述](这里放图片链接)

例子：![美女漂亮不](https://tse2-mm.cn.bing.net/th?id=OIP.rF3VYN1CRvtyWBPU0I7kyQDMEy&p=0&pid=1.1)



定义尺寸

<img width = '150' height ='150' src ="https://tse2-mm.cn.bing.net/th?id=OIP.rF3VYN1CRvtyWBPU0I7kyQDMEy&p=0&pid=1.1"/>



MarkDown语法进阶（三）（文字居中、图片处理、插入视频音乐、标准字体）

定义大小并居中显示
<div align=center><img width = '150' height ='150' src ="https://tse2-mm.cn.bing.net/th?id=OIP.rF3VYN1CRvtyWBPU0I7kyQDMEy&p=0&pid=1.1"/></div>

MarkDown语法进阶（三）（文字居中、图片处理、插入视频音乐、标准字体）

3、插入音乐（普通音乐标签不生效，网易云音乐 iframe 不生效）

<embed height="86" width="800" src="https://music.163.com/outchain/player?type=2&amp;id=528478901&amp;auto=1&amp;height=66"></embed>

<iframe frameborder="no" border="0" marginwidth="0" marginheight="0" width=330 height=86 src="https://music.163.com/outchain/player?type=2&amp;id=528478901&amp;auto=1&amp;height=66"></iframe>

4、插入视频

不支持优酷，可以用youtube。

<iframe width="560" height="315" src="https://www.youtube.com/embed/Ilg3gGewQ5U" frameborder="0" allowfullscreen></iframe>

5、跳转链接
<a href="http://1uvu.com/" target="_blank">http://1uvu.com/</a>

跳到自己博客列表：

<a href="http://1uvu.com/" target="_blank">http://1uvu.com/</a>

6、使用标准字体
<font face="黑体">我是黑体字</font>
<font face="微软雅黑">我是微软雅黑</font>
<font face="STCAIYUN">我是华文彩云</font>
我是黑体字
我是微软雅黑
我是华文彩云

7、多种矩阵形式输入（这个库有问题，反斜杠会被吸收掉一个）
不带括号的：



$$
\begin{matrix}
1&2 \\\\  3&4 \\\\ 5&6
\end{matrix}
$$

带大括号的：
$$
\left\\{
\begin{matrix}
1&2 \\\\  3&4 \\\\ 5&6
\end{matrix}
\right\\}
$$

带中括号的
$$
\left[
\begin{matrix}
1&2 \\\\  3&4 \\\\ 5&6
\end{matrix}
\right]
$$
