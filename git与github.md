git是一个软件，可以供用户在电脑未联网的情况下查看以前自己完成的程序以及文件，并可以对自己以前的程序进行管理
而github是一个网站，由于网站是一个全球的开源性的网站，在上面有许多计算机方面的大牛，并有一些技术大牛在上面提交的源代码，可以供用户在上面进行学习，也可以与其他人进行交流。


### git 使用流程：
1.建立一个空文件夹，右键选择“Git Bash Here”,输入 git clone 右键选择paste粘贴库地址 回车
2.然后当本地改变时，右键与你库名字相同的那个文件夹，选择“Git GUI Here”,单击Unstaged Changes 下的改变的文件夹，它会移到Staged Changes  ，  然后点击Commit Changes，输入相关的改变内容，再点击Commit ，再点push，出现success就OK了
3当库发生变化，同步到本地，，右键与你库名字相同的那个文件夹，选择“Git GUI Here”,选择Remote>>Fetch from>>origin,  出现success后点击close，再点击Merge>>Local Merge>>Merge，success后点击close
