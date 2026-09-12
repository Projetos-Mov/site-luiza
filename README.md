# NAVS Consultoria Técnica — Landing Page

Site estático. Basta servir a pasta.

## Estrutura
- index.html — página (SEO, JSON-LD, GTM GTM-T3WC4S6C)
- support.js — runtime que renderiza a página
- assets/ — logo e fotos

## Publicação
GitHub Pages: Settings → Pages → branch `main`, pasta `/site`.
Ou Vercel/Netlify apontando para esta pasta.

## Antes de publicar
1. Trocar as URLs `https://www.navsconsultoria.com.br/` (canonical, Open Graph) pelo domínio final.
2. No GTM, criar gatilhos de Evento Personalizado: `generate_lead` (cta_label, cta_location) e `scroll_depth` (percent_scrolled 25/50/75/100).
3. Verificar a propriedade no Google Search Console e enviar o sitemap.

WhatsApp de contato: +55 71 99963-4593
