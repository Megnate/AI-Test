# AI-Test

一些AI Agent或工具的自定义项目

## 项目内容

### Vue 2.7 到 Vue 3 迁移工具

本项目包含用于在Dify平台中将Vue 2.7项目升级到Vue 3的AI Agent提示词和相关文档。

#### 文件说明

- **`dify-agent-prompt.md`** - 优化后的AI提示词，专门用于Dify Agent，用于将Vue 2.7的class装饰器语法转换为Vue 3的setup语法
- **`使用文档.md`** - 详细的使用文档，包含配置步骤、使用方法、常见问题处理等
- **`vue2-to-vue3-migration-prompt.md`** - 原始版本的迁移提示词（保留作为参考）

#### 快速开始

1. 在Dify平台创建Agent应用
2. 将`dify-agent-prompt.md`的内容复制到Agent的提示词配置中
3. 按照`使用文档.md`中的说明使用Agent进行代码迁移

#### 功能特性

- ✅ 自动将class组件转换为setup语法
- ✅ 处理所有this引用
- ✅ 转换Vuex 3到Pinia
- ✅ 处理Vue实例方法（$confirm、$bus、$store等）
- ✅ 支持自定义指令转换
- ✅ 完整的类型定义支持
