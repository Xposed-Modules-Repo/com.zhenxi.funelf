# FunELF   
 
基于Xposed现实的SO文件脱壳机:  
通过hook linker的方式在So加载完毕的时候对So文件进行dump和修复。  
支持无ELF头的soinfo dump修复 。核心修复使用的sofix。
(https://github.com/F8LEFT/SoFixer)  
支持5-13系统。  

使用方式：  
1、Lsposed激活插件
2、在模块页面选择需要脱壳对应的Apk。 
3、启动目标Apk即可。  

修复的So文件保存在/data/data/包名/FunELF/目录下。  
