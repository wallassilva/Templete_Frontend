## 🚀 Tecnologias

- [React 18](https://react.dev/)
- [Vite](https://vitejs.dev/)
- [TypeScript](https://www.typescriptlang.org/)

---

## ▶️ Como rodar

```bash
# Clone o repositório
git clone https://github.com/wallassilva/Templete_Frontend.git

# Entre na pasta
cd Templete_Frontend

# Instale as dependências
npm install

# Inicie o servidor de desenvolvimento
npm run dev
```

---

## 📁 Estrutura de pastas

```
Templete_Frontend/
├── public/
│   └── favicon.svg                 # Ícone da aba do navegador
│
├── src/
│   ├── assets/                     # Arquivos estáticos (imagens, ícones, fontes)
│   │   ├── react.svg
│   │   └── vite.svg
│   │
│   ├── components/                 # Componentes React reutilizáveis
│   │   └── .gitkeep                # (pasta reservada — adicione seus componentes aqui)
│   │
│   ├── config/                     # Configurações globais da aplicação
│   │   └── .gitkeep                # (ex: constantes, configuração de API, rotas)
│   │
│   ├── pages/                      # Páginas da aplicação
│   │   └── .gitkeep                # (cada página é uma pasta ou arquivo .tsx)
│   │
│   ├── services/                   # Chamadas à API (axios)
│   │   └── .gitkeep                # (ex: obrasService.ts, authService.ts)
│   │
│   ├── styles/                     # Arquivos CSS globais e variáveis
│   │   └── globals.css             # Design tokens (cores, fontes, espaçamentos)
│   │
│   ├── types/                      # Interfaces e tipos TypeScript
│   │   └── .gitkeep                # (ex: )
│   │
│   ├── utils/                      # Funções utilitárias e helpers
│   │   └── .gitkeep                # (ex: formatDate.ts, masks.ts)
│   │
│   ├── App.tsx                     # Componente raiz da aplicação
│   ├── App.css                     # Estilos do componente raiz
│   ├── index.css                   # Estilos base (importa o globals.css)
│   └── main.tsx                    # Ponto de entrada — monta o React no DOM
│
├── index.html                      # HTML raiz do Vite
├── vite.config.ts                  # Configuração do Vite
├── tsconfig.json                   # Configuração base do TypeScript
├── tsconfig.app.json               # Configuração TypeScript para o app
├── tsconfig.node.json              # Configuração TypeScript para o Vite (Node)
├── package.json                    # Dependências e scripts npm
├── eslint.config.js                # Configuração do ESLint
└── .gitignore                      # Arquivos ignorados pelo Git
```

---

## 🎨 Design Tokens

O arquivo `src/styles/globals.css` centraliza todas as variáveis de estilo do sistema. Importe-o no `main.tsx` ou no `index.css`:

```ts
// main.tsx
import './styles/globals.css'
```

### Cores disponíveis

| Variável | Valor | Uso |
|---|---|---|
| `--color-primary` | `#155DFC` | Botões, links, itens ativos |
| `--color-primary-light` | `#F1F8FF` | Fundos de destaque |
| `--color-danger` | `#E7000B` | Botão Sair, erros |
| `--color-success` | `#02AC02` | Bordas de metas e ações |
| `--color-text-primary` | `#45556C` | Texto base |
| `--color-text-info` | `#2B7FFF` | Avisos com fundo azul claro |
| `--color-bg-page` | `#F0F4F8` | Fundo geral da página |
| `--color-bg-card` | `#FFFFFF` | Cards e painéis |
| `--color-sidebar-bg` | `#1A2B45` | Fundo da sidebar |
---

## 🔤 Tipografia

| Variável | Fonte | Uso |
|---|---|---|
| `--font-primary` | Arimo | Corpo geral da aplicação |
| `--font-info` | Inter | Avisos e alertas informativos |

---

## 📜 Scripts disponíveis

| Comando | O que faz |
|---|---|
| `npm run dev` | Inicia o servidor de desenvolvimento |
| `npm run lint` | Roda o ESLint para verificar o código |
