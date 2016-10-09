# Git-vs-tortoiseGit
<p>
  Git和tortoiseGit共存时候产生的一些问题</br>
  好吧，首先我承认这个问题困扰了N久，废话少说 上问题~</br>
## 概述：起初公司项目和个人github去clone/pull都是没问题的，然而某天不知搞到了哪里 个人的github不好用了...</br>
   错误提示： </br>
   <code>server sent (publickey)</code>
</p>

<p>请教高人或者在网上也是试了N种方法，什么删除某注册表、更改SSH client、重置SSH到个人github甚至卸载安装Git和tortoiseGit...</br>
   当然，既然放在这里说，那结果肯定是问题依然存在de...</br>
   唯一一个感觉比较靠谱的答案是：
   <code>Git和tortoiseGit冲突...</code> 
   但是问题描述也是模模糊糊甚至扑朔迷离 我也是醉醉的了...
   霎时间也是感觉万能的谷歌百度并非万能，出错原因千千万，奈何少了这个问题的正确答案<br>
   突然想起原公司leader说的一句话
   <blockquote>慢慢试着自己去踩坑吧，踩的坑多了ye就化身大神了~</blockquote>
   So, I feel on my own!!!
</p>

<p>
   想来原leader的话真心是真理的，on my own 也是该真理的不错诠释，问题总算被 KO 了。<br>
   放下了谷歌百度的“包袱”，开始自己去探索问题的原因</br>
   关键点就在Git和tortoiseGit冲突，那为什么冲突怎样就不冲突了呢？ </br>
   是否Git和tortoiseGit都有配置文件而最终不知道要走哪个配置文件？ </br> 
   猜想基本正确，有个配置文件Git和tortoiseGit都会去写这个配置文件导致最终不知道该走哪个配置~</br>
   删除该配置文件重新走Git和tortoiseGit的相关配合，</br>
   完美解决问题~</br>
</p>
   
   问题可能并不是多大问题，但是也为摸索中行进中的我竖起了“灯塔”~
   
   <blockquote>慢慢试着自己去踩坑吧，踩的坑多了ye就化身大神了~</blockquote>

