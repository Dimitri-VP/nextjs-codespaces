# Next.js Codespaces Project

Este é um projeto Next.js configurado para desenvolvimento na nuvem usando GitHub Codespaces.

## Como começar

1. Crie um repositório no GitHub com este template.
2. Abra o repositório no GitHub Codespaces:
   - Clique em "Code" > "Open with Codespaces" > "New codespace".
3. Aguarde o ambiente ser configurado (o `postCreateCommand` instalará as dependências).
4. Execute `npm run dev` no terminal para iniciar o servidor de desenvolvimento.
5. Acesse a aplicação no endereço exibido (geralmente `http://localhost:3000`).

## Estrutura do projeto

- `.devcontainer/devcontainer.json`: Configuração do ambiente Codespaces.
- `package.json`: Dependências e scripts do projeto.
- `pages/index.js`: Página inicial padrão do Next.js.

## Comandos úteis

- `npm run dev`: Inicia o servidor de desenvolvimento.
- `npm run build`: Gera a build de produção.
- `npm run start`: Inicia a aplicação em modo produção.
- `npm run lint`: Executa o linter.

## Extensões VS Code

O ambiente inclui:
- ESLint para linting.
- Prettier para formatação de código.
- Suporte ao Turbopack (opcional, para builds mais rápidas).
