# Inter Risk — Site (protótipo estático)

Site institucional da Inter Risk, pronto para hospedar no GitHub Pages.

## Conteúdo
- `index.html` — Home
- `Sobre.html`, `Insights.html`
- Soluções: `Solucao.html` (Aviação), `Beneficios.html`, `Ramos-Elementares.html`, `Riscos-Maritimos.html`, `Resseguros.html`
- Indústrias: `Industria.html` (Agronegócio) e demais `Industria-*.html`
- `support.js` — runtime das páginas (necessário, manter na raiz)
- `assets/` — logos e imagens

## Como hospedar no GitHub Pages
1. Crie um repositório e envie **todos** os arquivos desta pasta para a raiz (mantendo `support.js` e `assets/` no mesmo nível dos `.html`).
2. Em **Settings → Pages**, selecione a branch (ex.: `main`) e a pasta `/ (root)`.
3. O GitHub publica em `https://<usuario>.github.io/<repo>/` — a entrada é `index.html`.

## Observações
- As páginas precisam de internet para a fonte Schibsted Grotesk (Google Fonts) e para as imagens dos cards de Insights (servidores Inter Risk / YouTube) e o player do Spotify. Tudo isso carrega normalmente quando o site está hospedado.
- Os links internos usam caminhos relativos (`Sobre.html`, `Solucao.html`, etc.), então funcionam em qualquer subdiretório.
