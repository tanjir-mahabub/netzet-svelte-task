# Netzet Svelte Task

A modern web project built with **SvelteKit**, **TailwindCSS**, and **TypeScript**, initialized using the official [`sv`](https://github.com/sveltejs/cli). This project is optimized for fast development and deployment on **Vercel**.

---

## 🚀 Tech Stack

- [SvelteKit](https://kit.svelte.dev/) – Full-stack application framework
- [Tailwind CSS](https://tailwindcss.com/) – Utility-first CSS framework
- [TypeScript](https://www.typescriptlang.org/) – Static type checking
- [Vercel](https://vercel.com/) – Zero-config deployment
- [pnpm](https://pnpm.io/) – Fast, disk-efficient package manager

---

## 📦 Getting Started

Clone the repository and install dependencies:

```bash
git clone https://github.com/your-username/netzet-svelte-task.git
cd netzet-svelte-task
pnpm install
```

---

## 🧪 Development

Start a development server:

```bash
pnpm dev
```

Or with automatic browser open:

```bash
pnpm dev -- --open
```

---

## 🛠 Build

Create a production build of the app:

```bash
pnpm build
```

Preview the production build locally:

```bash
pnpm preview
```

---

## ☁️ Deployment (Vercel)

This project uses the official **Vercel adapter** for deployment.

### Deploy Steps:

1. Push this project to GitHub/GitLab/Bitbucket.
2. Visit [vercel.com](https://vercel.com) and import the repository.
3. Vercel will auto-detect the SvelteKit + Vite project.
4. No extra configuration needed. Click "Deploy".

> The adapter is already configured in `svelte.config.js`:

```ts
import vercel from '@sveltejs/adapter-vercel';
export default {
	kit: {
		adapter: vercel()
	}
};
```

---

## 🎨 Styling

TailwindCSS is fully integrated. Configuration is in:

- `tailwind.config.js`
- `src/app.postcss` or `src/app.css`

Customize utility classes and themes as needed.

---

## 🧹 Linting & Formatting

This project includes:

- `eslint` – Linting
- `prettier` – Code formatting

Run manually:

```bash
pnpm lint
pnpm format
```

---

## 📁 Project Structure (Minimal)

```
netzet-svelte-task/
├── src/
│   ├── routes/       → SvelteKit routing
│   ├── lib/          → Components, utilities
│   └── app.css       → Tailwind entry CSS
├── svelte.config.js  → SvelteKit config
├── tailwind.config.js
├── tsconfig.json
└── README.md
```

---

## 🧾 License

[MIT](LICENSE)

---
