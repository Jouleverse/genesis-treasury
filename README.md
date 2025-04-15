# genesis-treasury

All about Jouleverse GT(Genesis Treasury) and tokenomics.

关于Jouleverse的GT(创世金库)及其通证经济。

## GT多签 & 时间锁

- GT multisig: 0x3B717119878E2db1AA7df46F5AdcF9766A01706F
- timelock core: 0x628beb88dD440A8c5e4cC89Ab33a041f521e4323
- timelock eco: 0xbb6b53Fadf85B73258cb6A54F1343Ac4D5F99773

管理方法：多签合约，社区共管 + 时间锁

里程碑：
- 2025.4.15：全部Joule完成迁移，从GT迁移到两个时间锁合约中，严格按照Joulenomics（焦耳经济学）释放/解锁，彻底杜绝了多签人的干预可能性

多签变更历史：
起止日期 | m/n | 多签人
-|-|-
2022.10-2023.9 | 2/3 | 教链，一痕，Jacky
2023.10-2024.6 | 3/5 | 教链，一痕，Jacky，Koant，谢勇
2024.6- | 3/5 | 教链，Jacky，Koant，谢勇，Jeff

**多签人** | **多签人权限地址**
-|-
教链 | 0xB313C0de794F530Ab08e0a71C31Ee022e875Fe76
Jacky | 0xA2029982158382E5f60E7df51593a6309Bc9Ba1c
Koant | 0x3bD7F1E5C4b059a85a7b2F0a91934fB6A28e7104
谢勇 | 0xb23823CBE3962aed787fAfbc2a5B907c0F4d1489
Jeff | 0x5d1CA5f6506272A81BEdB830a47981ad73eE21BB

## Tokenomics

