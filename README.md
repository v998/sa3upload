# sa3upload
sa3Upload GAE網盤

**The source code from the original author could be found on https://bitbucket.org/benmao/sa3upload**

**This app has been migrated to Python 2.7 since Google App Engine has shutdown support for Python 2.5 on June 20, 2017.**

## 特點

1. 單個文件限制10M
2. 每天流量1G
3. 可以綁定自己的域名

## INSTALL

1. 修改src/app.yaml，把sa3upload替換為您自己的APP ID
2. 使用 "appcfg.py update 目錄地址" 命令，將代碼上傳到App.
