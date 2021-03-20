# fckeditor-upload-dircheck
# 介绍
此工具主要对fckeditor编辑器的上传路径进行检测，目录字典为`dir_fckeditor.txt`，各位大佬也可以根据自己需求、经验进行字典的添加。
# 安装
```
pip3 install requests
```
# 使用
```
python3 fckeditor_check.py url
```
# 示例
```
> python3 fckeditor_dircheck.py https://www.xxx.com
[-] 404 https://www.xxx.com/fckeditor/editor/filemanager/browser/default/connectors/test.html
[-] 404 https://www.xxx.com/fckeditor/editor/filemanager/upload/test.html
[-] Connection Failed https://www.xxx.com/fckeditor/editor/filemanager/connectors/test.html
[+] 200 1293 https://www.xxx.com/fckeditor/editor/filemanager/connectors/uploadtest.html
……
```

![](https://teamssix.oss-cn-hangzhou.aliyuncs.com/TeamsSix_Subscription_Logo2.png)
