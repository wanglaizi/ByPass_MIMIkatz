# ByPass_MIMIkatz

mimikatz 原版免杀，仅供安全研究
----------------------------------
1、删除OR替换源码内相关特征；注释、无用空行等。  
2、upx压缩，删除PE里面带upx相关字段。  
3、伪造签名。  
主要是思路，杀了重新做一份即可免杀  
## example  
xxx.exe privilege::debug sekurlsa::logonpassword  
参考如上自行替换命令参数  
windows.exe = x64  
linux.exe = x86  

## 更新
MiMikatz 版本：2.2.0 20200715  
免杀时间：2020/7/21 21点43分  

## 参考
https://mp.weixin.qq.com/s/ZaRuK3qV9h-KGqiYT8kqqw
