# Crack Tracking
裂纹追踪系统

## tips

- 最快支持2s一张图片输入
- 输出坐标时间约为4-6s
- 使用main.py来开始
- 每次开始之前试验机坐标应当清零
- 已知支持1080*1920 .JPG格式输入，其他格式未做测试
- 裂纹生长暂时只支持左右两个方向
- 生成release的时候要加入image、config.ini、model

## v0.00
    First
    
## v0.01
坐标以绝对值而不是相对值的形式传送   
为打包发布做了一些准备，包括IMPORT的精简(吐了，它为啥还这么大啊    
调试了TcpIP通讯
修复了若干bug

## v0.02
第一个release上线啦！！
添加了requirements
