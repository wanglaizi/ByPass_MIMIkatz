# ByPass_MIMIkatz

mimikatz 原版免杀，仅供安全研究
----------------------------------
1、删除OR替换源码内相关特征；注释、无用空行等。  
2、upx压缩，删除PE里面带upx相关字段。  
3、伪造签名。  
主要是思路，杀了重新做一份即可免杀  
## example   
windows.exe = x64  
linux.exe = x86  

## 更新
MiMikatz 版本：2.2.0 20200918
免杀时间：2021/01/24  
