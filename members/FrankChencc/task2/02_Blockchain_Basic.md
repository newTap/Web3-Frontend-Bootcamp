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
- [x] 要给我黒米
- [x] 给我下套呢

## [多选题] 以下哪些是以太坊的二层扩容方案？

- [ ] Lightning Network（闪电网络）
- [x] Optimsitic Rollup
- [x] Zk Rollup

## [简答题] 简述区块链的网络结构

```
一个链由运行在全世界的节点组成，每个节点都有自己的区块链副本，每个节点都运行着相同的代码。
节点之间可以互相链接，通过共识算法验证数据正确性，不正确的数据不会被承认。
用户与区块链网络交互，将以节点作为入口。
而节点可以简单理解成，一堆运行了RPC 服务的服务器。

```

## [简答题] 智能合约是什么，有何作用？

```
智能合约就是部署在区块链上的后端程序，开发者可以自己编写，部署智能合约，他可以被用户发起交易来调用。
智能合约类似于账本，他的作用是记录交易，并执行交易。我们可以通过智能合约，将数据保存在链上，同时也能调用智能合约读取链上数据。

```

## [简答题] 怎么理解大家常说的 `EVM` 这个词汇？

```
运行以太坊的智能合约的虚拟机就是 EVM。如上面智能合约的描述，智能是部署在连上的一个后端程序，而运行这个后端程序的环境需要一个虚拟的操作系统，这个虚拟的操作系统就是 EVM。
```

## [分析题] 你对去中心化的理解

```
去中心化就是一种云上数据存储、处理传输的方式，与 CDN 通常将数据存储到单一节点不同，他将数据存储在多个节点上，并使用共识算法来保证数据的一致性和可信赖的。这样做的解决了一个信任问题，所有操作，都需通过共识过程同步到所有节点中，只要不同时修改所有节点的数据，就能确保数据不会被篡改。

```

## [分析题] 比较区块链与传统数据库，你的看法？

```
区块链最重要的就是去中心化，传统数据库就是一个有中心的，即使是高可用也是有一个主从关系的。
优点：解决了一个信任问题，所有操作，都需通过共识过程同步到所有节点中，只要不同时修改所有节点的数据，就能确保数据不会被篡改。
缺点：因为同步机制的存在，当节点过多，会产生拥堵，不管是读数据还是写数据都比传统数据库慢。

```

## 操作题

安装一个 WEB3 钱包，创建账户后与 [openbuild.xyz](https://openbuild.xyz/profile) 进行绑定，截图后文件命名为 `./bind-wallet.jpg`.