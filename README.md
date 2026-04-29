# ⚛️ React Environment (VS Code)

Базовый репозиторий для настройки комфортной среды разработки на **React** с использованием **VS Code**.

## 🔧 Рекомендуемые расширения VS Code

Рекомендуемые расширения для эффективной работы с React:

- [ES7+ React/Redux/React-Native snippets](https://marketplace.visualstudio.com/items?itemName=dsznajder.es7-react-js-snippets) — автосниппеты для компонентов, хуков и пр.
- [Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag) — синхронное переименование JSX-тегов
- [Auto Close Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-close-tag) — автозакрытие тегов
- [Prettier – Code Formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) — автоформатирование кода
- [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint) — линтинг кода по правилам
- [Path Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense) — автоподсказки путей к файлам

> 💡 Все рекомендуемые расширения перечислены в `.vscode/extensions.json` и будут предложены при открытии проекта в VS Code.

## ⚙️ Настройки

Редактор автоматически применяет настройки из `.vscode/settings.json`.

> 💡 Код автоматически форматируется при сохранении, если установлены Prettier и ESLint, а в настройках VS Code включён `editor.formatOnSave`.

## 🚀 Быстрый старт

```bash
git clone https://github.com/Out0fScope/react-environment.git
cd react-environment
npm install
npm run dev       # Запуск dev-сервера с хот-револдом
npm run build     # Сборка production версии в папку dist
npm start         # Запуск статического сервера для продакшн сборки
npm run preview   # Запуск production-сборки в локальном сервере (удобно для проверки перед деплоем)

```

## 🎯 Линтинг и форматирование

Для проверки кода на ошибки и соответствие стилю:

```bash
npm run lint
npm run format:check

```

Для автоматического исправления:

```bash
npm run lint:fix
npm run format

```
