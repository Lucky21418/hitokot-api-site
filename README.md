## hitokot-api-site 毒鸡汤

#### 预览网站
<a herf="https://du.co2.press" target="_blank">毒鸡汤｜碳导航</a> https://du.co2.press

#### 环境要求
PHP 5.7-7.3

#### 项目说明
1. 项目源自owen0o0的<a herf="https://github.com/owen0o0/dujitang" target="_blank">dujitang</a> https://github.com/owen0o0/dujitang
2. Fontawesome文件分图标字体和一言字体，小水管建议屏蔽一言字体，也可以考虑托管到CDN
3. CSS文件、字体文件、图片文件托管到了<a herf="https://www.jsdelivr.com" target="_blank">Jsdelivr</a> https://www.jsdelivr.com ，可以改成自己的

#### 安装说明
1. 下载源码，修改index.htm中需要调整的信息
2. 上传所有文件到普通站点根目录下即可访问

#### 网页调用说明

```
<script type="text/javascript" src="https://你的域名/api/?format=js&charset=utf-8"></script>
<div id="hitokoto"><script>hitokoto()</script></div>
```
