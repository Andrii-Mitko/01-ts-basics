# 01 TypeScript Basics

Навчальний проєкт для вивчення основ **TypeScript** та практичного закріплення базових концепцій мови. Містить 8 окремих завдань — від примітивних типів до асинхронних операцій і роботи з HTTP API.

## 🔗 Посилання

- **Live Demo:** https://andrii-mitko.github.io/01-ts-basics/
- **GitHub Repository:** https://github.com/Andrii-Mitko/01-ts-basics

## 🛠️ Технології

- TypeScript 6
- Vite 8
- Axios
- HTML5
- npm

## 📚 Практичні завдання

| №   | Тема            | Що вивчається                                   |
| --- | --------------- | ----------------------------------------------- |
| 1   | Primitive Types | `string`, `number`, `boolean`                   |
| 2   | Interfaces      | Інтерфейси, `readonly`, optional properties     |
| 3   | Arrays          | Типізація масивів та об'єктів                   |
| 4   | Functions       | Типізація параметрів і значень, що повертаються |
| 5   | Union Types     | Об'єднання типів та обмеження значень           |
| 6   | Generics        | Узагальнені функції та типи                     |
| 7   | Promises        | Типізація асинхронних операцій                  |
| 8   | HTTP Requests   | Axios, інтерфейси та типізація API-відповідей   |

## 📂 Структура проєкту

```text
01-ts-basics/
├── public/
│   ├── favicon.svg
│   └── icons.svg
├── src/
│   ├── task-1.ts
│   ├── task-2.ts
│   ├── task-3.ts
│   ├── task-4.ts
│   ├── task-5.ts
│   ├── task-6.ts
│   ├── task-7.ts
│   ├── task-8.ts
│   └── vite-env.d.ts
├── .gitignore
├── index.html
├── package.json
├── package-lock.json
├── tsconfig.json
└── README.md
```

## 🚀 Запуск проєкту

**Вимоги:** Node.js та npm.

1. Клонуйте репозиторій:

   ```bash
   git clone https://github.com/Andrii-Mitko/01-ts-basics.git
   ```

2. Перейдіть до папки проєкту:

   ```bash
   cd 01-ts-basics
   ```

3. Встановіть залежності:

   ```bash
   npm install
   ```

4. Запустіть режим розробки:

   ```bash
   npm run dev
   ```

5. Відкрийте адресу, яку покаже Vite у терміналі.

## 📦 Доступні команди

| Команда           | Призначення                            |
| ----------------- | -------------------------------------- |
| `npm run dev`     | Запуск сервера розробки                |
| `npm run build`   | Перевірка TypeScript та збірка проєкту |
| `npm run preview` | Перегляд production-збірки             |

## 📝 Примітки

- Кожне завдання розміщене в окремому TypeScript-файлі.
- Результати виконання прикладів виводяться в консоль браузера.
- Для завдання №8 потрібне підключення до інтернету, оскільки використовується зовнішній API JSONPlaceholder.
- Проєкт має навчальне призначення та не є production-застосунком.

---

**Автор:** [Andrii Mitko](https://github.com/Andrii-Mitko) · [Portfolio](https://andrii-mitko-brand.vercel.app/)
