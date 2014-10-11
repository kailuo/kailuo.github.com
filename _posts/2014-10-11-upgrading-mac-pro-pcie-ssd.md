---

title: Mac Pro 2010 升级 - PCIe SSD
layout: post
category: topic

---


关于存储部分，考虑了一段时间后还是决定使用 PCIe SSD 解决方案。Mac Pro 5,1 系列只有 PCIe 2.0 接口，最大带宽 5GT/s（大约 700 MB/s 的实际传输速率上限）比较接近现在的消费级 SSD，另外考虑到我的使用方式，机箱里至少还能空出两个 PCI 插槽。

目前可以选择的品牌厂商，同时出品 SSD 以及接口的好像只有 Plextor 一家，M6e 系列是他们今年的新产品，目前来看口碑很不错（这个接口也完美支持三星 X941 系列）。我还是更喜欢这种搭配，完全不需要担心兼容性。

![images](http://i.v2ex.co/P26kMt4A.jpeg)
[Plextor M6e 256GB](http://www.plextoramericas.com/index.php/pcie-ssd/hhhl/pcie-m6e)

单片 SSD 在 Mac 上面完美流畅启动，我的 256GB 版本测试结果为打文件 550 MB/s 连续写入和 682 MB/s 连续读取。4K 和 256K 的表现也都很不错，对比 SATA 2 接口的 Crucial MT4 性能提升都在两倍以上。

数据之外，目前最明显的使用感受是，系统要比 SATA 2 + MT4 的时候更加流畅，尤其是内存吃紧的时候。而且，这次我尝试用打开了 Trim 支持，一直很好奇但没机会尝试。传说中 Trim 对于需要长时间不间断工作的机器还是很重要的。另外，机箱还有一个插槽可以进行升级，如果两片 M6e 组合 RAID0，理论读写速度应该能超过 1GB/s，算是老机器的极限了。

安装很方便，之后使用 Disk Utility 将系统 Restore 一下就好了，比 Time Machine 更快速。然后现在可以将整个 MT4 划给 iTunes 做存储使用，非常惬意。 

最后要说，其实还有更完美的解决方案，深圳有一些厂商造出了支持拆机 MBP, MBA SSD 的 PCIe 接口，比如 [这一家](http://eshop.sintech.cn/)，售价大约在 40 刀左右，之后再花差不多的价钱淘拆机 SSD 进行组装。不过这种方式实在没有任何体验可谈，即使能有原生的 Trim 支持。