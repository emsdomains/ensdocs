# 漏洞奖金计划

ENS 漏洞奖金计划用于奖励那些在本计划涉及的 ENS 智能合约中发现漏洞的人。

### 奖励规则

* 其他用户已经提交的问题或 ENS 团队已经知道的问题没有资格获得奖励。
* 包括主网或任何公共测试网络上的漏洞在内，公开披露漏洞会丧失获得奖励的资格。
* 由 ENS 项目直接或间接支付的 ENS 团队、员工等人都没有获得奖励的资格。
* 只有在下列智能合约中发现漏洞才有资格获得奖励，网站和其他基础设施不在悬赏计划的覆盖范围之内。
* ENS 赏金计划在决定奖励时会考虑多种因素，资格、分数以及与奖项相关的所有条款的确定均由ENS团队自行决定。

奖金额度与漏洞严重性相关，漏洞严重性根据 Impact and Likelihood 的 OWASP 风险评级模型计算：

奖金额度遵循以下规则，但最终由 ENS 团队自行决定

* **极危**: 最高 $250,000 USD
* **高危**: 最高 $150,000 USD
* **中危**: 最高 $100,000 USD
* **低危**: 最高 $20,000 USD
* **提醒**: 最高 $5,000 USD

ENS 团队保留在未来任何时间调整奖金额度的权利。

对于我们 GitHub 仓库中合约与以太坊上部署合约存在差异的地方，由于自上次部署以来发生了变化，以下规则适用:

1. 如果在以太坊上部署的合约中存在漏洞，则应支付全额奖金。
2. 如果只有 GitHub 上的版本存在漏洞，ENS 团队会以代码的状态作为依据来决定一个合适赏金比例（从未打算部署的代码适用比例为 0%，最终版本的代码适用比例为 100%）。

当 ENS 团队对漏洞评分时，除了严重程度，还会考虑其他因素，包括（但不限于）：

* 描述质量。清晰、规范的提交内容会得到更高的奖励。
* 重现性质量。请测试代码、脚本和详细说明一起提交。我们越容易复制和验证弱点，奖金就越高。
* 修复质量（如果包含修复方法的话）。如果提交的内容清楚地描述了如何解决问题，就会获得更高的奖励。

### 涉及合约

奖金计划涉及以下合约：

* [ensdomains/ens-contracts](https://github.com/ensdomains/ens-contracts) 中的所有非测试合约。
* [ensdomains/name-wrapper](https://github.com/ensdomains/name-wrapper)

### 重要法律信息

漏洞奖金计划是一个自由决定的奖励计划，旨在鼓励和奖励那些帮助改进平台的人。这不是竞赛，我们可能在任何时间取消该计划，且奖项由 ENS 团队全权决定。此外，我们不能向在制裁名单上的个人或在制裁名单上的国家的个人颁发奖励。您要对所有的税收负责。所有裁决均受适用法律约束。提供任何补丁必须要遵循相应代码仓库的许可协议。最后，您的测试不能违反任何法律或泄露任何不属于您的数据。

### 漏洞提交方式

漏洞可以通过电子邮件提交至 bugs@ens.domains，或通过 Keybase 提交给 @arachnid。
