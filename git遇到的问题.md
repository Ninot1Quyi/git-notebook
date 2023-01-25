Q：![image-20230125113615287](https://raw.githubusercontent.com/Ninot1Quyi/Typora-s-picture/master/img/image-20230125113615287.png)

A：git config --global http.sslVerify false



Q:![image-20230125131902197](assets/image-20230125131902197.png)

A:原因：本地拉取项目后，仓库文件被修改，导致两方面数据不一致

​	解决方法：下班push，上班pull

​	发现这种问题是应该使用  git pull 重新拉取一下仓库文件，然后再git push即可