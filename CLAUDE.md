# Colosso Reformas e Construções — Site

Protótipo de site da **Colosso Reformas e Construções** (reformas / construção civil).
Cliente EngeTech Reis.

## O que é
- HTML/CSS/JS puro, single-file (`index.html`). Protótipo de prospecção.

## Preview
Servidor estático na **porta 3001** (`python -m http.server 3001`).

## Deploy / Repo
- Repo: **https://github.com/ClaudeReis/colosso-site-** (branch `main`). Só o **site** vai ao GitHub; proposta/apresentação comercial fica local.
- Publicado via **GitHub Pages**: **https://claudereis.github.io/colosso-site-/**
- **Google Search Console:** propriedade verificada (arquivo `google410a0cf7b8fa500b.html` na raiz). Home **indexada** (HTTPS ✓). Sitemap pode mostrar "não foi possível ler" — cosmético, a página já indexou.
- ⚠️ Domínio próprio `colossoreformas.com.br` **ainda não está no ar**. Por isso `canonical`, `og:url`, schema `@id/url`, `robots.txt` e `sitemap.xml` apontam para a URL do **github.io** por enquanto. Quando o domínio for ao ar, reverter as URLs e criar nova propriedade no Search Console.

## Identidade Visual (Brand Guide oficial)

### Slogan
> "Construímos sonhos. Reformamos espaços. **Entregamos resultados.**"

### Cores da marca
| Token          | Hex       | Uso                          |
|----------------|-----------|------------------------------|
| Verde escuro   | `#0F3D2E` | Fundo principal, header      |
| Verde médio    | `#2E7D32` | Botões, destaques secundários|
| Amarelo        | `#FFC107` | CTA, destaques, acento       |
| Cinza          | `#555555` | Texto corrido                |
| Off-white      | `#F5F5F5` | Fundo de seções claras       |

### Tipografia
- **Títulos e destaques:** Poppins Extra Bold
- **Textos e informações:** Poppins Regular

### Contato oficial
- WhatsApp: **21 98084-5281**
- Instagram: **@colossoreformaseconstrucoes**
- Atendimento: Rio de Janeiro e Região

### Pilares de conteúdo
1. **Obras e Projetos** — obras em andamento e concluídas
2. **Dicas de Construção** — conteúdo educativo
3. **Transformações** — antes e depois
4. **Qualidade e Segurança** — compromisso com normas
5. **Clientes Satisfeitos** — depoimentos e histórias reais

### Valores da marca (trust bar)
- Qualidade do início ao fim
- Segurança em cada detalhe
- Confiança que constrói resultados
- Compromisso com prazos e excelência

## Regras de agência
- **Personalizar por este cliente** — nunca template genérico de agência.
- Mobile-first (maioria do tráfego é celular), CTA do WhatsApp sempre alcançável.
- Sem prova social fabricada.
- Mostrar **prévia antes** de commit/push.

## Status do alinhamento de marca
- ✅ Paleta oficial aplicada nos tokens CSS (`:root`) — verde escuro/médio, amarelo, cinza, off-white.
- ✅ Fonte **Poppins** (heading 800 / body 400) substituindo Montserrat + Inter.
- ✅ Logo SVG, favicon e `theme-color` recoloridos para os hexes oficiais.
- ✅ Títulos em verde escuro (`#0F3D2E`); corpo em cinza (`#555555`).
- ✅ Hero usa o **slogan institucional** ("Construímos sonhos. Reformamos espaços. *Entregamos resultados.*"). A headline de conversão anterior ("Sua obra começa bagunçada...") foi substituída a pedido do cliente.

## Status de SEO
- ✅ Title (~48 chars) e meta description (~155 chars) otimizados.
- ✅ Schema `LocalBusiness` + `FAQPage` (FAQ bate com a página). `aggregateRating` fabricada **removida** (era 4.9/47 sem avaliações reais).
- ✅ `robots.txt` + `sitemap.xml` na raiz.
- Pendente (nice-to-have): `og:image`/`twitter:image` próprias da marca (hoje usam fotos genéricas do Unsplash).
