# **[Snippets](./../../README.md) - Yarn**

[yarnpkg.com](https://yarnpkg.com/)

## Установка и обновление Yarn

```bash
npm install -g yarn
```

В каталоге проекта:

```bash
yarn set version berry
```

Обновление:

```bash
yarn set version latest
```

## Список команд

```bash
yarn help
```

## Инициализация проекта

```bash
yarn init
```

## Установка всех зависимостей

```bash
yarn install или просто yarn
```

## Установка зависимости

```bash
yarn add [package]
yarn add [package]@[version]
yarn add [package]@[tag]
```

## Добавление зависимости различных категорий

```bash
yarn add [package] --dev
yarn add [package] --peer
```

## Обновление зависимости

```bash
yarn up [package]
yarn up [package]@[version]
yarn up [package]@[tag]
```

## Удаление зависимости

```bash
yarn remove [package]
```
