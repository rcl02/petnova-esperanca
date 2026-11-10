# Site Pet Shop Nova Esperança

Landing page estática (HTML + CSS puro) que leva o visitante a agendar pelo WhatsApp.

## Arquivos

| Arquivo | O que é |
|---|---|
| `index.html` | Página inteira (estrutura, CSS e o pequeno script de animação) |
| `assets/img` | Fotos em AVIF/WebP (400 px e 724 px) + JPG original de reserva, ícones, imagem de compartilhamento (OG) |
| `assets/fonts` | Fontes Archivo Black e Poppins (WOFF2, auto-hospedadas) |
| `_headers` | Regras de cache para o Cloudflare Pages |
| `robots.txt`, `sitemap.xml`, `favicon.ico`, `favicon.svg`, `apple-touch-icon.png`, `site.webmanifest` | SEO e ícones |

## O que falta preencher

- **Endereço final do site**: troque `https://petnova-esperanca.pages.dev/` pelo endereço real em `index.html`, `robots.txt` e `sitemap.xml` (procure por `✏️ CONFIRMAR`).
- **Horário de funcionamento** (opcional, ajuda no Google): adicione `openingHoursSpecification` no bloco `application/ld+json` do `index.html`.

## Trocar uma foto

Gere `nome-400.avif/.webp`, `nome-724.avif/.webp` e `nome.jpg` (proporção 4:5) em `assets/img` e troque `nome` no `<picture>` correspondente.

## Publicar grátis no Cloudflare Pages

Cloudflare → Workers & Pages → Create → Pages → **Upload assets** → arraste esta pasta → Deploy.
