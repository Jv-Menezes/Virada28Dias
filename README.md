# Calculadora de IMC — Projeto Virada 28 Dias 🔥

Calculadora de IMC completa com análise personalizada, dicas e visual motivacional.

## Deploy na Vercel (passo a passo)

### Opção 1 — Pelo GitHub (recomendado)

1. Crie um repositório no GitHub (ex: `calculadora-imc`)
2. Faça upload dos arquivos desta pasta para o repositório
3. Acesse [vercel.com](https://vercel.com) e faça login com sua conta GitHub
4. Clique em **"Add New Project"**
5. Selecione o repositório que você criou
6. A Vercel vai detectar as configurações automaticamente
7. Clique em **"Deploy"**
8. Pronto! Sua URL será algo como: `calculadora-imc.vercel.app`

### Opção 2 — Pelo CLI da Vercel

```bash
# Instale a CLI da Vercel (se ainda não tiver)
npm install -g vercel

# Na pasta do projeto, rode:
vercel

# Siga as instruções no terminal
# Na primeira vez, vai pedir login e configuração
# Depois é só confirmar e aguardar o deploy
```

### Opção 3 — Arrastar e soltar

1. Acesse [vercel.com/new](https://vercel.com/new)
2. Arraste a pasta `public` para a área de upload
3. Aguarde o deploy
4. Pronto!

## Domínio personalizado (opcional)

Após o deploy, você pode conectar um domínio próprio:

1. No dashboard da Vercel, acesse seu projeto
2. Vá em **Settings > Domains**
3. Adicione seu domínio (ex: `imc.projetovirada28dias.com.br`)
4. Aponte o DNS conforme as instruções da Vercel

## Estrutura do projeto

```
vercel-imc/
├── public/
│   └── index.html    ← Calculadora completa (HTML/CSS/JS)
├── package.json
├── vercel.json       ← Configuração da Vercel
└── README.md
```
