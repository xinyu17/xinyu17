#Self-discipline Give me freedom
--------------------------------

## 监控对象
 -  数据库实例

## 监控项
 - 主从延迟
 - 并发连接数
 - DML增量数
 - 数据库链接与增删改查
 - 慢查询增量数

## 告警粒度
 - 重试次数 <连续N次失败告警>
 - 以监控对象为粒度的告警暂停和开始
 - 告警级别 <邮件 - 短信 - 电话>
 - 告警接受人

# Monitor 应该具有哪些特质
 - 可以灵活的添加删除监控对象、监控项 <通过数据表控制>。
 - 具有健康的告警机制。可灵活的设置告警粒度。
 - 独立模块，具有良好的移植和扩展性。
 - 完整的回调处理 <后续配合Controller模块进行告警响应>。
 - 标准的日志记录 <是否配合graphite进行监控数据记录>。
 - 良好的扩展性 <后续添加支持NoSQL监控>。



