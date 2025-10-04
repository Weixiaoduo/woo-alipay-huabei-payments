# Woo Alipay - Huabei Installment Extension

一个 WooCommerce 插件，用于独立启用支付宝花呗分期支付网关。

## 描述

本插件是 Woo Alipay 核心插件的扩展，专门用于启用支付宝花呗分期支付功能。需要先安装并启用 WooCommerce 和 Woo Alipay 核心插件。

## 功能特性

- 🌸 支持支付宝花呗分期支付
- 🔧 独立启用和管理花呗网关
- 📦 支持 WooCommerce Blocks
- ⚙️ 自动设置管理快捷入口
- 🎨 包含独立的样式和脚本文件

## 系统要求

- WordPress 5.0+
- WooCommerce 3.0+
- Woo Alipay 核心插件

## 安装方法

1. 下载插件压缩包
2. 在 WordPress 后台进入 "插件" > "安装插件" > "上传插件"
3. 选择压缩包并上传
4. 激活插件

## 使用说明

1. 确保已安装并启用 WooCommerce 和 Woo Alipay 核心插件
2. 在 WooCommerce 设置中找到 "结账" > "花呗分期"
3. 配置相关参数和设置
4. 启用网关

## 文件结构

```
woo-alipay-huabei/
├── woo-alipay-huabei.php    # 主插件文件
├── bootstrap.php            # 插件引导文件
├── inc/                     # 核心类文件
│   ├── class-wc-alipay-installment.php
│   └── class-wc-alipay-installment-blocks-support.php
├── css/                     # 样式文件
├── js/                      # JavaScript 文件
└── README.md               # 说明文档
```

## 技术信息

- **插件版本**: 0.1.0
- **作者**: WooCN.com
- **插件主页**: https://woocn.com/
- **文本域**: woo-alipay-huabei

## 许可证

本插件遵循 WordPress 插件许可证。

## 支持

如有问题或需要支持，请访问 [WooCN.com](https://woocn.com/)。