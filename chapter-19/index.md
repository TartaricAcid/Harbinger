## 世界生成与新维度

Minecraft 有一大特色就是它写实的世界生成。虽然这世界生成也时常被人诟病，但不可否认它的确是 Minecraft 成功的关键一环。  
实际上，Minecraft 的世界生成并没有太多的玄学。世界生成的本质是按特定方式放置方块。对于原版 Minecraft 来说，这个过程大致是：先确定生物群系，然后生成地形，接着放置结构，最后填充剩余的特征（生物群系装饰及其他地图特性）。前几个过程中大量利用了噪音，而最后的填充（“populate”）过程则基本上是伪随机数发生器和各种奇奇怪怪的函数的世界。简单来说，地图生成其实是数学的领域。

虽然说一个像样的世界生成的确需要对相关知识有所认知，但如果只是写一些简单的特性，我们并不需要管这么多。比如这些内容：

  * [矿石生成](world-gen-feature/ore.md)
  * [野生动物生成](biome/natural-spawn.md)

但如果你想写一个全新的维度的话，那就需要做好被莫名其妙的数学公式绕晕的准备了。
