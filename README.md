# NLW Agents - Web

Interface frontend do projeto NLW Agents, desenvolvido durante um evento da Rocketseat.

## Tecnologias Utilizadas

- **React 19** - Biblioteca para interfaces de usuário
- **TypeScript** - Tipagem estática
- **Vite** - Build tool e dev server
- **TailwindCSS v4** - Framework CSS utility-first
- **React Router DOM** - Roteamento SPA
- **TanStack Query** - Gerenciamento de estado server
- **Radix UI** - Componentes acessíveis
- **Lucide React** - Ícones
- **Biome** - Linter e formatter

## Setup e Configuração

### Pré-requisitos

- Node.js 18+

### Instalação

1. Instale as dependências:

```bash
npm install
```

### Desenvolvimento

```bash
npm run dev
```

### Build para Produção

```bash
npm run build
```

### Preview da Build

```bash
npm run preview
```

## Estrutura do Projeto

```
src/
├── components/      # Componentes reutilizáveis
│   └── ui/         # Componentes base (shadcn/ui)
├── pages/          # Páginas da aplicação
├── lib/            # Utilitários e configurações
├── app.tsx         # Configuração de rotas
└── main.tsx        # Entry point da aplicação
```

## Padrões de Desenvolvimento

- **Shadcn/ui Components** - Sistema de componentes baseado em Radix UI
- **Utility Classes** - TailwindCSS para estilização
- **Type Safety** - TypeScript em toda aplicação
- **Modern React** - Hooks e functional components
- **Client-side Routing** - React Router DOM para navegação

## Scripts Disponíveis

- `npm run dev` - Executa em modo desenvolvimento
- `npm run build` - Gera build de produção
- `npm run preview` - Preview da build de produção
