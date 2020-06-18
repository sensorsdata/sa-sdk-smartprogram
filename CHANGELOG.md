## 0.7.0(2020-04-13)
1. 新增
    - 新增控制台 `log` 日志显示开启/关闭功能；
    - 新增 `logout()` 接口；

## 0.6.0(2020-04-08)
1. 新增
    - 新增全埋点版百度小程序 `SDK`；使用文档 `https://manual.sensorsdata.cn/sa/latest/page-7544539.html`

## 0.5.0(2020-03-30)
1. 新增
    - 新增 `init()` 接口。注意：在调用 `init()` 接口之前，采集的数据被缓存在内存中；调用 `init()` 接口后，会将缓存的数据通过网络发送出去！！！；
    - 新增渠道采集功能；
2. 优化
    - 去掉了 `sensorsdata_conf.js` 文件，增加 `setPara()` 方法初始化配置参数！！！新版集成文档 `https://manual.sensorsdata.cn/sa/latest/tech_sdk_client_mp_bd-1573898.html#id-.%E7%99%BE%E5%BA%A6%E5%B0%8F%E7%A8%8B%E5%BA%8FSDKv1.13-%E9%9B%86%E6%88%90%E4%B8%8E%E4%BD%BF%E7%94%A8`；

## 0.4.0
1. 优化
    - 全局定义 `mpshow_time`

## 0.3.0
1. 优化
    - 修改 `$os` 的取值

## 0.2.0
1. 新增
    - 新增全埋点

## 0.1.0
1. 第一个版本