# test
##project viewers
>me  

>you  
>they

## project going
* project1
	* project2
	* projet3

### 需求确认
**1.缓存**<br>
所有频道共用缓存，http和https共用缓存，缓存时间尽可能长;  
**2.回源**   
提供了电信、联通及移动3条回源链路。默认走电信、联通走联通、移动和铁通走移动   
**3. 其他特殊配置**
* 404 缓存5分钟
* 0字节文件不缓存
* 需要对文件md5做校验

>> 20161104 回源链路 
![pics](http://test.dl.qingcdn.com/test.jpg "ceshi")

## 部署实施

## 研发需求进度
### 基于HMAC的时间戳防盗链
* 志道开发中，预计一周时间，11月25号前提供
### 乱序range请求支持
* 晓波之前为了解决京东的问题，已经开发了一个版本，可以支持这个功能，需要灰度上线
* 灰度上线计划
	* 11月17号之前已经在做tcpcopy的测试；
	* 11月17号开始做线上小批量灰度；


| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

