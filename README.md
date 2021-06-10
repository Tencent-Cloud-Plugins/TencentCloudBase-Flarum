<p align="center">
  <img height="100px" src="./logo.png" />
</p>

# [Flarum](https://github.com/flarum/flarum)

Flarum 是一款非常简洁的开源论坛软件。它响应快速、简便易用，拥有打造一个成功的社区所需的所有功能。YOURLS是一款开源免费的URL短链接管理平台，可利用它构建URL缩短服务并追踪访问效果。

## 部署

本项目基于开源项目 [CloudBase Framework](https://github.com/Tencent/cloudbase-framework) 开发部署，支持一键云端部署

[![](https://main.qcloudimg.com/raw/67f5a389f1ac6f3b4d04c7256438e44f.svg)](https://console.cloud.tencent.com/tcb/env/index?action=CreateAndDeployCloudBaseProject&appUrl=https%3A%2F%2Fgithub.com%2FTencent-Cloud-Plugins%2FTencentCloudBase-Flarum&branch=master)

### 配置
- `FLARUM_ADMIN_USER`: 管理员用户
- `FLARUM_ADMIN_PASS`: 管理员密码
- `FLARUM_ADMIN_MAIL`: 管理员邮箱

### 依赖

- CynosDB：使用 CynosDB 数据库存储数据
- Cfs：使用 Cfs 持久化存储静态资源，日志等

## 注意事项

1. 部署时，需要将服务路径设置为根路径 `/`
