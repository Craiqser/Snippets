# **[Snippets](../README.md) - NPM**

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

## Поиск и просмотр информации о пакете

```bash
npm search i18next
npm view i18next
```

## Локальная и глобальная установка пакета

```bash
npm install i18next
npm install i18next -g
```

## Установка конкретной версии пакета

```bash
npm install i18next@0.13.2
```

## Проверка обновлений пакетов

```bash
npm outdated
```

## Локальное и глобальное удаление пакета

```bash
npm uninstall i18next
npm uninstall i18next -g
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
