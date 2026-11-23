# Consent Radar — site público

Site institucional da extensão Consent Radar. HTML + CSS puros, sem build, sem framework.

## Regras

- **Conteúdo** das páginas: português do Brasil.
- **Nomes de arquivos e pastas**: inglês (en-US), minúsculas, com hífen (ex.: `privacy.html`, `css/style.css`).
- **Classes e ids em HTML/CSS**: inglês (ex.: `id="content"`, `.site-footer`).
- Zero rastreamento: sem analytics, sem pixels, sem Google Fonts nem CDNs — só fontes de sistema. Único terceiro
  permitido: o embed do Tally na página `pro.html`.
- Responsivo, acessível (contraste, alt, foco visível via `:focus-visible`).
- Trechos de decisão jurídica na política de privacidade ficam marcados `[REVISAR]` até validação humana — nenhum
  pode permanecer ao publicar.
- A declaração de Limited Use (seção 10 de `privacy.html`) é exigida pela Chrome Web Store para qualquer
  extensão que lide com dados do usuário — não só para quem usa APIs do Google. Não remover essa declaração.
- Sem commit/push sem aprovação explícita do usuário em cada ocasião.
