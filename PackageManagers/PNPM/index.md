# **[Snippets](./../../README.md) - PNPM**

[pnpm.io](https://pnpm.io/ru/)

## Установка и обновление PNPM

- Установка с использованием npm

```bash
npm install -g pnpm
```

- Установка через npx

```bash
npx pnpm add -g pnpm
```

- Обновление

```bash
pnpm add -g pnpm
```

## Установка всех зависимостей
```bash
pnpm install или pnpm i
```

## Локальная и глобальная установка зависимости

```bash
pnpm add [package]
pnpm add [package] -g
```

## Установка зависимости в devDependencies

```bash
pnpm add [package] -D
```

## Установка конкретной версии зависимости

```bash
pnpm add [package]@[version]
```

## Проверка обновлений зависимостей

```bash
pnpm outdated
```

## Локальное и глобальное удаление зависимости

```bash
pnpm remove [package]
pnpm remove [package] -g
```
