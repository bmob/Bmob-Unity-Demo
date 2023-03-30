# Bmob Unity使用教程
# 项目准备
本教程采用Unity Hub3.3.0-c8，编辑器采用2021.3.21flc1（长期支持版本），visual studio 2019社区版。

# 创建项目
![创建项目](./imgs/%E5%88%9B%E5%BB%BA%E9%A1%B9%E7%9B%AE.png "创建项目")

# 下载源码
源码地址：[下载源码](./Source.zip "源码地址")，并解压如下：

# 导入源码
打开创建的项目，把整个Source文件夹复制（拖拽）到Assets文件夹下，如下图。
![导入源码](./imgs/%E5%AF%BC%E5%85%A5%E6%BA%90%E7%A0%81.png "导入源码")

# 获取密钥
在Bmob后端云后台，创建项目，并获取这个项目对应的Application ID和REST API Key，如下图。
![获取密钥](./imgs/%E8%8E%B7%E5%8F%96%E5%AF%86%E9%92%A5.png "获取密钥")

# 填入密钥
把Assets/Bmob/api/BmobUnity.cs文件 和 Assets/HelloBmob.cs 文件同时拖拽到需要用到数据服务的对象中（如主摄像头），并把从Bmob后端云中获取的密钥填写到组件中，如下图。
![设置密钥](./imgs/%E8%AE%BE%E7%BD%AE%E5%AF%86%E9%92%A5.png "设置密钥")

# 运行项目
如果一切操作都顺利的话，运行项目就会如下图。
![运行项目](./imgs/%E6%96%B0%E5%A2%9E%E6%95%B0%E6%8D%AE.png "运行项目")

BmobUnity.cs文件包含了不少的测试案例，如果你有更多的疑问，请参考Bmob Unity开发文档：

# 相关资料
- [Bmob Unity开发文档](https://github.com/bmob/bmob-demo-csharp/wiki/1-%E5%BF%AB%E9%80%9F%E5%85%A5%E9%97%A8)
- [Bmob官方网址](https://www.bmobapp.com/)
- 官方QQ：2395453054