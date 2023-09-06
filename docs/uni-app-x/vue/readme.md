# vue

uni-app x的vue语法，是按vue3规范实现的，但一期uvue不支持setup，只支持选项式。

目前也不支持vue插件，比如pinia、vuex、i18n、router。简单的状态管理可以参考文档[全局变量和状态管理](tutorial/store.md)

还有一些支持差异，在左侧文档点开后搜索“uni-app x”可见。

- 组件使用注意

默认组件的后缀名为.vue。而不是.uvue。

.vue里面写uvue的语法，可以正常被.uvue页面引用和编译。

如果使用.uvue的组件，则需要手动import，包括easycom也必须配规则才能识别。