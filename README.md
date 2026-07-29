# 月结账本（MonthLedger）支持

月结账本是一款以月度结算为核心的个人财务记录工具，支持快速记账、账户与信用卡账期、预算结转、月末净资产、标签分组、多币种、借入借出、CSV 导入导出和桌面小组件。

## 获取帮助

如遇到问题或希望提出建议，请发送邮件至：

**Oasis7311.monthledger@gmail.com**

为了更快定位问题，邮件中可以附上：

- iPhone 型号与 iOS 版本
- App 版本号
- 问题发生前的操作步骤
- 不包含敏感财务信息的截图

请不要通过邮件发送真实账目、账户余额、银行卡信息或其他敏感内容。

## 常见问题

### 是否需要注册账号？

不需要。月结账本没有账号系统，也没有订阅。

### 数据保存在哪里？

账本数据保存在设备本地，并通过 App Group 与月结账本桌面小组件共享。开发者不会接收你的账目内容。

### 如何备份或迁移？

可在 App 设置中使用 CSV 导入导出功能。导出的文件由你自行选择保存位置和分享方式。

### 汇率更新会上传账本吗？

不会。启用多个币种后，App 最多每 24 小时自动刷新一次汇率，也可以由你手动刷新。刷新时只会向 ExchangeRate-API Open Access 服务发送本位币代码，不会上传目标币种列表、交易、余额、标签、备注或其他账本内容。

在线值每日更新，仅用于账本估算，不代表银行成交或结算价格；App 中仍可手动覆盖汇率。汇率来源：[Rates By Exchange Rate API](https://www.exchangerate-api.com)。

## 隐私政策

请查看 [月结账本隐私政策](PRIVACY.md)。

---

## MonthLedger Support

MonthLedger is a local-first personal finance app focused on monthly closing, budgets, accounts, net-worth snapshots, tags, multi-currency records, imports/exports, and widgets.

After multiple currencies are enabled, online reference rates refresh no more than once every 24 hours and can also be refreshed manually. They are used only for ledger estimates, not as bank transaction or settlement rates, and remain manually editable in the app. Source: [Rates By Exchange Rate API](https://www.exchangerate-api.com).

For help or feedback, email **Oasis7311.monthledger@gmail.com**. Please do not include real financial records, account balances, bank details, or other sensitive information.

Read the [Privacy Policy](PRIVACY.md).
