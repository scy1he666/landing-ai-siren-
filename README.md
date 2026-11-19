<div align="center">

# SIREN AI — Landing Page

**Лендинг новой AI-модели с глубоким пониманием контекста.**

[![React](https://img.shields.io/badge/React-19.2.6-61DAFB?logo=react&logoColor=black)](https://react.dev/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.9.3-3178C6?logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Vite](https://img.shields.io/badge/Vite-7.3.7-646CFF?logo=vite&logoColor=white)](https://vite.dev/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-4.1.17-06B6D4?logo=tailwindcss&logoColor=white)](https://tailwindcss.com/)
[![Status](https://img.shields.io/badge/status-WIP-yellow)](https://github.com/scy1he666/landing-ai-siren-/projects)

[![Stars](https://img.shields.io/github/stars/scy1he666/landing-ai-siren-?style=social)](https://github.com/scy1he666/landing-ai-siren-/stargazers)
[![Forks](https://img.shields.io/github/forks/scy1he666/landing-ai-siren-?style=social)](https://github.com/scy1he666/landing-ai-siren-/forks)
[![Issues](https://img.shields.io/github/issues/scy1he666/landing-ai-siren-)](https://github.com/scy1he666/landing-ai-siren-/issues)
[![Last commit](https://img.shields.io/github/last-commit/scy1he666/landing-ai-siren-)](https://github.com/scy1he666/landing-ai-siren-/commits)
[![Top language](https://img.shields.io/github/languages/top/scy1he666/landing-ai-siren-)](https://github.com/scy1he666/landing-ai-siren-)
[![Repo size](https://img.shields.io/github/repo-size/scy1he666/landing-ai-siren-)](https://github.com/scy1he666/landing-ai-siren-)

</div>

---

## О проекте

SIREN AI — промо-страница искусственного интеллекта, ориентированная на глубокое понимание контекста.
Ключевое сообщение лендинга: тестовый доступ уже открыт, и пользователь получает **50 000 кредитов** на знакомство с моделью.

Проект собран на современном стеке: React 19 + TypeScript в связке с Vite 7 и Tailwind CSS 4. Сборка настроена через `vite-plugin-singlefile`: результат получается одним автономным HTML-файлом, который удобно публиковать как статику без дополнительных ассетов.

> [!NOTE]
> Сейчас в репозитории — каркас проекта: `index.html` и конфигурация сборки. Папка `src/` и `favicon.svg`, на которые ссылается точка входа, ещё не добавлены, поэтому `npm run dev` / `npm run build` пока не заработают до появления исходников.

## Возможности

- ⚡️ Мгновенная разработка и production-сборка на Vite 7
- ⚛️ React 19 с новым JSX-рантаймом (`react-jsx`)
- 🎨 Tailwind CSS 4 через официальный Vite-плагин
- 🧩 Алиас `@/*` → `src/*` для чистых импортов
- 📦 Single-file сборка: весь JS и CSS инлайнятся в `dist/index.html`
- 🔒 Строгий TypeScript: `strict`, `noUnusedLocals`, `noUnusedParameters`, `noFallthroughCasesInSwitch`
- 🌐 Русскоязычная страница с готовыми метаданными (description, theme-color, шрифты Manrope и Unbounded)

## Стек

| Слой | Технология | Версия |
| --- | --- | --- |
| UI | [React](https://react.dev/) | 19.2.6 |
| Язык | [TypeScript](https://www.typescriptlang.org/) | 5.9.3 |
| Сборщик | [Vite](https://vite.dev/) | 7.3.7 |
| Стили | [Tailwind CSS](https://tailwindcss.com/) | 4.1.17 |
| Утилиты | clsx, tailwind-merge | 2.1.1 / 3.4.0 |
| Плагины | `@vitejs/plugin-react`, `@tailwindcss/vite`, `vite-plugin-singlefile` | 5.1.1 / 4.1.17 / 2.3.0 |

## Структура

```text
landing-ai-siren-/
├── index.html          # точка входа: #root, подключение /src/main.tsx, метаданные
├── package.json        # зависимости и npm-скрипты
├── package-lock.json   # зафиксированные версии зависимостей
├── tsconfig.json       # строгий TS, bundler-режим, алиас @/*
├── vite.config.ts      # React + Tailwind + singlefile, alias @ → src
└── src/                # исходники приложения (пока не добавлены)
```

## Быстрый старт

Требуется **Node.js 20.19+** или **22.12+** (минимальные версии для Vite 7).

```bash
# 1. Клонировать репозиторий
git clone https://github.com/scy1he666/landing-ai-siren-.git
cd landing-ai-siren-

# 2. Установить зависимости
npm install

# 3. Запустить dev-сервер (http://localhost:5173)
npm run dev
```

## Скрипты

| Команда | Назначение |
| --- | --- |
| `npm run dev` | запуск dev-сервера с HMR |
| `npm run build` | production-сборка в `dist/` (один HTML-файл) |
| `npm run preview` | локальный просмотр готовой сборки из `dist/` |

## Roadmap

- [ ] Добавить `src/main.tsx`, стили и `favicon.svg`
- [ ] Сверстать секции лендинга (hero, преимущества, CTA)
- [ ] Настроить CI-проверку сборки
- [ ] Опубликовать демо-страницу

## Лицензия

Файл `LICENSE` в репозитории отсутствует — по умолчанию все права защищены. Если нужна open source-лицензия, добавьте соответствующий файл в корень проекта.

---

<div align="center">

Сделано с ⚛️ React и ⚡ Vite · [Репозиторий на GitHub](https://github.com/scy1he666/landing-ai-siren-)

</div>
