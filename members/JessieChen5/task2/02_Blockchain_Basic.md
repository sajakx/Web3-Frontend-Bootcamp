# Task2 Blockchain Basic

本任务分为简答题、分析题和选择题，以此为模板，在下方填写你的答案即可。

选择题，请在你选中的项目中，将 `[ ]` 改为 `[x]` 即可

## [单选题] 如果你莫名奇妙收到了一个 NFT，那么

- [ ] 天上掉米，我应该马上点开他的链接
- [x] 这可能是在对我进行诈骗！

## [单选题] 群里大哥给我发的网站，说能赚大米，我应该

- [ ] 赶紧冲啊，待会米被人抢了
- [x] 谨慎判断，不在不信任的网站链接钱包

## [单选题] 下列说法正确的是

- [x] 一个私钥对应一个地址
- [ ] 一个私钥对应多个地址
- [ ] 多个私钥对应一个地址
- [ ] 多个私钥对应多个地址

## [单选题] 下列哪个是以太坊虚拟机的简称

- [ ] CLR
- [x] EVM
- [ ] JVM

## [单选题] 以下哪个是以太坊上正确的地址格式？

- [ ] 1A4BHoT2sXFuHsyL6bnTcD1m6AP9C5uyT1
- [ ] TEEuMMSc6zPJD36gfjBAR2GmqT6Tu1Rcut
- [ ] 0x997fd71a4cf5d214009619808176b947aec122890a7fcee02e78e329596c94ba
- [x] 0xf39Fd6e51aad88F6F4ce6aB8827279cffFb92266

## [多选题] 有一天某个大哥说要按市场价的 80% 出油给你，有可能

- [x] 他在洗米
- [ ] 他良心发现
- [ ] 要给我黒米
- [ ] 给我下套呢

## [多选题] 以下哪些是以太坊的二层扩容方案？

- [ ] Lightning Network（闪电网络）
- [x] Optimsitic Rollup
- [ ] Zk Rollup

## [简答题] 简述区块链的网络结构

```
组成：由账户、节点、区块、分布式网络、公钥体制、共识机制、智能合约等技术；
基本流程：用户通过钱包账户，与节点进行交易，并在公钥体制，共识机制的作用下，在分布式网络中生成，同步区块，生成智能合约等功能。
```

## [简答题] 智能合约是什么，有何作用？

```
定义：存储在区块链上的程序，满足预先确定的条件时可以运行（人为触发或自动运行）。智能合约包括了代码，也包括了与其他合约进行交互，存储，发送代币等操作。
作用：使得交易透明、不可逆转、消除中介并减少时间浪费。
```

## [简答题] 怎么理解大家常说的 `EVM` 这个词汇？

```
EVN 是以太坊虚拟机的缩写，是运行在以太坊网络中的操作系统。采用去中心化方式，提供一个可构建，执行代码等的环境。
```

## [分析题] 你对去中心化的理解

```
定义：去中心化是指一个系统或网络由多方共同维护，每一方都是平等的，没有任何中心化的系统控制者。
意义：没有一个组织或者一个人能对全链路的信息真实性和完整性负责。
```

## [分析题] 比较区块链与传统数据库，你的看法？

```
区块链与传统数据库的区别：
1. 存储方式：区块链是分布式数据库，存储在网络中，每个节点都存储一份完整的数据，而传统数据库是集中式数据库，存储在一台服务器上。
2. 安全性：区块链的安全性依赖于共识机制，一旦数据被篡改，将无法被追溯。传统数据库的安全性依赖于密码学和访问控制。
3. 性能：区块链的性能受限于网络的带宽，每秒处理的交易数量有限。传统数据库的性能受限于硬件的性能。
```

## 操作题

安装一个 WEB3 钱包，创建账户后与 [openbuild.xyz](https://openbuild.xyz/profile) 进行绑定，截图后文件命名为 `./bind-wallet.jpg`.
