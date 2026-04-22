<div align="center">

<img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" />
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
<img src="https://img.shields.io/badge/tsup-building-orange?style=for-the-badge" />
<img src="https://img.shields.io/badge/tsx-dev--runtime-black?style=for-the-badge" />
<img src="https://img.shields.io/badge/license-MIT-blue?style=for-the-badge" />

# ⚙️ Node.js TypeScript Boilerplate

**A minimal and framework-agnostic Node.js boilerplate built with TypeScript, designed for clarity, control and scalable foundations.**

</div>

---

## 📌 Overview

This boilerplate provides a **clean starting point for Node.js applications using TypeScript**, without relying on frameworks or unnecessary abstractions.

Instead of enforcing a rigid architecture upfront, this boilerplate focuses on:

- A **minimal and understandable structure**
- **Explicit configuration handling**
- A foundation that **evolves naturally as the application grows**

The goal is to strike a balance between:

- Overengineered boilerplates that slow you down
- Bare setups that don’t scale

---

## 🏗 Project Structure

```
src/
├── config/
│   └── env.ts        # Environment loader and validation
└── server.ts         # Application entry point
```

| File        | Responsibility                                           |
| ----------- | -------------------------------------------------------- |
| `server.ts` | Bootstraps the application and handles startup lifecycle |
| `env.ts`    | Loads and validates environment variables from `.env`    |

---

## ✨ Features

- ⚡ Minimal and clean project structure
- 🔐 Typed environment variables (no external libraries)
- 🔥 Fast development workflow using tsx
- 📦 Optimized build with tsup
- 🧠 Explicit and predictable application startup
- 🧩 Framework-agnostic (ready for Fastify, Express, or native HTTP)

---

## ⚙️ Environment Setup

Create a `.env` file in the root:

```env
PORT=3000
```

> `.env` files are ignored by Git to prevent sensitive data from being exposed.  
> Use `.env.example` as a reference.

---

## 🛠 Technologies

| Package       | Role                                                  |
| ------------- | ----------------------------------------------------- |
| `typescript`  | Static typing and modern language features            |
| `tsx`         | Development runtime for executing TypeScript directly |
| `tsup`        | Bundler for generating production builds              |
| `@types/node` | Type definitions for Node.js                          |

---

## 🚀 Getting Started

### Prerequisites

- Node.js v18+

### Installation

```bash
git clone https://github.com/your-username/node-ts-minimal-boilerplate.git
cd node-ts-minimal-boilerplate
npm install
```

### Run in development

```bash
npm run dev
```

### Run production build

```bash
npm run build
npm start
```

Once running, the application will be available at:

```
http://localhost:3000
```

---

## 📜 Scripts

| Script        | Command                   | Description                        |
| ------------- | ------------------------- | ---------------------------------- |
| `dev`         | `tsx watch src/server.ts` | Run in development mode with watch |
| `build`       | `tsup`                    | Build the project into `dist/`     |
| `build:watch` | `tsup --watch`            | Rebuild on file changes            |
| `start`       | `node dist/server.js`     | Run compiled production build      |

---

## 🧠 Philosophy

This boilerplate is built around a few core principles:

- **Simplicity first** - no abstractions without real need
- **Explicit over implicit** - clear and predictable behavior
- **Scales naturally** - as the project grows
- **Framework-agnostic** - no lock-in to any HTTP layer

---

## 🔮 Intended Usage

This boilerplate is designed to be used as a foundation for:

- REST APIs
- Microservices
- Backend services
- Prototyping and rapid development

It can be easily extended with:

- Fastify or Express
- Database layers
- Validation systems
- Logging tools

---

## 📄 License

MIT License

---

## 👨‍💻 Author

**Victor Hugo**  
Frontend Engineer · [GitHub](https://github.com/itsmevictorhugo) · [LinkedIn](https://linkedin.com/in/itsmevictorhugo)
