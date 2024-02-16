# genesis-treasury

All about Jouleverse GT(Genesis Treasury) and tokenomics.

关于Jouleverse的GT(创世金库)及其通证经济。

## GT多签

0x3B717119878E2db1AA7df46F5AdcF9766A01706F

管理方法：多签合约，社区共管

多签变更历史：
起止日期 | m/n | 多签人
-|-|-
2022.10-2023.9 | 2/3 | 教链，一痕，Jacky
2023.10-至今 | 3/5 | 教链，一痕，Jacky，Koant，谢勇

## Tokenomics

1. 创世总量1000亿J(Joule)。
2. 线性释放，每月固定解锁6000万J（一年12个月即7.2亿J/年）。简单计算可知，全部释放完成大约需要138.88年（超过两个康波周期）。
3. 每月释放量按照二八原则拆分为两个部分：核心激励（core incentives）20%，即每月1200万J；生态基金（eco-fund）80%，即每月4800万J。目标是以20%的核心工作，撬动80%的生态发展。
4. 20%的核心激励部分采取强制空投（类似BTC的“区块奖励”）的刚性支出方式（逐月），用于激励核心项目（core projects），实行PoWh按劳分配原则（类似BTC的按算力比例分配区块奖励）。有关PoWh，参考[workspace repo](https://github.com/Jouleverse/workspace)。
5. 80%的生态基金部分采取治理使用的灵活支出方式，用于资助生态项目（ecosystem projects），实行具备投票权的社区成员链上投票表决的集体决策原则。具体参考ecofund的有关内容（建设中）。未支出的资金则继续保留在生态基金里。

## Financial Records

释放情况（202210-202312）：

 x | 月数 | 理论释放量(J) | 实际支出(J)
-|-|-|-
核心激励 | 15 | 1.80亿 | 约1.76亿
生态基金 | 15 | 7.20亿 | 0
总计 | 15 | 9亿 | 约1.76亿

对账记录：

时间 | 目的 | 转账方向 | 增减数量(J) | 变动后余额(J) | 链上对账一致(Y/N) | 备注
-|-|-|-|-|-|-
2022.10.1 | 创世 | 0x0 -> 一痕(代) | 100,000,000,000 | - | - | 划出150 J（每人50 J）作为测试用gas
2022.10.10 | 多签设立 | 一痕(代) -> 多签 | +99,999,999,850 | 99,999,999,850 | - | -
2023.6.28 | 测试wJ | 多签 -> 教链(代) | -10 | 99,999,999,840 | - | 10人参与测试，每人发1 WJ
2023.7.1 | 核心激励预算202210-202302 | 多签 -> 教链(代) | -60,000,000 | 99,939,999,840 | - | -
2023.8.1 | 核心激励预算202303-202306 | 多签 -> 教链(代) | -48,000,000 | 99,891,999,840 | - | -
2023.8.22 | 核心激励预算202307 | 多签 -> 教链(代) | -12,000,000 | 99,879,999,840 | - | -
2023.10.8 | 归还 | 一痕 -> 多签 | +50 | 99,879,999,890 | - | 测试gas 50J
2023.10.11 | 核心激励预算202308 | 多签 -> 教链(代) | -12,000,000 | 99,867,999,890 | Y | 99867999889.99974
2023.12.4 | 核心激励预算202309 | 多签 -> 教链(代) | -12,000,000 | 99,855,999,890 | - |
2023.12.7 | 核心激励预算202310 | 多签 -> 教链(代) | -12,000,000 | 99,843,999,890 | Y | 99843999889.99974
2024.1.17 | 核心激励预算202311+12 | 多签 -> 教链(代) | -24,000,000 | 99,819,999,890 | Y | 99819999889.99974
2024.1.30 | 补零 | 教链 -> 多签 | +0.00026 | 99,819,999,890 | Y | 99819999890
2024.2.15 | 核心激励预算202401 | 多签 -> 教链(代) | -12,000,000 | 99,807,999,890 | Y | -
