《The Swift Programming Language》in Chinese
=============================================

中文版 Apple 官方 Swift 教程《The Swift Programming Language》

[英文原版在线版](https://docs.swift.org/swift-book/)

# 在线阅读

使用 GitBook 制作，可以在 [GitBook](https://swiftgg.gitbook.io/swift/) 网站阅读。

# 当前阶段

- 更新到 Swift 5.7，2022-06-06
- 更新到 Swift 5.6，2022-03-14
- 更新到 Swift 5.5，2021-06-07
- 更新到 Swift 5.4，2021-04-26
- 更新到 Swift 5.3，2020-09-16
- 更新到 Swift 5.2，2020-02-15
- 更新到 Swift 5.1，2019-11-11
- 更新到 Swift 5.0，2019-04-05
- 更新到 Swift 4.2，2019-01-29
- 更新到 Swift 4.1，2018-04-12，感谢 [@Mylittleswift](https://github.com/Mylittleswift)
- 更新到 Swift 3.0，2016-09-23


# 贡献力量

如果想做出贡献的话，你可以：

- 参与翻译
- 帮忙校对，挑错别字、病句等等
- 提出修改建议
- 提出术语翻译建议

# 翻译建议

如果你有兴趣参与项目，请仔细阅读说明：

排版格式和流程说明：

- 翻译排版格式要求参考 SwiftGG [排版指南](https://github.com/SwiftGGTeam/translation/blob/master/SwiftGG%20排版指南.md)
- Pull Request 发起方式参考 SwiftGG [Pull Request 说明](https://github.com/SwiftGGTeam/translation/blob/master/%E7%BF%BB%E8%AF%91%E6%B5%81%E7%A8%8B%E6%A6%82%E8%BF%B0%E5%8F%8APR%E8%AF%B4%E6%98%8E.md#%E5%A6%82%E4%BD%95%E5%8F%91%E8%B5%B7-pull-request)

原版文档差异比较：

在翻译时可以通过 Calibre 软件对 [document 目录下](https://github.com/SwiftGGTeam/the-swift-programming-language-in-chinese/tree/gh-pages/document) 不同版本的文档进行 diff，检查待更新部分。

diff 操作如下：

将最新文档加入到 Calibre 中，点击 **Edit Book**，然后在编辑界面选择 **File** -> **Compare to other book** 检查各模块的更新内容，详见 [链接](https://manual.calibre-ebook.com/diff.html)。

其他说明：

- 相关术语请严格按照术语表来翻译，如果有问题可以发 Issue 大家一起讨论
- 使用 Markdown 进行翻译，文件名必须使用英文
- 翻译后的文档请放到 source 文件夹下的对应章节中，然后 Pull Request 即可，我们会用 GitBook 编译成网页
- 有其他任何问题都欢迎发 Issue

# 术语表

翻译术语的时候请参考这个对照表：

| 术语 | 备选翻译 |
| --- | --- |
| result builder | 结果构造器 |
| property wrapper | 属性包装器（[翻译相关讨论](https://github.com/SwiftGGTeam/the-swift-programming-language-in-chinese/issues/982#issuecomment-536244784)） |
| projected value | 被呈现值 |
| wrapped value | 被包装值 |
| argument | 实参 |
| parameter | 形参 |
| variadic parameters| 可变参数 |
| associated type | 关联类型 |
| range | 区间 |
| type property | 类型属性 |
| unary operator | 一元运算符 |
| binary operator | 二元运算符 |
| ternary operator | 三元运算符 |
| labeled statement | 具名语句 |
| conform protocol | 遵循协议 |
| availability-condition | 可用性条件 |
| fallthrough | 贯穿 |
| branch statement | 分支语句 |
| control transfer statement | 控制传递语句 |
| type annotation | 类型注解 |
| type identifier | 类型标识符 |
| metatype type | 元类型 |
| protocol composition type | 复合协议类型 |
| associated value | 关联值 |
| raw value | 原始值 |
| computed property | 计算属性 |
| stored property | 存储属性 |
| operator | 运算符 |
| playground | 不翻译 |
| array | 数组 |
| dictionary | 字典 |
| list | 列表 |
| statement | 语句 |
| expression | 表达式 |
| optional | 可选 |
| implicitly unwrapped optional | 隐式解包可选值 |
| optional binding | 可选绑定 |
| optional chaining | 可选链 |
| collection | 集合 |
| convention | 约定 |
| iterate | 迭代 |
| nest | 嵌套 |
| inheritance | 继承 |
| override | 重写 |
| base class | 基类 |
| designated initializer | 指定构造器 |
| convenience initializer | 便利构造器 |
| automatic reference counting | 自动引用计数 |
| type inference | 类型推断 |
| type casting | 类型转换 |
| unwrapped | 解包 |
| wrapped | 包装 |
| note | 注意 |
| closure | 闭包 |
| tuple | 元组 |
| first-class | 一等 |
| deinitializer | 析构器 |
| initializer | 构造器 |
| initialization | 构造过程 |
| deinitialization | 析构过程 |
| getter | 不翻译 |
| setter | 不翻译 |
| subscript | 下标 |
| property | 属性 |
| attribute | 特性或者属性，根据上下文 |
| method | 方法 |
| enumeration | 枚举 |
| structure | 结构体 |
| protocol | 协议 |
| extension | 扩展 |
| generic | 泛型 |
| literal value | 字面量 |
| alias | 别名 |
| assertion | 断言 |
| conditional compilation | 条件编译 |
| opaque type | 不透明类型 |
| function | 函数 |
| runtime | 运行时 |

# 贡献者

[贡献者列表](https://github.com/SwiftGGTeam/the-swift-programming-language-in-chinese/blob/gh-pages/source/contributors.md)，感谢大家！



# 协议
和 [苹果官方文档](https://swift.org/documentation/) 协议一致：[Creative Commons Attribution 4.0 International (CC BY 4.0) License](https://creativecommons.org/licenses/by/4.0/)。
#Thank you😊
