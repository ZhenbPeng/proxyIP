**************************************************************************
**************************************************************************
************************代理地址获取小程序********************************
***********             ******************           *********************
**************************************************************************

简要说明：
    本程序是一个简单的获取免费代理IP地址的小爬虫，免费代理IP地址来源http://www.xicidaili.com/nn/

文件说明：
    proxyIP.py         主程序文档
    BeautifulSoup.py   bs3源代码，因为这里有使用bs3解析网页，具体信息见https://www.crummy.com/software/BeautifulSoup/bs3/documentation.html
    readme.md          说明文档

运行方法：
    在安装有Python的PC机上运行即可" Python proxyIP.py -o IP.txt -n 1 -d 8"

参数说明：
    -o    输出保存可用代理IP的文件
    -d    线程数目，默认使用单线程
    -n    爬取IP地址页面数目，默认为爬取第1页
    -v    版本号
    -h    帮助说明
    
CopyRight：
    Write by Aunity
    Version 1.0.1
    Update time: 2016-5-24
    Email:y864702062@qq.com
    https://github.com/aunity