1. 创世总量1000亿J(Joule)。
2. 线性释放，每月固定解锁6000万J（一年12个月即7.2亿J/年）。简单计算可知，全部释放完成大约需要138.88年（超过两个康波周期）。释放速度由无人干预的时间锁合约控制。
3. 每月释放量按照二八原则拆分为两个部分：核心激励（core incentives）20%，即每月1200万J；生态发展（ecosystem development）80%，即每月4800万J。目标是以20%的核心工作，撬动80%的生态发展。
4. 20%的核心激励部分采取（由core自主决定）强制空投（类似BTC的“区块奖励”）的刚性支出方式（逐月），用于激励核心项目（core projects），实行PoWh按劳分配原则（类似BTC的按算力比例分配区块奖励）。有关PoWh，参考[workspace repo](https://github.com/Jouleverse/workspace)。
5. 80%的生态发展部分采取由社区共同投票治理使用的按需支出方式，用于资助生态项目（ecosystem projects），实行具备投票权的社区成员链上投票表决的集体决策原则。具体参考ecofund的有关内容（建设中）——参见[首支生态基金ecofund1](https://github.com/Jouleverse/ecofund1)。未支出的资金则继续保留在生态时间锁里。

## Financial Records

Joule释放情况（202210-现在）：

 x | 月数 | 已释放(J) | 已支出/流通(J) | 已释放且未支出/流通(J)
-|-|-|-|-
核心激励 | n | [1] | [3] | -
生态发展 | n | [2] | [4] | -
总计 | n | 当前宇宙总能量[5] | 流动中的能量[6] | 暗能量[7]

- [1] 与链上timelock core合约released之数值相等（链上算法是后置释放，也就是进入7月份才释放6月份的预算）
- [2] 与链上timelock eco合约released之数值相等（算法同上）
- [3] 应与链上timelock core合约used之数值相等
- [4] 应与链上timelock eco合约used之数值相等
- [5][6][7] 请查看区块链浏览器中的实时数值

对账记录：

GT创世金库多签：
时间 | 事务序号 | 目的 | 转账方向 | 增减数量(J) | 变动后余额(J) | 链上对账一致(Y/N) | 备注
-|-|-|-|-|-|-|-
2022.10.1 | x | 创世 | 0x0 -> 一痕(代) | 100,000,000,000 | - | - | 划出150 J（每人50 J）作为测试用gas
2022.10.10 | x |多签设立 | 一痕(代) -> 多签 | +99,999,999,850 | 99,999,999,850 | - | -
2023.6.28 | 8 | 测试wJ | 多签 -> 教链(代) | -10 | 99,999,999,840 | - | 10人参与测试，每人发1 WJ
2023.7.1 | 9 | 核心激励预算202210-202302 | 多签 -> 教链(代) | -60,000,000 | 99,939,999,840 | - | -
2023.8.1 | 10 | 核心激励预算202303-202306 | 多签 -> 教链(代) | -48,000,000 | 99,891,999,840 | - | -
2023.8.22 | 11 | 核心激励预算202307 | 多签 -> 教链(代) | -12,000,000 | 99,879,999,840 | - | -
2023.10.8 | x | 归还 | 一痕 -> 多签 | +50 | 99,879,999,890 | - | 测试gas 50J
2023.10.11 | 15 | 核心激励预算202308 | 多签 -> 教链(代) | -12,000,000 | 99,867,999,890 | Y | 99867999889.99974
2023.12.4 | 16 | 核心激励预算202309 | 多签 -> 教链(代) | -12,000,000 | 99,855,999,890 | - |
2023.12.7 | 17 | 核心激励预算202310 | 多签 -> 教链(代) | -12,000,000 | 99,843,999,890 | Y | 99843999889.99974
2024.1.17 | 18+19 | 核心激励预算202311+12 | 多签 -> 教链(代) | -24,000,000 | 99,819,999,890 | Y | 99819999889.99974
2024.1.30 | x | 补零 | 教链 -> 多签 | +0.00026 | 99,819,999,890 | Y | 99819999890
2024.2.15 | 20 | 核心激励预算202401 | 多签 -> 教链(代) | -12,000,000 | 99,807,999,890 | Y | -
2024.3.29 | 21 | 核心激励预算202402 | 多签 -> 教链(代) | -12,000,000 | 99,795,999,890 | Y | -
2024.4.25 | 22 | [JIP-5第一次拨款](https://github.com/Jouleverse/open-meetings/blob/main/governance0/JIP-5.md) | 多签 -> ecofund1 | -72,000,000 | 99,723,999,890 | Y | -
2024.5.27 | 23 | 核心激励预算202403 | 多签 -> Koant(代) | -12,000,000 | 99,711,999,890 | Y | -
2024.6.4  | 24 | 核心激励预算202404 | 多签 -> 教链(代) | -12,000,000 | 99,699,999,890 | Y | -
2024.6.20  | GT:30 | 核心激励预算202405-07 | 多签 -> timelock core | -36,000,000 | 99,663,999,890 | Y | 试运行timelock core
2024.7.26 | x | 归还 | 教链 -> GT | +110 | 99,664,000,000 | Y | 归还2022.10.1测试50J；代Jacky归还2022.10.1测试50J；代2023.6.28参与测试10人归还10J；总共归还110J
2024.11.19 | GT:44 | 核心激励剩余全部预算锁定 | 多签 -> timelock core | -19,736,000,000 | 79,928,000,000 | Y | [迁移计划](https://github.com/Jouleverse/governance/blob/master/README.md)
2025.4.15 | GT:53 | 生态发展剩余全部预算锁定 | 多签 -> timelock eco | -79,928,000,000 | 0 | Y | [迁移计划](https://github.com/Jouleverse/governance/blob/master/README.md)

timelock核心：
时间 | 事务序号 | 目的 | 转账方向 | 增减数量(J) | 变动后余额(J) | 链上对账一致(Y/N) | 备注
-|-|-|-|-|-|-|-
2024.6.20 | GT:30 | GT划拨试运行3个月(202405-07)预算 | GT -> timelock core | +36,000,000 | 36,000,000 | Y | -
2024.7.16 | GT:32,33 | 核心激励预算202405 | timelock core -> Koant(代) | -12,000,000 | 24,000,000 | Y | -
2024.8.15 | GT:38,39 | 核心激励预算202406 | timelock core -> 谢勇(代) | -12,000,000 | 12,000,000 | Y | -
2024.10.14 | GT:40,41 | 核心激励预算202407 | timelock core -> Jeff(代) | -12,000,000 | 0 | Y | -
2024.11.19 | GT:44 | 核心激励剩余全部预算锁定 | GT -> timelock core | +19,736,000,000 | 19,736,000,000 | Y | [迁移计划](https://github.com/Jouleverse/governance/blob/master/README.md)
2024.11.23 | GT:47,48 | 核心激励预算202408 | timelock core -> Koant(代) | -12,000,000 | 19,724,000,000 | - | -
2025.3.26 | GT:50,51 | 核心激励预算202409-12 | timelock core -> Koant(代) | -48,000,000 | 19,676,000,000 | Y | -

timelock生态：
时间 | 事务序号 | 目的 | 转账方向 | 增减数量(J) | 变动后余额(J) | 链上对账一致(Y/N) | 备注
-|-|-|-|-|-|-|-
2025.4.15 | GT:53 | 生态发展剩余全部预算锁定 | GT -> timelock eco | +79,928,000,000 | 79,928,000,000 | Y | [迁移计划](https://github.com/Jouleverse/governance/blob/master/README.md)

