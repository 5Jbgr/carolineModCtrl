# .pak - 卡罗琳模组管理器

![主界面预览图](https://github.com/5Jbgr/carolineModCtrl/blob/main/img/mainui.png)
基于aardio的管理器，玩家可以轻松管理、安装和卸载游戏模组，提供更丰富的游戏体验。
支持基于哈希的重复模组检测，添加预览图，按照角色分类。

## 使用方法

1. 打开管理器，设置游戏所在目录
2. 点击添加，选择.pak文件加入管理器
3. 双击或者选中后点击启用/禁用来操作模组
4. 模组文件如果需要更新，在模组列表中选择对应的模组，点击更新文件。

详细使用方法请参照[Wiki](https://github.com/5Jbgr/carolineModCtrl/wiki)。

## 模组文件自动分类

依靠程序读取pak文件内封游戏资源文件名，通过字符匹配的方式获取对应其对应角色编号，通过编号对应表确定其所属类别。因此此分类器仅支持角色对应模组，非角色模组分类将失效或可能误报。
自动分类功能拥有最高优先级，仅当自动分类无法判断时才会使用用户指定的类别。
pak文件内封资源名解析代码翻译自项目[CUE4Parse](https://github.com/FabianFG/CUE4Parse)。
**由于样本不足无法测试到全部代码，如果出现问题请提出[issue](https://github.com/5Jbgr/carolineModCtrl/issues)并附带对应问题文件或者将问题以及文件[发到邮箱](mailto:whkq668220@outlook.com)。**

## 开发计划

+ ~~模组详细分类方法~~
+ ~~批量导入功能~~
+ ~~模组可添加预览图片~~
+ ~~重复模组检测~~
+ 文件拖动导入
+ 模组排序
+ ~~配置自动更新~~
+ 完善图片文件管理
+ ~~模组信息列显示可控~~
+ ~~控制模组方式可选硬链接/复制~~
+ ~~导入模组方式可选复制/移动~~
+ ~~添加模组可自动解析压缩包中文件~~
+ 模组集合启用方案

## 其它

有其他需求可在issue中提出
