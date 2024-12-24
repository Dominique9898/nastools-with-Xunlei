基于[hsuyelin/nas-tools](https://github.com/hsuyelin/nas-tools) 二次开发, 加入迅雷下载器

## 必要安装
[Docker迅雷](https://github.com/cnk3x/xunlei)

## Docker安装该版本
`docker pull dominique9898/nas-tools`

## 功能特点

### 下载器支持
- QB、TR、Aria2、Transmission 下载器支持
- 迅雷下载器支持 (新增)
  - 支持磁力链接和种子文件下载
  - 支持下载任务管理(开始/暂停/删除)
  - 支持自定义下载目录
  - 支持下载进度显示
  - 支持多设备同步

### 下载器配置
...

#### 迅雷下载器配置
在`设置-下载器`中添加迅雷下载器:
- 名称：自定义名称
- 类型：选择"迅雷"
- 地址：迅雷WebAPI地址(例如: http://192.168.1.100)
- 端口：迅雷WebAPI端口(默认为5055)
- 用户名：迅雷登录用户名
- 密码：迅雷登录密码
- 下载目录：默认下载保存目录

## 配置
...

## 版本更新记录

### v1.x.x
- 新增迅雷下载器支持
  - 支持磁力链接和种子文件下载
  - 支持下载任务管理
  - 支持自定义下载目录
  - 支持下载进度显示
  - 修复已知问题

## 鸣谢
...

## 赞助
...

## 免责声明
...
