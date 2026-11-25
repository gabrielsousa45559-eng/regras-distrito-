# Regras — Distrito 011 Paulista

Site público com as regras da cidade organizadas por categoria. O conteúdo foi estruturado a partir do documento de regras fornecido pelo responsável do Distrito 011.

## Publicar no Render

Crie um serviço **Static Site** no Render e conecte este repositório. Configure:

- **Branch:** `main`
- **Root Directory:** deixe vazio
- **Build Command:** deixe vazio
- **Publish Directory:** `.`

Não use **Web Service** nem Docker para esta publicação. O site é composto por HTML, JavaScript, CSS e imagens; não precisa de instalação nem etapa de build. Se a tela pedir um `Dockerfile`, volte e crie um **Static Site**.

Para executar localmente ou em uma VPS, sirva esta pasta com qualquer servidor de arquivos estáticos.

## GitHub Pages

Para publicar pelo GitHub Pages, abra **Settings → Pages** neste repositório e selecione **Deploy from a branch**, branch `main` e pasta `/ (root)`.
