# 星展银行客户活动管理平台


### 环境准备

- 安装 [Node.js](https://nodejs.org/en)
- 安装 [pnpm](https://pnpm.io/installation)

### 操作步骤

- 安装依赖

```sh
pnpm install
```

- 启动 Dev Server

```sh
pnpm run dev
```

- 在浏览器访问 http://localhost:3000

1. 应用概述
新加坡银行客户事件管理系统是一个数字化活动管理平台，用于优化私人银行客户活动的全流程管理，从活动创建、客户提名审批到活动后分析。

2. 功能列表
2.1 功能概览
系统包含以下主要页面：

活动管理页面：创建/编辑活动、设置筛选标准、广播活动通知
客户提名页面：筛选客户、提交提名、跟踪审批状态
审批中心页面：多级审批流程、席位管理、最终名单确认
邀请管理页面：自动生成邀请、RSVP跟踪、座位分配
活动执行页面：现场签到通知、座位引导、实时提醒
分析报告页面：出席统计、反馈分析、ROI评估
2.2 功能详情
页面名称	功能模块	功能描述
活动管理	活动创建	设置活动主题/时间/地点，定义客户筛选标准(AUM/收入等)
活动广播	向指定银行家群体发布活动通知，附带筛选标准
客户提名	客户筛选	按标准筛选现有/潜在客户，支持多条件组合查询
提名提交	提交客户名单，自动生成提名报告，状态追踪
审批中心	多级审批	基于角色的审批流程(助理→银行家→经理)
席位管理	设置活动总席位，按优先级分配，避免超员
邀请管理	邀请生成	自动套用银行品牌模板，个性化客户邀请函
RSVP管理	跟踪客户确认状态，自动提醒未回复客户
座位分配	根据客户级别/关系自动分配座位，支持手动调整
活动执行	签到通知	客户到达时自动通知负责银行家
现场引导	显示客户座位图，提供导航指引
分析报告	出席分析	统计出席率，分析客户层级分布
反馈收集	自动发送满意度调查，收集客户反馈
ROI评估	计算活动成本效益，生成可视化报告
3. 界面设计
全局设计风格:

专业金融风格，深蓝色主色调(#002366)
简洁清晰的布局，最大化数据可见性
Segoe UI字体，符合微软产品设计规范
微交互动画增强用户体验
页面名称	功能界面	设计细节
活动管理	创建表单	分步骤向导式设计，必填项醒目标记
客户提名	筛选面板	多条件筛选器固定在左侧，结果分页显示
审批中心	审批看板	卡片式设计，待办事项突出显示
邀请管理	模板预览	实时预览邀请函效果，支持快速调整
活动执行	现场视图	平面图+列表双视图，支持搜索筛选
分析报告	数据看板	PowerBI集成，可交互图表和过滤器