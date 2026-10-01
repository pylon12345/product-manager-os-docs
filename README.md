# AI Product Manager OS｜专业介绍与使用说明

**面向 AI、Agent、SaaS 和已有产品的中文产品决策与交付 Skill。**

适用版本：**v1.1.1**｜文档更新：**2026-10-02**。本仓库提供独立阅读入口；完整 Skill 已在[源码仓库](https://github.com/pylon12345/product-manager-os)公开。

## 阅读导航

| 内容 | 入口 |
|---|---|
| 定位、方法、能力架构、证据与责任边界 | [专业介绍与运营指南](PRODUCT_MANAGER_OS_GUIDE.md) |
| 25 个模式、常用指令、项目记录、知识库和测试 | [详细使用说明](USER_GUIDE.md) |
| Codex、Claude 与 WorkBuddy 安装、升级及排错 | [安装指南](INSTALL.md) |
| 电商售前与售后 AI 客服演练 | [案例](https://github.com/pylon12345/product-manager-os/blob/main/product-manager/examples/ecommerce-customer-service.md) |
| 主入口、修复记录与下载 | [Skill](https://github.com/pylon12345/product-manager-os/blob/main/product-manager/SKILL.md) · [CHANGELOG](https://github.com/pylon12345/product-manager-os/blob/main/product-manager/CHANGELOG.md) · [Releases](https://github.com/pylon12345/product-manager-os/releases) |

它帮助团队确认需求、选择最小验证、控制首版范围、定义研发和 AI 验收，并把真实结果带回下一轮决定。重要结果应包含依据、假设、取舍、Owner、下一动作与复查条件。

## 快速体验

先按[安装指南](INSTALL.md)安装并启用本技能。下面使用 Codex 语法；Claude Code 改用 `/product-manager`，Claude／WorkBuddy 用自然语言指定已安装技能：

```text
$product-manager
我想设计电商售前与售后 AI 客服，目前没有真实咨询数据。
先判断关键问题、首版范围与最小验证。
区分事实、假设和待验证项，不编造数据或宣称已接入系统。
```

本仓库仅包含文档，不包含可安装的 Skill 源码。安装和运行以源码仓库为准；知识库、网页快照、备份、客户资料和本机配置不在两个公开仓库内。

## 本次更新

补齐 Claude Code、Claude 网页／桌面端与 WorkBuddy 安装步骤和调用差异，增加独立安装指南。

同步 v1.1.1 的任务驱动 AI 架构、知识库门禁页处理和按需入口；新增详细手册与案例导航，修正旧文档关于“Skill 未公开”的过期说明。

## 许可

本说明仓库文档继续采用 [CC BY 4.0](LICENSE)，转载、翻译、改编时请署名 pylon12345 并注明出处。链接指向的源码仓库、Skill、脚本与模板采用其 [Apache-2.0 许可](https://github.com/pylon12345/product-manager-os/blob/main/LICENSE)，不因文档镜像而改变。

专业指南和手册是版本化镜像；源码、运行规则与版本变更以[主仓库](https://github.com/pylon12345/product-manager-os)为准。
