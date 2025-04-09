=== Kim email login ===
Contributors: kim
Tags: smtp, email, mail, login, statistics
Requires at least: 5.0
Tested up to: 6.7
Stable tag: 1.1.4
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

使用 SMTP 配置和邮件统计实现的安全 WordPress 邮件管理插件。

== 描述 ==

Kim 邮件登录是一个 WordPress 插件，提供以下功能：

* 通过外部 SMTP 服务器发送邮件
* 支持 TLS/SSL 加密
* 邮件发送统计功能
* 测试邮件发送
* 调试模式
* 禁用 WordPress 默认邮件功能

== 安装 ==

1. 下载插件 ZIP 文件
2. 在 WordPress 后台 > 插件 > 安装插件 > 上传插件
3. 激活插件
4. 进入 设置 > Kim 邮件登录 配置 SMTP 设置

== 常见问题 ==

= SMTP 连接失败怎么办？ =
1. 检查主机地址、端口和加密设置
2. 确认用户名和密码正确
3. 检查服务器防火墙设置
4. 尝试使用不同的加密方式

= 测试邮件发送失败 =
1. 确保已正确保存设置
2. 检查收件人邮箱地址是否正确
3. 查看服务器错误日志获取更多信息

== 更新日志 ==

= 1.1.4 =
*修复无法正常发送测试邮件
*改进统计表单两列横向排布

= 1.1.1 =
* 修复了 SMTP 密码加密问题
* 改进了错误提示信息
* 增加了更详细的配置建议

= 1.1.0 =
* 添加了邮件统计功能
* 增加了仪表盘小工具
* 改进了设置界面

= 1.0.0 =
* 初始版本发布

== 高级使用 ==

您可以通过以下过滤器自定义插件行为：

`kim_email_login_capability` - 修改访问插件所需的权限
`kim_email_login_settings` - 修改默认设置值

== 截图 ==

1. 设置页面截图
2. 统计信息截图
3. 测试邮件截图

== 贡献者 ==

* kim

插件主页: [https://blog.lekims.com/](https://blog.lekims.com/)
