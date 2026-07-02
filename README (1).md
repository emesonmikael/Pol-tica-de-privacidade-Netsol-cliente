# Política de Privacidade – NetSol Cliente

Projeto estático (HTML puro) contendo a Política de Privacidade do aplicativo **NetSol Cliente**, pronto para publicação na **Vercel**.

## Estrutura do projeto

```
vercel-project/
├── index.html      # Página principal (Política de Privacidade)
├── vercel.json     # Configuração da Vercel
└── README.md       # Este arquivo
```

## Como publicar na Vercel

### Opção 1 – Deploy via interface web (mais simples)

1. Acesse [https://vercel.com](https://vercel.com) e faça login (pode usar sua conta GitHub, GitLab ou e-mail).
2. Clique em **"Add New..." → "Project"**.
3. Escolha **"Import"** (se estiver no GitHub) **ou** arraste a pasta `vercel-project` na área de upload em **"Deploy"**.
4. Não precisa configurar build — a Vercel detecta que é um site estático automaticamente.
5. Clique em **Deploy**.
6. Em segundos você terá uma URL pública tipo `https://seu-projeto.vercel.app`.

### Opção 2 – Deploy via Vercel CLI

```bash
# 1. Instale a CLI (uma única vez)
npm i -g vercel

# 2. Entre na pasta do projeto
cd vercel-project

# 3. Faça o deploy
vercel

# 4. Para publicar em produção
vercel --prod
```

### Opção 3 – Deploy via GitHub

1. Crie um repositório no GitHub e envie os arquivos do projeto.
2. Na Vercel, clique em **"Import Project"** e selecione o repositório.
3. Deixe as configurações padrão e clique em **Deploy**.
4. A cada `git push` a Vercel fará deploy automático.

## Contato

- **WhatsApp:** +55 84 9 9918-1760
- **E-mail:** pablorafael.2009@gmail.com
