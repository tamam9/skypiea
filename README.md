# 

<html>
<body>
win10 下配置genymotion</br>
  Genymotion 是当今最给力的安卓模拟器。可配置，应用没那么顺畅。
  下面我给出了我怎么配置模拟器</br>
  1.装genymotion再下virtual box，推荐genymotion和virtual box 分开下最新版本。
  genymotion官方地址  https://www.genymotion.com
  virtual box 官方地址     www.virtualbox.org/ </br>
  2.genymotion和virtual box 设置成 win7兼容模式</br>
  3.virtual box 配置: 进入virtual box 界面，管理-全局设置-网络-仅主机(Host-only)网络，在此如果有多个适配器其中一个留下其余都删掉。
  4.双击配置：第一部分 ip地址192.168.56.1，子网掩码255.255.255.0。第二部分   服务器地址 192.168.56.100，服务器子网掩码 255.255.255.0，
  最小地址 192.168.56.101,最大地址  192.168.56.254  。</br>
  5.重启，打开virtual box,再打开genymotion 就ok了。</br>
</br>
ps：想下系统的童鞋很有可能不会顺利下下系统，这里你可以手动下载系统，再把系统放在C:\Users\用户名\AppData\Local\Genymobile\Genymotion\ova 目录下，再重新走一遍下系统流程就可以成功添加系统到你的genymotion目录下。那么怎么手动下？你走一遍正规的下系统流程，整个过程会记录在log里面。log地址  C:\Users\用户名\AppData\Local\Genymobile\genymotion.log  。从最下面开始往上找 有没有 downloading ，再把对应的下载地址复制过来就行了。


  
</body>

</html>
