---
layout: default
title: 隐私政策 · 花前记账
permalink: /privacy/
---
# 隐私政策 · 花前记账

**最后更新:** 2026-05-06
**适用版本:** V1（中国大陆首发）

---

## 一句话总结

花前记账把你的所有财务数据都留在你的手机上。我们没有服务器，看不到你的收入、消费、目标。

## 我们会收集什么 — 仅在你同意之后

只有你在 app 第一次启动时点了「同意并继续」，我们才会收集以下两类数据。任何一项你都可以单独拒绝（点「不同意，仅使用基础功能」），app 的核心功能不会受影响。

### 1. 匿名使用统计（友盟+ / Umeng+）
**目的:** 了解哪些功能在用、哪些没用，决定下一版做什么。
**包含:**
- 你打开了哪些页面（例如 B3「检查」屏）
- 你点了什么按钮（例如「先不买」「买了」）
- 设备的型号、操作系统版本、屏幕分辨率（用于排查兼容问题）
- 一个匿名设备 ID（不绑定你的身份）

**不包含（永远不会发送）:**
- 你的具体消费金额
- 你的商品名称
- 你的目标内容
- 你的收入或固定开支

### 2. 崩溃报告（Sentry）
**目的:** 当 app 出错崩溃时，把出错位置发给我们，方便修复。
**包含:**
- 出错的代码位置（堆栈信息）
- 设备型号和操作系统版本
- 出错时 app 的当前状态（页面名、操作步骤）

**不包含:**
- 你的任何财务数据
- 你的身份信息

## 我们永远不会收集

不论你是否同意上面的两项，我们绝不会收集：

- 你的姓名、手机号、邮箱、微信、支付宝账户
- 你的通讯录、相册、定位、麦克风、摄像头数据
- 你的消费明细、收入金额、目标内容（这些只在你设备本地的 SQLite 数据库里）
- 你的浏览历史、其他 app 的使用情况

## 数据存放在哪里

- **你的财务数据**: 仅在你的手机上（本地 SQLite 数据库 `prespend.db`）。我们没有服务器，没有云端备份，没有同步。如果你卸载 app 或换手机，这些数据就没了——我们也找不回来。
- **匿名使用统计**: 由友盟+（友盟同欣信息科技（北京）有限公司，阿里巴巴旗下）存放在他们的中国境内服务器。
- **崩溃报告**: 由 Sentry（Functional Software, Inc.，美国）存放在他们的服务器。

## 你的权利

根据《个人信息保护法》（PIPL），你有权：

1. **随时撤回同意**: 进入 app「设置 → 隐私」可以单独关闭匿名使用统计或崩溃报告。（V1 暂未提供，V2 即将上线；目前如需撤回，请卸载 app；本地数据不会被发送，停止收集即时生效。）
2. **删除你的数据**: 因为我们没有云端，所以删除即卸载——卸载 app 等于完全清除。
3. **查询/复制你的数据**: 因为数据本地存放，你可以直接通过手机的备份功能（iCloud / Google Drive / 本地）保留。
4. **联系我们**: 任何关于隐私的问题或投诉，发邮件到 `privacy@prespend.app`（如该邮箱尚未配置，请通过 app 内「设置 → 反馈」提交，我们会在 7 个工作日内回复）。

## 14 岁以下用户

花前记账不面向 14 岁以下用户。如果我们发现某账户来自 14 岁以下用户，会立即停止数据收集。

## 第三方 SDK 列表

V1 集成的第三方 SDK 仅以下两项，且均需你的明确同意才会启动：

| SDK | 用途 | 隐私政策链接 |
|---|---|---|
| 友盟+ (Umeng+) | 匿名使用统计 | https://www.umeng.com/page/policy |
| Sentry | 崩溃报告 | https://sentry.io/privacy/ |

我们不集成广告 SDK、推送 SDK（V1 仅使用本地通知）、社交分享 SDK、支付 SDK、地图 SDK 或任何位置类 SDK。

## 政策变更

任何对本政策的变更，会在 app 内置通知（不通过短信/邮件，因为我们没有你的联系方式）并在本页顶部更新「最后更新」日期。重大变更（例如新增数据收集类型）会在你下次启动 app 时重新弹出同意对话框，你可以重新选择。

## 联系方式

- **开发者**: 个人开发者
- **邮箱**: privacy@prespend.app
- **app 内反馈**: 设置 → 反馈

---

## English summary (informational; the Chinese text above is authoritative)

PreSpend stores all your financial data locally on your device. We have no backend, no cloud sync, no accounts. The only data leaving your device is anonymized usage statistics (Umeng+) and crash reports (Sentry) — both opt-in at first launch. No financial amounts, item names, goal contents, or identifying information are ever transmitted. To withdraw consent: uninstall the app (V1) or use Settings → Privacy (V2). Contact: privacy@prespend.app.
