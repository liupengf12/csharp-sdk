**2016-12-01**

最新版本v7.0.0.5

增加：[Fusion](http://developer.qiniu.com/article/index.html#fusion)相关功能

增加： dfop

修复：上传(分片上传)文件发生重试时，上传到空间的文件内容错误

修改：默认不使用CDN（可自行设置）；重试域名和原始上传域名保持一致

* * *


**2016-11-22**

最新版本v7.0.0.3，适用于.NET xx

（xx: 2.0/3.0/3.5/4.0/4.5/4.5.1/4.5.2/4.6/4.6.1/4.6.2）

增加：上传域名默认使用CDN（`Qiniu.Common.Config.UploadFromCDN:Boolean`）

优化：应对更多类型的网络错误（`WebException`）

优化：上传失败重试域名（`upHost`）保持不变

优化：上传分块数量（`blockCount`）计算优化


* * *


**2016-10-28**

优化：上传示例中增加`UpCompleteHandler`的说明


* * *


**2016-10-24**

增加：增加`listFiles`（获取空间文件列表）功能，更新示例及文档


* * *


**2016-10-08**

推出新版本v7


* * *


**2016-08 ~ 2016-09**

增加：`Zone`模块

增加：多机房支持（华东/华北/华南/北美）

增加：示例及说明文档