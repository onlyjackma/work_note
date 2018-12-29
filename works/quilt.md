# 工作笔记-quilt
## quilt简单使用方法
1. 添加补丁
```
进入需要打补丁的工程的根路径
1、quilt new xxxxx.patch
2、quilt add xxxx.c
3、cp xxxx.c 或者 quit edit xxxx.c
4、quilt refresh
生成的补丁文件位于$(pwd)/patches/xxxxx.patch
```



