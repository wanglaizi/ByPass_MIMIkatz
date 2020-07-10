# ByPass_MIMIkatz

mimikatz 原版免杀，仅供安全研究
----------------------------------
1、删除OR替换源码内相关特征；注释、无用空行等。
2、upx压缩，删除PE里面带upx相关字段。
3、伪造签名。

无任何技术亮点，勿喷!!
example
xxx.exe privilege::debug sekurlsa::logonpassword
参考如上自行替换命令参数
