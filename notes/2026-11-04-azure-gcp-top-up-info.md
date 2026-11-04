---
title: Azure 与 Google Cloud 充值前，要先跟顾问对齐哪些信息
description: Azure 订阅和 Google Cloud 结算账户的结构比阿里云、腾讯云复杂，充值为什么要先找顾问确认，以及事先准备好哪些信息能少来回沟通。
tags: [Azure, Google Cloud, 充值, 顾问办理]
---

# Azure 与 Google Cloud 充值前，要先跟顾问对齐哪些信息

> **一句话结论：** Azure 和 Google Cloud 的「钱」挂在订阅或结算账户上，而不是挂在登录账号上。先把这层关系说清楚，充值才不会充错地方。

阿里云国际、腾讯云国际和 AWS 充值时，填一个账号标识就够了。Azure 和 Google Cloud 不一样，所以在云大哥这两家都是 **顾问办理**，不走网页自助。

## 为什么不能只填一个账号？

| 平台 | 登录用的是 | 费用挂在 | 一个登录身份可以对应 |
| :--- | :--- | :--- | :--- |
| Microsoft Azure | Entra ID（原 Azure AD）用户 | 订阅（Subscription） | 多个租户、多个订阅 |
| Google Cloud | Google 账号 | 结算账户（Billing Account） | 多个结算账户、多个项目 |

也就是说，同一个人登录进去，可能看到好几个订阅或结算账户。只说「给我的账号充值」，顾问没法确定充到哪里。

## 找顾问之前，先准备这些

**Azure：**

- [ ] 订阅名称和订阅 ID（门户 → 订阅）
- [ ] 订阅所属的租户（目录）名称
- [ ] 订阅当前状态是否正常（已禁用的订阅要先说明情况）
- [ ] 这次计划充值的金额

**Google Cloud：**

- [ ] 结算账户名称和结算账户 ID（Billing → Account management）
- [ ] 挂在这个结算账户下、需要继续运行的项目 ID
- [ ] 结算账户当前状态是否正常
- [ ] 这次计划充值的金额

截图时遮住无关信息即可，**不要发送密码或密钥**。

## 小提醒

- 只有通过云大哥开通的订阅或结算账户才能办理充值。
- 用 Azure OpenAI 或 Vertex AI 的，配额和区域也会影响用量预估，可以对照 [Azure OpenAI 与 Vertex AI 使用前检查清单](https://www.clouddage.com/resources/azure-openai-vertex-ai-checklist)。
- 报价方式见 [报价方式与办理流程](https://www.clouddage.com/pricing)。

## 怎么联系

准备好信息后，通过 [联系页面](https://www.clouddage.com/contact) 找顾问，注明平台和需求。平台介绍在这里：[Microsoft Azure](https://www.clouddage.com/platforms/azure) · [Google Cloud](https://www.clouddage.com/platforms/google-cloud)。

---

上一篇：[AWS 什么时候扣钱](2026-11-04-aws-billing-cycle.md) · [← 回到笔记列表](../) · 下一篇：无
