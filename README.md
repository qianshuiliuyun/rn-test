# rn-test

RN 测试题
assets 目录下有两张图片，一张原图，一张遮罩图，请使用 object-c 或者 swift 利用像素遍历实现抠图效果，并且在 RN 中显示。
题目完成后提供github链接，需要可以完整运行。
技术要点
1. 编写ios像素遍历抠图，提供桥接接口供rn使用（提供一个桥接函数，传入原图和遮罩图路径，返回抠完图的路径）
2. 展示页面分别用class组件和函数组件实现

加分项
1. 抠图可以编写android原生模块
2. 使用typescript做类型约束
3. 在class组件和函数组件可以使用mobx对生成图进行状态管理
4. 能够对原生模块做容错处理

最终效果图如下

![effect.png](https://github.com/qianshuiliuyun/rn-test/blob/main/effect.png)
