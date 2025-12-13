# Dscan 自动化安全扫描与资产管理平台
## 项目简介
Dscan​ 是一个功能全面的自动化安全扫描与资产管理平台。它集成了资产发现、漏洞扫描、指纹识别、空间测绘等多种能力，并提供了可视化的态势大屏和专业报告输出，拥有三种主题切换，旨在帮助安全团队高效地进行攻击面管理和漏洞生命周期管理。企鹅qq：2649566514

# 更新记录
## [v1.4]
**功能升级**：新增AI对话模块、适配手机端Web界面
## [v1.3]
**功能升级**：新增Nmap端口扫描模块、威胁分布图、修复hunter的bug
## [v1.2]
**功能升级**：Web界面筛选优化
## [v1.1]
**功能升级**：POC支持在线更新、优化任务列表
## [v1.0]
**POC/指纹升级**：Next.js RCE漏洞、GeoServer XXE注入漏洞、FortiWeb 、Oracle_E_Business 、泛微E Cology等

## 目录
- [登录界面](#登录界面)
- [态势大屏](#态势大屏)
- [首页](#首页)
- [新建扫描](#新建扫描)
- [URL爬虫](#url爬虫)
- [指纹识别](#指纹识别)
- [子域名爆破](#子域名爆破)
- [数据中心](#数据中心)
  - [漏洞发现](#漏洞发现)
  - [资产发现](#资产发现)
  - [扫描报告](#扫描报告)
  - [系统日志](#系统日志)
  - [漏洞情报](#漏洞情报)
  - [空间测绘](#空间测绘)
- [管理中心](#管理中心)
  - [扫描任务](#扫描任务)
  - [定时任务](#定时任务)
  - [POC/指纹](#poc指纹)
  - [分布式节点](#分布式节点)

## 核心功能模块
# 登录界面
**安全认证**：session接口访问控制
![image](https://github.com/kk12-30/Dscan/blob/main/pic/p0.png)
# 态势大屏
**可视化指挥大屏**：严重、高危、中危漏洞的风险分布用饼图呈现得明明白白，还有POC数量、漏洞总数这些核心数据，一目了然。
![image](https://github.com/kk12-30/Dscan/blob/main/pic/p1.png)
# 首页
**多维度数据呈现**：指纹分布和端口分布都做了统计可视化，一眼就能锁定 “高危端口” 和 “易受攻击的系统指纹”，不用自己费劲做数据透视分析。
![image](https://github.com/kk12-30/Dscan/blob/main/pic/p2.png)
# 新建扫描
**一键启动扫描**：支持IP、域名、URL等多种目标输入，灵活配置端口范围、扫描深度、POC选择，轻松发起全方位资产探测与漏洞扫描。
![image](https://github.com/kk12-30/Dscan/blob/main/pic/p5.png)
# URL爬虫
**智能爬虫引擎**：自动抓取目标站点的URL路径、接口地址、敏感文件，为后续漏洞扫描提供全面的攻击面信息。
![image](https://github.com/kk12-30/Dscan/blob/main/pic/p3.png)
# 指纹识别
**精准指纹探测**：识别Web应用框架、CMS系统、中间件版本、操作系统等关键信息，为漏洞利用提供精准情报支撑。
![image](https://github.com/kk12-30/Dscan/blob/main/pic/p4.png)
# 子域名爆破
**子域名发现利器**：内置海量字典，支持DNS爆破与泛解析过滤，快速枚举目标域名下的所有子域名资产。
![image](https://github.com/kk12-30/Dscan/blob/main/pic/p6.png)
# Nmap端口扫描
![image](https://github.com/kk12-30/Dscan/blob/main/pic/pt1.png)
# AI对话
![image](https://github.com/kk12-30/Dscan/blob/main/pic/pt2.png)

# **数据中心*
# 漏洞发现
**漏洞展示库**：集中展示所有扫描发现的漏洞，支持按严重程度、漏洞类型、目标资产多维度筛选。
![image](https://github.com/kk12-30/Dscan/blob/main/pic/p7.png)
![image](https://github.com/kk12-30/Dscan/blob/main/pic/pt2.png)

# 资产发现
**资产清单管理**：资产分组管理，自动归集扫描发现的IP、端口、服务、Web应用等资产信息，构建完整的攻击面资产地图。
![image](https://github.com/kk12-30/Dscan/blob/main/pic/p8.png)
![image](https://github.com/kk12-30/Dscan/blob/main/pic/p9.png)
# 扫描报告
**专业报告输出**：一键生成HTML/Excel格式的扫描报告，包含攻击面综合报告，满足渗透测试交付需求。
![image](https://github.com/kk12-30/Dscan/blob/main/pic/p10.png)
# 系统日志
**全程日志追踪**：记录扫描过程中的每一步操作日志，便于问题排查与任务回溯，确保扫描过程可审计、可追溯。
![image](https://github.com/kk12-30/Dscan/blob/main/pic/p11.png)
# 漏洞情报
**实时威胁情报**：对接最新漏洞情报源，及时推送高危漏洞预警，帮助安全团队快速响应新型威胁。
![image](https://github.com/kk12-30/Dscan/blob/main/pic/p12.png)
# 空间测绘
**网络空间探测**：集成Fofa、Hunter、Quake空间测绘引擎，快速检索互联网暴露资产，扩展攻击面发现范围。
![image](https://github.com/kk12-30/Dscan/blob/main/pic/p13.png)

# **管理中心*
# 扫描任务
**任务调度中心**：查看所有扫描任务的执行状态、进度百分比、耗时统计，支持任务暂停、恢复、终止等操作。
![image](https://github.com/kk12-30/Dscan/blob/main/pic/p14.png)
![image](https://github.com/kk12-30/Dscan/blob/main/pic/p15.png)
# 定时任务
**周期性扫描**：配置定时扫描计划，支持按天、周、月周期自动执行，实现资产安全的持续监控与漏洞巡检，支持钉钉机器人获取结果。
![image](https://github.com/kk12-30/Dscan/blob/main/pic/p16.png)
![image](https://github.com/kk12-30/Dscan/blob/main/pic/p17.png)
# POC/指纹
**武器库管理**：管理内置的POC漏洞检测脚本与指纹识别规则，支持自定义POC导入、启用/禁用、分类管理。
![image](https://github.com/kk12-30/Dscan/blob/main/pic/p18.png)

# 分布式节点
**集群扩展能力**：支持部署多个扫描节点，实现分布式并行扫描，大幅提升大规模资产的扫描效率与吞吐量。
![image](https://github.com/kk12-30/Dscan/blob/main/pic/p19.png)

# 免责声明
本工具仅面向合法授权的企业安全建设行为，如您需要测试本工具的可用性，请自行搭建靶机环境。POC搜集均来源于互联网公开信息，无exp。

在使用本工具进行检测时，您应确保该行为符合当地的法律法规，并且已经取得了足够的授权。请勿对非授权目标进行扫描。

如您在使用本工具的过程中存在任何非法行为，您需自行承担相应后果，我们将不承担任何法律及连带责任。

在安装并使用本工具前，请您务必审慎阅读、充分理解各条款内容，限制、免责条款或者其他涉及您重大权益的条款可能会以加粗、加下划线等形式提示您重点注意。 除非您已充分阅读、完全理解并接受本协议所有条款，否则，请您不要安装并使用本工具。您的使用行为或者您以其他任何明示或者默示方式表示接受本协议的，即视为您已阅读并同意本协议的约束。
