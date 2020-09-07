# ha_file_explorer
在HA里使用的文件管理器



## 使用方式


```
# 默认配置
ha_file_explorer:

```

```

# 完整配置
ha_file_explorer:
  sidebar_title: 文件管理
  sidebar_icon: mdi:folder
  access_key: 七牛云配置
  secret_key: 七牛云配置
  bucket_name: 七牛云配置
  prefix: 七牛云上传文件前缀(用来区分多个HA)
  download: 七牛云自定义域名[http://xxx.xxx.com/]（用来下载备份文件）
```


## 更新日志

### 2020-09-07
- 使用子线程开启拉取功能

### 2020-08-13
- 新增上传文件夹功能
- 升级qiniu依赖库
- 优化界面

### v2.1
- 新增备份上传服务
- 修复上传异常兼容性问题
- 新增删除云备份功能
- 升级依赖库到最新版本

### v2.0
- 上传文件可以修改名称
- 新增下载网络文件的功能
- 修复编辑页面主题未同步的问题
- 按名称降序排列

### v1.9
- 主题跟着系统变
- 加入文件上传功能
- 调整更新列表
- 修复备份列表出错不提示的问题

### v1.8
- 支持新建文件夹
- 备份列表排序
- 添加拉取其它GitHub项目功能
- 修改备份目录
- 支持还原备份的文件夹

### v1.7
- 加入拉取最新代码测试功能
- 文件列表分类排序
- 删除WebLink引入，兼容HomeAssistant 0.107版本

### v1.6
- 加入备份全选功能
- 修复云备份列表时间错误的问题
- 云备份过滤掉tts目录
- 修复无法打开空目录的问题
- 支持显示文件夹占用空间大小
- 修复切换目录时，编辑框无法隐藏的问题
- 修复列表接口读取文件偶尔错误的问题
- 修复更新逻辑错误

### v1.5
- 加入新建文件的功能
- 修复服务配置错误的问题

### v1.4
- 加入单个(文件/文件夹)备份
- 查询云端文件列表
- 备份文件上传后自动删除本地临时文件
- 移动端加入HA菜单功能（可控制HA菜单的隐藏显示）
- 加入重新加载功能（无需重启HA就能升级本组件）

### v1.3
- 修复隐藏文件夹不显示的问题
- 修复隐藏文件不能编辑的问题
- 修复在HA的APP中不能使用的问题
- 加入七牛云备份功能

### v1.2
- 调整打开方式
- 加入删除功能
- 修复菜单被隐藏的问题
- 修复小屏幕操作菜单换行的问题

### v1.1
- 加入文本格式编辑器
- 修复html文件直接被解析的问题
- 隐藏头部标题
- 修复py文件格式显示不正确的问题

### v1.0
- 实现查看功能
- 文本编辑功能