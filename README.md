# vite+vue3搭建uniapp开发环境

## ⚠️前排提示

目前 uniapp 对 Vue3 的支持还处于 alpha 版，即开发阶段，大概率是会遇到很多问题的，个人不建议uniapp上vue3

## 安装

```sh
npm i
```

## 运行、发布uni-app

```
npm run dev:%PLATFORM%
npm run build:%PLATFORM%
```

%PLATFORM% 可取值如下：

| 值                      | 平台                                                         |
| :---------------------- | :----------------------------------------------------------- |
| app-plus                | app平台生成打包资源（支持npm run build:app-plus，可用于持续集成。不支持run，运行调试仍需在HBuilderX中操作） |
| h5                      | h5                                                           |
| mp-alipay               | 支付宝小程序                                                 |
| mp-baidu                | 百度小程序                                                   |
| mp-weixin               | 微信小程序                                                   |
| mp-toutiao              | 字节跳动小程序                                               |
| mp-lark                 | 飞书小程序                                                   |
| mp-qq                   | QQ小程序                                                     |
| mp-360                  | 360小程序                                                    |
| mp-kuaishou             | 快手小程序                                                   |
| quickapp-webview        | 快应用(webview)                                              |
| quickapp-webview-union  | 快应用联盟                                                   |
| quickapp-webview-huawei | 快应用华为                                                   |
