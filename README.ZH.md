[English](./README.md) | 中文

# Turborepo + Tailwind 4 + Shadcn/ui Starter

这是一个基于 Turborepo 官方脚手架增强的项目模板，集成了最新的 Tailwind 4 和 Shadcn/ui 组件库。

## 特性

- 🚀 基于 Turborepo 的高性能 Monorepo 工作流
- 💎 集成最新的 Tailwind 4，支持更多强大的样式特性
- 🎨 内置 Shadcn/ui 组件库，提供美观且可定制的 UI 组件
- ♻️ 完全兼容 Tailwind 3 组件，无缝迁移

## 使用方法

运行以下命令创建项目：

```sh
npx create-turbo@latest
```

## 项目结构

### 应用和包

- `web`: 另一个 [Next.js](https://nextjs.org/) 应用
- `@repo/ui`: 共享的 React 组件库，集成了 Shadcn/ui，供 `web` 应用使用
- `@repo/eslint-config`: ESLint 配置（包含 `eslint-config-next` 和 `eslint-config-prettier`）
- `@repo/typescript-config`: 整个 Monorepo 使用的 `tsconfig.json` 配置

所有的包和应用均使用 [TypeScript](https://www.typescriptlang.org/) 开发。

### 工具集成

本项目已经为您配置好了以下工具：

- [TypeScript](https://www.typescriptlang.org/) - 静态类型检查
- [ESLint](https://eslint.org/) - 代码检查
- [Prettier](https://prettier.io) - 代码格式化
- [Tailwind CSS 4](https://tailwindcss.com) - 最新版本的实用优先的 CSS 框架
- [Shadcn/ui](https://ui.shadcn.com) - 高质量的 React 组件库

### Tailwind 4 特性

本项目集成了 Tailwind CSS 4，带来了许多激动人心的新特性：

- 更强大的响应式设计能力
- 增强的主题定制选项
- 优化的构建性能
- 新增的实用工具类

### Tailwind 3 兼容性

我们确保了与 Tailwind 3 的完全兼容性：

- 支持所有 Tailwind 3 的类名和功能
- 无需修改即可使用现有的 Tailwind 3 组件
- 平滑的升级路径，可逐步采用新特性

### 构建

构建所有应用和包：

```
cd my-turborepo
pnpm build
```

### 开发

启动开发环境：

```
cd my-turborepo
pnpm dev
```

## 有用链接

了解更多关于 Turborepo 的强大功能：

- [任务](https://turbo.build/repo/docs/core-concepts/monorepos/running-tasks)
- [缓存](https://turbo.build/repo/docs/core-concepts/caching)
- [远程缓存](https://turbo.build/repo/docs/core-concepts/remote-caching)
- [过滤](https://turbo.build/repo/docs/core-concepts/monorepos/filtering)
- [配置选项](https://turbo.build/repo/docs/reference/configuration)
- [CLI 使用](https://turbo.build/repo/docs/reference/command-line-reference)
