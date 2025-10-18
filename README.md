# 💼 Polarys

**Polarys** é um SaaS moderno para gestão financeira de **MEIs**, desenvolvido em um ambiente **monorepo** com **Next.js** (frontend) e **NestJS** (backend).

---

## 🚀 Tecnologias

- ⚡ **Next.js 15** com **Turbopack**
- 🧠 **NestJS 11**
- 🔷 **TypeScript**
- 📦 **pnpm Workspaces**
- 🧩 **Turborepo**

---

## ⚙️ Scripts principais

Na raiz do projeto:

```bash
# Inicia frontend e backend simultaneamente
pnpm dev

# Build de todos os apps
pnpm build

# Formata o código
pnpm format

polarys/
├── apps/
│   ├── web/   → frontend (Next.js)
│   └── api/   → backend (NestJS)
├── packages/  → libs e módulos compartilhados (futuro)
├── turbo.json
├── pnpm-workspace.yaml
└── package.json

# Clonar o repositório
git clone https://github.com/KaiqueWillian/polarys.git

# Entrar na pasta
cd polarys

# Instalar dependências
pnpm install

# Rodar o ambiente completo
pnpm dev
