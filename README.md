# LMS

A modern frontend starter template built with **Vue 3**, **Vite**, **TypeScript**, **Tailwind CSS**, **Vitest**, and **Storybook**.

##  Features

* Vue 3 with Composition API
* Vite for fast development and optimized builds
* TypeScript support
* Tailwind CSS v4
* Unit Testing with Vitest
* Component Testing with Vue Test Utils
* Storybook for component-driven development
* Accessibility testing with Storybook A11y
* Browser testing with Playwright
* Code Coverage with V8

##  Tech Stack

| Technology     | Purpose                  |
| -------------- | ------------------------ |
| Vue 3          | Frontend Framework       |
| Vite           | Build Tool               |
| TypeScript     | Static Typing            |
| Tailwind CSS   | Styling                  |
| Vitest         | Unit Testing             |
| Vue Test Utils | Vue Component Testing    |
| Storybook      | UI Component Development |
| Playwright     | Browser Testing          |

---

##  Prerequisites

* Node.js 20+
* npm 10+

---

##  Installation

Clone the repository and install dependencies:

```bash
npm install
```

---

##  Development

Start the development server:

```bash
npm run dev
```

Application will be available at:

```text
http://localhost:5173
```

---

##  Build for Production

```bash
npm run build
```

Preview the production build:

```bash
npm run preview
```

---

##  Testing

Run unit tests:

```bash
npx vitest
```

Run tests in watch mode:

```bash
npx vitest --watch
```

Generate coverage report:

```bash
npx vitest run --coverage
```

---

## Storybook

Start Storybook:

```bash
npm run storybook
```

Storybook will be available at:

```text
http://localhost:6006
```

Build Storybook:

```bash
npm run build-storybook
```

---

##  Project Structure

```text
src/
├── assets/
├── components/
│   ├── Button.vue
│   └── Button.stories.ts
├── views/
├── App.vue
├── main.ts
└── style.css

.storybook/
├── main.ts
└── preview.ts
```

---

##  Scripts

| Command                   | Description              |
| ------------------------- | ------------------------ |
| npm run dev               | Start development server |
| npm run build             | Build application        |
| npm run preview           | Preview production build |
| npm run storybook         | Run Storybook            |
| npm run build-storybook   | Build Storybook          |
| npx vitest                | Run tests                |
| npx vitest run --coverage | Generate coverage report |

---

## Contributing

Contributions, issues, and feature requests are welcome.

##  License

MIT License
