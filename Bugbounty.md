# Bug Bounty program

### 威胁等级奖励
智能合约漏洞奖励基于 [免疫漏洞严重程度分级系统](https://immunefi.com/severity-system/)，根据漏洞影响程度进行分配。这是一个简化的 5 级量表，分别针对网站/应用程序和智能合约/区块链进行了单独的量表，涵盖了从利用的后果到成功利用所需的特权的所有内容。

为了确定最终奖励金额，考虑对可用性、完整性和/或资金损失产生有意义影响的可能性。支付金额的最终决定将由 Fort DAO 自行决定。

付款由 Fort DAO 直接处理，并以DCU计价。

#### 智能合约和区块链
|等级|支付|
|---|---|
|危机|10000 - 50000 DCU|
|高|5000 - 10000 DCU|
|中|1000 - 5000 DCU|
|低|100 - 1000 DCU|

### 优先漏洞
我们对接收和奖励以下类型的漏洞特别感兴趣：

- 重入
- 逻辑错误
- 未考虑 Solidity/EVM 细节
    - 包括整数上溢/下溢
    - 包括未处理的异常
- 信任信任/依赖漏洞
    - 包括可组合性漏洞
- Oracle 故障/操纵
- 新型治理攻击
- 经济/金融攻击
    - 包括闪贷攻击
- 拥塞和可扩展性
    - 包括gas超过上限
    - 包括阻塞区块
- 密码学问题

### 超出范围和规则

此漏洞赏金计划的奖励不包括以下漏洞：

- 报告者自己已经利用攻击，导致损害
- 需要访问泄露的密钥/凭证的攻击
- 需要访问特权地址的攻击（治理）
- 第三方预言机提供的数据不正确
    - 不排除预言机操纵/闪电贷攻击
- 基本经济治理攻击（例如 51% 攻击）
- 缺乏流动性
- 女巫攻击

#### 规则

本次漏洞赏金规则如下：

- 错误尚未公开披露。
- 先前由其他贡献者提交或 Fort DAO已知的漏洞不符合奖励资格。
- 赏金支出的大小取决于对漏洞利用严重程度的评估。请参阅下面的奖励部分了解更多详情。
- 错误必须是可重现的，以便我们验证漏洞。
- 奖励和漏洞的有效性由 Fort DAO 确定，任何支出均由他们自行决定。
- 漏洞赏金计划的条款和条件可以随时由 Fort 自行决定更改。
- 任何有效错误的详细信息都可以与 Fort 生态系统中使用的补充协议共享，以促进生态系统的凝聚力和安全性。

---

### Rewards by Threat Level
Rewards for Smart Contract vulnerabilities are distributed according to the impact of the vulnerability based on the [Immunefi Vulnerability Severity Classification System](https://immunefi.com/severity-system/). This is a simplified 4-level scale, with separate scales for websites/apps and smart contracts/blockchains, encompassing everything from consequence of exploitation to privilege required to likelihood of a successful exploit.

To determine the final reward amount, the likelihood to have a meaningful impact on availability, integrity, and/or loss of funds is considered. The final decision on the payout amount will be determined by the Fort DAO at its discretion.

Payouts are handled by the Fort DAO directly and are denominated in DCU. 

#### Smart Contracts and Blockchain
|Level|Payout|
|---|---|
|Critical|10000 - 50000 DCU|
|High|5000 - 10000 DCU|
|Medium|1000 - 5000 DCU|
|Low|100 - 1000 DCU|

### Prioritized Vulnerabilities
We are especially interested in receiving and rewarding vulnerabilities of the following types:

- Re-entrancy
- Logic errors
- Solidity/EVM details not considered
    - including integer over-/under-flow
    - including unhandled exceptions
- Trusting trust/dependency vulnerabilities
    - including composability vulnerabilities
- Oracle failure/manipulation
- Novel governance attacks
- Economic/financial attacks
    - including flash loan attacks
- Congestion and scalability
    - including running out of gas
    - including block stuffing
- Cryptography problems

### Out of Scope & Rules

The following vulnerabilities are excluded from the rewards for this bug bounty program:

- Attacks that the reporter has already exploited themselves, leading to damage
- Attacks requiring access to leaked keys/credentials
- Attacks requiring access to privileged addresses (governance)
- Incorrect data supplied by third party oracles
    - Not to exclude oracle manipulation/flash loan attacks
- Basic economic governance attacks (e.g. 51% attack)
- Lack of liquidity
- Sybil attacks

#### Rules

The rules of this bug bounty are as follows:

- Bug has not been publicly disclosed.
- Vulnerabilities that have been previously submitted by another contributor or already known by the Fort DAO are not eligible for rewards.
- The size of the bounty payout depends on the assessment of the severity of the exploit. Please refer to the rewards section below for additional details.
- Bugs must be reproducible in order for us to verify the vulnerability.
- Rewards and the validity of bugs are determined by the Fort DAO and any payouts are made at their sole discretion.
- Terms and conditions of the Bug Bounty program can be changed at any time at the discretion of Fort.
- Details of any valid bugs may be shared with complementary protocols utilized in the Fort ecosystem in order to promote ecosystem cohesion and safety.

