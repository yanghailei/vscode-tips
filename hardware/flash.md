
sector： 扇区是磁盘的最小操作单位，一般是512字节，新的磁盘有4K的扇区
block：块是操作系统的概念，一般block = sector * （1~N)
---
> 在Windows下，FAT，FAT32和NTFS 文件系统中叫做簇（cluster）；在Linux下如Ext4等文件系统中叫做块（block）。
> 每个簇或者块可以包括2、4、8、16、32、64…2的n次方个扇区。
---
> 磁盘控制器，其作用除了读取数据、控制磁头等作用外，还有的功能就是映射扇区和磁盘块的关系。
> 扇区是对硬盘而言，是物理层的，块和簇是对文件系统而言，是逻辑层的。磁盘控制器是用来映射两层的。
---
> 操作系统操作需要与内存、硬盘这两种硬件设备打交道。
> 都需要虚拟一种单位来操作。与内存操作，是虚拟一个页的概念来作为最小单位。
> 与硬盘打交道，就是以块为最小单位。
---
## 磁盘组成
- 磁头
- 磁道：一个盘面上的同心圆
- 柱面: 多个盘面上相同编号的同心圆组成的柱面
- 扇区：磁道上的某一段


