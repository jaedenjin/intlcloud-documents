## 简介
获取图片主色调。目前支持大小在 20M 以内、长宽小于 9999 像素的图片处理。
## 接口形式
download_url?imageAve
## 参数说明
| 参数                                      | 含义                                       |
| --------------------------------------- | ---------------------------------------- |
|download_url                            |文件的访问链接，具体构成为<bucket id>-<appid>.<picture region>.<domain>.com/<picture name>，如 examples-1251000004.picsh.myqcloud.com/sample.jpeg|

## 示例

```
http://examples-1251000004.picsh.myqcloud.com/sample.jpeg?imageAve

```
