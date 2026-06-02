# 你好，我是程序员小蔡

AI + Cocos 游戏前端开发工程师，现居广州，求职方向为广州地区游戏前端开发岗位。

我主要做 Cocos Creator 游戏前端开发，也具备 Vue、uni-app 小程序、Go 游戏后端、Egret、Unity 项目经验。日常开发中会结合 GPT / Codex 做需求拆解、代码实现、问题排查和文档整理，提升工程交付效率。

## 关于我

- 求职定位：AI + Cocos 游戏前端开发工程师
- 核心方向：Cocos Creator 游戏前端、TypeScript / JavaScript、AI 辅助开发
- 主要经验：游戏前端开发，包含 UI 交互、玩法逻辑、资源管理、工程构建、接口联调、Android 端对接
- 扩展能力：Vue 移动端 Web、uni-app 小程序、Go 游戏后端、Unity / Egret 游戏项目
- 期望城市：广州
- 联系邮箱：[507961037@qq.com](mailto:507961037@qq.com)

## 技术栈

| 分类 | 技术与能力 |
| --- | --- |
| 游戏开发 | Cocos Creator、TypeScript、JavaScript、Unity、Egret |
| AI 开发 | GPT、Codex、Prompt、AI 辅助编码、AI 辅助调试、自动化开发 |
| 前端 / 跨端 | Vue 3、Vite、Vant、uni-app、Pinia、小程序、移动端适配 |
| 后端协作 | Go、Gin、WebSocket、Protobuf、Redis、PostgreSQL、MQTT |
| 工程交付 | 私有项目脱敏展示、接口联调、构建配置、问题排查、文档沉淀 |

## 项目展示

> 当前项目多数为私有仓库，主页先展示项目类型、技术栈和负责方向。后续可补充脱敏后的 README、截图、动图、架构说明和开发复盘，不默认公开源码。

| 项目 | 类型 | 技术栈 | 展示重点 |
| --- | --- | --- | --- |
| 线下拉霸机 + 炮台打动物游戏 | Cocos Android 机台游戏 | Cocos Creator 2.4.15、TypeScript、Android JSB、WebSocket、Protobuf | 拉霸 + 打动物联合玩法、资源预加载、UI 管理、协议联调、Android 原生能力对接 |
| 交易所 | Vue 移动端 Web 项目 | Vue 3、Vite、TypeScript、Vant、Axios、ECharts、vue-i18n | 移动端交易业务页面、登录 / 市场 / 资产 / C2C / 广告等模块、接口代理、多语言和移动端适配 |
| 积分商城 | uni-app 积分商城小程序 | uni-app、Vue 3、Vite、Pinia、uview-plus、wot-design-uni | 首页、分类、购物车、我的、订单、优惠券、地址、支付等商城业务流程 |
| 拉霸机游戏后端 | Go 游戏后端项目 | Go、Gin、WebSocket、Protobuf、Redis、PostgreSQL、MQTT、GORM | 游戏 WebSocket 协议、余额缓存、批量落库、MQTT 管理、健康检查、客户端错误日志 |
| 208 游戏 | Unity 机台 / 桌台游戏 | Unity 5.6.3f1、C#、Socket、Protobuf、串口通信、AssetBundle | 桌台玩法界面、登录 / 重连、串口按键采集、跑灯 / 得分 / 筹码指令、资源打包 |
| 竞猜游戏平台 | Egret H5 游戏项目 | Egret 3.2.6、TypeScript、EUI、WebSocket、资源管理 | 动物园、转盘、西游记、排行榜、活动、支付跳转、资源加载和断线重连 |

## 重点项目能力

### Cocos 游戏前端：线下拉霸机 + 炮台打动物游戏

- 面向 Android 机台运行，不是普通 H5 小游戏，涉及 Cocos 前端与 Android 原生层协作。
- 负责游戏 UI、拉霸玩法、打动物玩法、资源预加载、音效、弹窗和后台运维界面等前端逻辑。
- 使用 WebSocket + Protobuf 对接后端协议，处理登录、心跳、重连、房间切换、游戏结果和配置下发。
- 对接 Android JSB 能力，包括设备信息、本地配置、存储权限、APK 更新、串口 / UDP / 热点等机台相关能力。

### Vue 移动端 Web：交易所

- 基于 Vue 3 + Vite + Vant 开发移动端业务页面。
- 覆盖登录注册、市场行情、资产、充值提现、C2C、广告、订单、活动、公告、多语言等模块。
- 使用 Axios、路由守卫、全局状态、移动端 rem 适配和接口代理完成移动端交付。

### uni-app 小程序：积分商城

- 基于 uni-app + Vue 3 + Pinia 开发积分商城类项目。
- 覆盖首页、分类、购物车、我的、商品详情、订单、优惠券、收货地址、支付等业务流程。
- 支持多端构建能力，包含微信小程序、H5 以及其他小程序平台构建配置。

### Go 游戏后端：拉霸机游戏后端

- 基于 Go + Gin 搭建游戏后端服务，提供 HTTP API 和 WebSocket 入口。
- 使用 Protobuf 组织游戏协议，支持登录、配置、拉霸玩法和客户端错误上报。
- 使用 Redis + PostgreSQL + GORM 做余额、记录和缓存管理，并通过批量刷盘降低高频写入压力。
- 封装 MQTT 连接、订阅、发布和重连管理，支持服务运行状态检查。

### Unity 游戏项目：208 游戏

- 基于 Unity 5.6.3f1 + C# 开发机台 / 桌台类游戏。
- 包含登录、Socket 连接、Protobuf 协议、桌台界面、下注展示、倒计时、历史记录等模块。
- 对接串口通信，处理机台按键采集、跑灯、得分、筹码切换、指令重发和资源关闭。

### Egret H5 游戏：竞猜游戏平台

- 基于 Egret 3.2.6 + TypeScript + EUI 开发 H5 游戏项目。
- 包含动物园、转盘、西游记、排行榜、活动、任务、支付跳转等多个业务模块。
- 使用 WebSocket 二进制协议、资源分组加载、主题加载、错误上报和断线重连支撑游戏运行。

## 正在建设的公开展示内容

- Cocos 项目展示仓库：整理脱敏后的项目背景、模块结构、核心流程和截图 / 动图。
- Go 游戏后端展示仓库：整理服务结构、协议说明、余额缓存和 WebSocket 流程。
- 跨端项目展示仓库：整理 Vue / uni-app 项目的页面结构、业务流程和接口联调说明。

## 联系我

- GitHub：[github.com/Cczp](https://github.com/Cczp)
- 邮箱：[507961037@qq.com](mailto:507961037@qq.com)
- 城市：广州
