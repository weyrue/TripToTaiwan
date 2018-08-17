# TripToTaiwan

git config 问题：

1. 查看系统config
   git config --system --list
　 查看当前用户（global）配置
   git config --global  --list
   查看当前仓库配置信息
   git config --local  --list
   
2. 若http.proxy 为 http://www.google.com:80 时，会导致无法链接GitHub，解决办法为：
   #unset Proxy
   git config --global --unset http.proxy
   
   git config --global --unset https.proxy
3.
