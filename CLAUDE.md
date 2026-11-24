# Consent Radar — site público

Site institucional da extensão Consent Radar. HTML + CSS puros, sem build, sem framework.

## Regras

- **Conteúdo** das páginas: português do Brasil.
- **Nomes de arquivos e pastas**: inglês (en-US), minúsculas, com hífen (ex.: `privacy.html`, `css/style.css`).
- **Classes e ids em HTML/CSS**: inglês (ex.: `id="content"`, `.site-footer`).
- Zero rastreamento: sem analytics, sem pixels, sem Google Fonts nem CDNs — as fontes da marca (IBM Plex) são
  servidas pelo próprio site, em `fonts/`. Único terceiro permitido: o embed do Tally na página `pro.html`.
- Responsivo, acessível (contraste, alt, foco visível via `:focus-visible`).
- Trechos de decisão jurídica na política de privacidade ficam marcados `[REVISAR]` até validação humana — nenhum
  pode permanecer ao publicar.
- A declaração de Limited Use (seção 10 de `privacy.html`) é exigida pela Chrome Web Store para qualquer
  extensão que lide com dados do usuário — não só para quem usa APIs do Google. Não remover essa declaração.
- Sem commit/push sem aprovação explícita do usuário em cada ocasião.

## Identidade visual

Fonte de verdade: `BRAND.md` e `brand-tokens.css` no kit de marca (fora deste repositório). Resumo:

- **Indício, nunca selo.** Nada na identidade (ícone, ilustração, botão) pode sugerir aprovação ou certificação —
  sem escudo, check, carimbo, selo ou medalha.
- **O semáforo é dos achados, não da marca.** `status-ok`/`status-warn`/`status-critical` (verde/laranja/vermelho)
  só representam o resultado de uma checagem. Nunca usar esses tons como cor da marca, de fundo ou de destaque —
  a cor da marca é `--brand` (petróleo).
- **Nada de aparência oficial.** Sem o verde e amarelo nem o azul do gov.br, brasões, ou qualquer elemento que
  sugira ser uma ferramenta da ANPD.
- **Zero terceiros.** Fontes (IBM Plex Sans/Mono) ficam em `fonts/`, com a licença em `fonts/OFL.txt`. Nunca
  carregar Google Fonts nem CDN de fonte.
- **Tamanho mínimo da marca:** a marca completa (`images/consent-radar-mark.svg`) nunca abaixo de 48px; para 32px
  ou menos, usar a versão simplificada (`images/consent-radar-mark-small.svg`).
- **Voz:** português do Brasil, minúscula de frase ("Ver cookies desta página", não "Ver Cookies Desta Página"),
  vocabulário de indício ("encontrado"/"não encontrado"/"não verificado"/"indício" — nunca "conforme", "aprovado",
  "seguro" ou "certificado").
