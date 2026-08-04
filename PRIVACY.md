# 月结账本隐私政策

生效日期：2026 年 7 月 30 日

月结账本（MonthLedger）尊重并保护你的隐私。本政策说明 App 如何处理数据。

## 1. 数据收集范围

月结账本无需注册或登录。开发者不会接收、存储或出售你的姓名、联系方式、位置、使用行为、交易记录、账户余额、标签、备注或其他账本内容，也不会使用这些数据进行广告、分析或跨 App 跟踪。

仅当你启用在线汇率更新时，第三方汇率服务可能为了提供汇率、限制滥用和保障服务安全而收集 IP 地址、请求时间和本位币代码等必要网络信息。这些信息可能与设备或网络身份关联，但不会用于广告或跨 App 跟踪。具体范围见第 3 节。

## 2. 本地数据存储

账本数据保存在你的设备本地。主 App 会通过 Apple 的 App Group 机制与月结账本桌面小组件共享完成小组件展示与快捷记账所需的数据。此共享只发生在你设备上的月结账本 App 与其小组件之间，开发者无法访问这些内容。

删除 App 会删除由系统管理的本地 App 数据。通过 CSV 导出的文件由你自行选择保存位置和分享对象，开发者无法控制或访问这些文件。

## 3. 汇率服务

当你启用多个币种后，App 最多每 24 小时自动刷新一次汇率，你也可以手动请求更新。刷新时，App 会通过 HTTPS 向免密公开的 ExchangeRate-API Open Access 服务发送你选择的本位币代码。服务返回每日参考汇率，App 仅将这些数值用于账本估算；它们不代表银行成交、交易执行、清算或结算价格。汇率来源：[Rates By Exchange Rate API](https://www.exchangerate-api.com)。

请求不会包含交易记录、余额、账户名称、标签、备注、联系人信息、设备标识符或其他账本内容，也不会发送目标币种列表。与任何联网请求一样，汇率服务及其网络基础设施服务商可能为了传输、安全和防止滥用而处理 IP 地址、请求时间、本位币代码等必要的网络信息；相关处理适用服务商自身的政策。

## 4. 权限与第三方服务

月结账本不接入广告 SDK、第三方分析 SDK、社交登录或银行账户连接。App 不会请求通讯录、精确位置、麦克风、相机或健康数据权限。

## 5. 儿童隐私

月结账本不面向儿童提供专门服务，开发者无法访问保存在设备本地的账本内容。启用在线汇率时产生的必要网络信息按照第 3 节所述由第三方汇率服务处理。

## 6. 政策更新

如果 App 的数据处理方式发生变化，本政策会更新生效日期，并在此页面发布新版本。

## 7. 联系方式

如对本隐私政策有疑问，请发送邮件至：**Oasis7311.monthledger@gmail.com**

---

# MonthLedger Privacy Policy

Effective date: July 30, 2026

MonthLedger does not require an account. The developer does not receive, store, sell, or use your financial records, account balances, notes, contacts, location, or usage data for advertising, analytics, or tracking. If online exchange-rate updates are enabled, the third-party rate service may collect the IP address, request time, and base-currency code to provide rates, prevent abuse, and secure the service. This information may be linked to a device or network identity, but it is not used for advertising or cross-app tracking.

Ledger data is stored locally on the device. The main app shares only the data needed for widgets and quick entry with its own Widget extension through Apple's App Group container. The developer cannot access this local data.

After the user enables multiple currencies, the app automatically refreshes rates no more than once every 24 hours; the user can also request a manual refresh. Each refresh sends the selected base-currency code over HTTPS to the keyless public ExchangeRate-API Open Access service. The service returns daily reference rates, which the app uses only for ledger estimates; they are not bank transaction, trade execution, clearing, or settlement rates. Source: [Rates By Exchange Rate API](https://www.exchangerate-api.com).

The request does not include target-currency selections, transactions, balances, account names, tags, notes, contact information, device identifiers, or other ledger content. As with any internet request, the exchange-rate service and its network infrastructure providers may process necessary network information such as the IP address, request time, and base-currency code to deliver and secure the service and prevent abuse under their own policies.

MonthLedger does not include advertising SDKs, third-party analytics SDKs, social login, or bank connections. CSV exports are created only at the user's request and are saved or shared to destinations chosen by the user.

For privacy questions, contact **Oasis7311.monthledger@gmail.com**.
