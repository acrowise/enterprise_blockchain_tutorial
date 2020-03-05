## 第三章 Hyperledger Fabric架构详解

在[区块链技术选型](./chapter2_05%20selection_of_technology.md)章节，我们讨论了超级账本与比特币、以太坊的差别，超级账本中的Fabric项目在效率和隐私保护都远远超过了公链的设计。

其实要做到这点也不难，联盟链的做法是限制成员加入——必须是经过认证通过的节点才能加入。由于节点需要认证，因此Hyperledger Fabric在设计上弱化了恶意攻击，在提高效率的同时还可以有效保护隐私，使得联盟链在企业实施变成可能。

Hyperledger Fabric的最大的优势是支持共识机制、权限管理、密钥、账本机制等模块的可插拔。Fabric早期被很多人诟病，效率低下，有中心化嫌疑，现在的说法是不符合国产密码算法要求。提出这些问题的人一方面是没有产品研发能力，另一方面是没有用发展的眼光看待新生事物。

现在业内很多知名区块链公司包括趣链、纸贵科技等都是基于Fabric进行的产品研发，研发的方向主要是集中在共识机制、密码算法等方面。Fabric目前已经提供了1.4稳定版本，这个版本在很多方面都有了大的提升。

这个章节我们深入学习下Hyperledger Fabric的设计架构。

