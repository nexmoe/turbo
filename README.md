English | [中文](./README.ZH.md)

# Turborepo + Tailwind 4 + Shadcn/ui Starter

This is an enhanced project template based on the official Turborepo scaffold, integrated with the latest Tailwind 4 and Shadcn/ui component library.

## Features

- 🚀 High-performance Monorepo workflow powered by Turborepo
- 💎 Integration of the latest Tailwind 4, supporting more powerful styling features
- 🎨 Built-in Shadcn/ui component library, providing beautiful and customizable UI components
- ♻️ Full compatibility with Tailwind 3 components, seamless migration

## Getting Started

Run the following command to create a project:

```sh
npx create-turbo@latest
```

## Project Structure

### Apps and Packages

- `web`: A [Next.js](https://nextjs.org/) app
- `@repo/ui`: Shared React component library integrated with Shadcn/ui, used by the `web` app
- `@repo/eslint-config`: ESLint configurations (includes `eslint-config-next` and `eslint-config-prettier`)
- `@repo/typescript-config`: `tsconfig.json` configurations used throughout the Monorepo

All packages and apps are written in [TypeScript](https://www.typescriptlang.org/).

### Integrated Tools

This project has been configured with the following tools:

- [TypeScript](https://www.typescriptlang.org/) - Static type checking
- [ESLint](https://eslint.org/) - Code linting
- [Prettier](https://prettier.io) - Code formatting
- [Tailwind CSS 4](https://tailwindcss.com) - Latest version of the utility-first CSS framework
- [Shadcn/ui](https://ui.shadcn.com) - High-quality React component library

### Tailwind 4 Features

This project integrates Tailwind CSS 4, bringing many exciting new features:

- Enhanced responsive design capabilities
- Improved theme customization options
- Optimized build performance
- New utility classes

### Tailwind 3 Compatibility

We ensure full compatibility with Tailwind 3:

- Support for all Tailwind 3 class names and functionalities
- Use existing Tailwind 3 components without modification
- Smooth upgrade path for gradually adopting new features

### Build

Build all apps and packages:

```
cd my-turborepo
pnpm build
```

### Development

Start the development environment:

```
cd my-turborepo
pnpm dev
```

## Useful Links

Learn more about Turborepo's powerful features:

- [Tasks](https://turbo.build/repo/docs/core-concepts/monorepos/running-tasks)
- [Caching](https://turbo.build/repo/docs/core-concepts/caching)
- [Remote Caching](https://turbo.build/repo/docs/core-concepts/remote-caching)
- [Filtering](https://turbo.build/repo/docs/core-concepts/monorepos/filtering)
- [Configuration Options](https://turbo.build/repo/docs/reference/configuration)
- [CLI Usage](https://turbo.build/repo/docs/reference/command-line-reference)