# WebFont Golos Text

Пакет для установки веб-шрифта: Golos Text.

## Установка

Чтобы установить пакет, Вы можете воспользоваться командой в CLI:

```bash 
npm install --save https://github.com/getscope/npm-webfont-golos-text
```

или в файле `package.json` создать свойство `dependencies` и добавить ссылку на github-репозиторий:

```json 
{
    "dependencies": {
        "@getscope/npm-webfont-golos-text": "github:getscope/npm-webfont-golos-text"
    }
}
```

и выполнить команду в CLI для обновления установленных зависимостей:

```bash 
npm update
```

## Примеры использования и подключения

```css 
body {
    font-family: 'Golos Text', sans-serif;
}
```

Для импорта веб-шрифта в SCSS, Вы можете воспользоваться следующими путями:

```scss 
@import "node_modules/@getscope/npm-webfont-golos-text/src/scss/_400-normal.scss";
@import "node_modules/@getscope/npm-webfont-golos-text/src/scss/_500-normal.scss";
@import "node_modules/@getscope/npm-webfont-golos-text/src/scss/_600-normal.scss";
@import "node_modules/@getscope/npm-webfont-golos-text/src/scss/_700-normal.scss";
@import "node_modules/@getscope/npm-webfont-golos-text/src/scss/_900-normal.scss";
@import "node_modules/@getscope/npm-webfont-golos-text/src/scss/_all-normal.scss";
```
