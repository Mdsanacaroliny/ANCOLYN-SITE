# ANCOLYN-SITE[README.md](https://github.com/user-attachments/files/34591841/README.md)
# ANCOLYN | Social Media Boutique

Site institucional da ANCOLYN. Um único arquivo (`index.html`), sem etapa de build: fontes, React e imagens já estão referenciados ou embutidos.

## Publicar no GitHub Pages

1. Crie um repositório (ex.: `ancolyn-site`) e envie `index.html`, `README.md` e `.nojekyll`.
2. Em **Settings → Pages**, escolha **Deploy from a branch**, branch `main`, pasta `/ (root)`, e salve.
3. Em alguns minutos o site estará em `https://SEU-USUARIO.github.io/ancolyn-site/`.

Para usar um domínio próprio (ex.: `ancolyn.com.br`), informe-o em **Settings → Pages → Custom domain** e aponte o DNS conforme as instruções do GitHub.

## Editar conteúdo

No início do script em `index.html`:

- `CONFIG`: número de WhatsApp, link do WhatsApp, e-mail, Instagram e foto da fundadora.
- `PORTFOLIO`: projetos exibidos no portfólio (cliente, título, formato e lâminas).

As imagens estão embutidas no arquivo (`window.IMG` e `founderPhoto`). Fora do Claude, você também pode salvar as imagens em uma pasta `img/` e trocar os valores por caminhos como `img/foto.webp`.
