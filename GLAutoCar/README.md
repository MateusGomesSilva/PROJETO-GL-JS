# GL - AutoCar

Este repositório contém um site estático (HTML/CSS/JS) pronto para deploy no Vercel.

Instruções rápidas para deploy pelo Vercel:

- Opcão A — Usar o site do Vercel (recomendado):
  1. Commit e push do repositório para o GitHub.
  2. Aceda a https://vercel.com/import e conecte o repositório.
  3. Escolha o projeto e clique em Deploy. O Vercel detecta site estático automaticamente.

- Opcão B — Usar o `vercel` CLI:
  1. Instale o Vercel CLI: ``npm i -g vercel``
  2. No diretório do projeto, execute: ``vercel``
  3. Siga as instruções interativas para criar/deployar o projecto.

Notas e alterações feitas para compatibilidade com Vercel:
- Adicionado `index.html` (lowercase) — servidores Linux são case-sensitive; o Vercel usa Linux, por isso criámos `index.html` a partir do seu `Index.html`.
- Corrigido um `src` de imagem que apontava para um caminho local do Windows e substituído por `img/lineup-suvs-26-escalade-iql-l-v3.avif`.
- Adicionado `vercel.json` com uma configuração simples para servir o projeto como site estático.

Se quiser que eu:
- renomeie/remova o `Index.html` original em vez de duplicar;
- crie um `package.json` com scripts de build (se for necessário usar um framework);
- corrija mais paths relativos e pequenos problemas de HTML/CSS;
diga qual opção prefere e eu aplico.
