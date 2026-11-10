# Site de Isabelly Roditis — pronto para GitHub e Vercel

Esta pasta contém o site já compilado. Não é necessário enviar `src`, `node_modules` ou executar `npm install` na Vercel.

## Enviar ao GitHub

1. Extraia o ZIP, caso esteja usando o arquivo compactado.
2. Abra a pasta `ARQUIVOS-PARA-GITHUB-VERCEL`.
3. Envie **todos os itens dentro dela** para a raiz do repositório GitHub: `index.html`, `vercel.json`, `favicon.svg`, `asset-manifest.json`, `images/`, `static/` e este guia.
4. Confirme no GitHub que `index.html` e `vercel.json` aparecem diretamente na página inicial do repositório, sem uma pasta envolvendo os arquivos.

**Não envie apenas o ZIP ao GitHub.** O ZIP serve para baixar e transportar os arquivos.

## Configurar na Vercel

Ao importar o repositório do GitHub, use:

- **Root Directory:** raiz do repositório (`./`).
- **Framework Preset:** `Other`.
- **Build Command:** em branco.
- **Output Directory:** `.`.
- **Environment Variables:** nenhuma.

O arquivo `vercel.json` incluído confirma o diretório de saída e configura o encaminhamento para `index.html`.

O botão **Entre em contato** abre o WhatsApp (13) 99621-6524. O formulário **Preparar e-mail** abre o aplicativo de e-mail do visitante.
