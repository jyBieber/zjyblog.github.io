# 个人作品集测试页

## 关于我
你好，我是朱嘉宜。以下是我的一些示例作品和技能展示。

## 作品展示

## Java

### 1. 校园外卖跑腿系统
一个面向高校场景的外卖及跑腿服务平台，支持学生点餐、骑手接单、商家及后台管理。

- **技术栈**：SSM (Spring + SpringMVC + MyBatis), MySQL, Bootstrap, ECharts
- **核心功能**：
  - 用户端：浏览商家、下单、追踪订单状态
  - 骑手端：抢单/派单、更新配送状态
  - 管理端：订单统计、用户管理、收益分析 (ECharts 图表)
- **主要工作**：
  - 设计订单状态机，使用乐观锁防止超卖与重复接单
  - 基于 Spring 定时任务自动处理超时订单
  - 采用 AOP 实现全局日志记录与性能监控
- **项目地址**：[GitHub 仓库](https://github.com/jyBieber/school)

**界面截图**：  
![管理员首页](/img/school/admin.png)  
![任务界面](/img/school/list.png)  
![接单界面](/img/school/errandslist.png)  
![登录页](/img/school/login.png)

> 该项目完整实现了从下单到配送的业务闭环，锻炼了复杂业务逻辑设计与数据库事务处理能力。

---

### 2. 游泳馆会员管理系统
为线下游泳馆开发的会员管理平台，提升会员办卡、消费与统计的效率。

- **技术栈**：SSM (Spring + SpringMVC + MyBatis), MySQL, Bootstrap, AJAX
- **核心功能**：
  - 会员管理：办卡、续费、签到、消费记录
  - 卡类型管理：支持多种卡种与折扣规则
  - 数据统计：会员增长、收入报表、到期提醒
- **主要工作**：
  - 独立完成数据库设计与索引优化
  - 实现分页搜索、Excel 导出功能
  - 使用拦截器实现登录验证与权限控制
  - 基于 AJAX 实现无刷新签到与余额更新
- **项目地址**：[GitHub 仓库](https://github.com/jyBieber/Swimming)

**界面截图**：  
![用户界面](/img/swin/user.png)  
![登录界面](/img/swin/login.png) 
![首页](/img/swin/home.png)

> 该项目强化了对 MyBatis 动态 SQL、SpringMVC 拦截器以及前端交互的实践，是一个完整的“增删改查+”企业级案例。
