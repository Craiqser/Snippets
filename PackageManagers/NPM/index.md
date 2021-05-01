# **[Snippets](./../../README.md) - NPM**

[www.npmjs.com](https://www.npmjs.com/)

## Установка и обновление NPM

Windows: ставится вместе с nodejs (https://nodejs.org/ru/);\
Unix-like:

```bash
curl https://npmjs.org/install.sh | sh
```

Обновление:

```bash
npm install npm -g
```

## Инициализация проекта с вопросами и без.

```bash
npm init
npm init -y
```

## Установка всех зависимостей
```bash
npm install
```

## Поиск и просмотр информации о зависимости

```bash
npm search [package]
npm view [package]
```

## Локальная и глобальная установка зависимости

```bash
npm install [package]
npm install [package] -g
```

## Установка конкретной версии зависимости

```bash
npm install [package]@[version]
```

## Проверка обновлений зависимостей

```bash
npm outdated
```

## Локальное и глобальное удаление зависимости

```bash
npm uninstall [package]
npm uninstall [package] -g
```

## Пример одновременного запуска задач

- Средствами npm:

```bash
npm run watch-js & npm run watch-css
```

- С помощью пакета [concurrently](https://www.npmjs.com/package/concurrently)

```json
{
	"scripts": {
		"dev": "concurrently \"npm:dev:backend\" \"npm:dev:frontend\"",
		"dev:backend": "nodemon src/server/index.js --watch",
		"dev:frontend": "vue-cli-service serve --port 3000"
	}
}
```
