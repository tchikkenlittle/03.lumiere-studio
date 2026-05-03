# 📋 GUIA BASE — Portfólios para Fotógrafos de Produto no Fiverr
### Do primeiro protótipo até o gig publicado e vendendo
**Versão 1.0 | Maio de 2026 | Mantido por: você**

---

## ÍNDICE RÁPIDO

1. [O Nicho e Por Que Ele](#1-o-nicho-e-por-que-ele)
2. [Perfil do Seu Cliente Ideal](#2-perfil-do-seu-cliente-ideal)
3. [O Que o Site Precisa Ter](#3-o-que-o-site-precisa-ter)
4. [Identidade Visual — Padrão do Nicho](#4-identidade-visual--padrão-do-nicho)
5. [Stack Técnico — O Que Usar](#5-stack-técnico--o-que-usar)
6. [Estrutura do Site (Arquitetura de Páginas)](#6-estrutura-do-site-arquitetura-de-páginas)
7. [Protótipo: Roteiro do Primeiro Modelo](#7-protótipo-roteiro-do-primeiro-modelo)
8. [Criando os 3 Portfólios Demo Fictícios](#8-criando-os-3-portfólios-demo-fictícios)
9. [Recursos Gratuitos para os Demos](#9-recursos-gratuitos-para-os-demos)
10. [Estrutura dos Pacotes e Preços](#10-estrutura-dos-pacotes-e-preços)
11. [Montando o Gig no Fiverr — Passo a Passo](#11-montando-o-gig-no-fiverr--passo-a-passo)
12. [Títulos, Tags e Keywords](#12-títulos-tags-e-keywords)
13. [Texto da Descrição do Gig](#13-texto-da-descrição-do-gig)
14. [Estratégia dos Primeiros 90 Dias](#14-estratégia-dos-primeiros-90-dias)
15. [Checklist de Qualidade Antes de Entregar](#15-checklist-de-qualidade-antes-de-entregar)
16. [Armadilhas e Como Evitar](#16-armadilhas-e-como-evitar)
17. [Referências Rápidas de Design](#17-referências-rápidas-de-design)

---

## 1. O Nicho e Por Que Ele

**Nicho escolhido:** Sites de portfólio para **fotógrafos de produto e e-commerce**

### Por que este nicho é o melhor ponto de entrada para você

| Critério | Realidade |
|---|---|
| Mercado-alvo | Fotógrafos que atendem marcas Shopify, Amazon, Instagram DTC, cosméticos, moda, eletrônicos, alimentos embalados |
| Tamanho do mercado | E-commerce global em expansão acelerada → +68% das listagens exigem fotos profissionais |
| Cliente tem mentalidade de negócio? | ✅ Sim. Ele mede ROI. Briefings mais claros, menos drama emocional |
| Concorrência de gigs específicos no Fiverr | Baixa. Há muitos gigs genéricos de "fotógrafo portfolio", mas poucos especializados neste nicho |
| A estética é executável com HTML/CSS/JS? | ✅ Totalmente. Dark mode + grids limpos + hover effects = vibe coding puro |
| Demanda por updates recorrentes? | ✅ Sim. Fotógrafos de produto atualizam portfólio frequentemente = clientes recorrentes |

### O argumento central de venda para o cliente

> "Você fotografa produtos para marcas premium. Seu site precisa fazer o mesmo — apresentar seu trabalho como uma marca premium apresenta seus produtos. Eu construo isso com código limpo, rápido e sem os compromissos de qualidade dos construtores de sites genéricos."

---

## 2. Perfil do Seu Cliente Ideal

**Quem é esse fotógrafo:**
- Freelancer ou pequeno estúdio, geralmente 1–3 pessoas
- Trabalha com marcas de e-commerce: moda, beleza, eletrônicos, alimentos, utensílios domésticos
- Tem perfil no Instagram, mas o portfólio online é fraco ou inexistente
- Busca clientes no Fiverr, LinkedIn, ou por indicação
- Fatura entre US$ 2.000 e US$ 15.000/mês
- Tem consciência de que um site profissional atrairia clientes maiores
- Está acostumado a pagar por ferramentas e serviços (Adobe CC, estúdio, equipamento)

**O que ele quer do site:**
- Que as fotos sejam as estrelas — nada competindo com elas
- Credibilidade imediata para marcas que pesquisam o fotógrafo
- Um lugar claro para dizer quais são seus serviços e preços
- Formulário fácil de contato / pedido de orçamento
- Carregamento rápido (marcas acessam de desktop, muitas vezes em WiFi corporativo)

**O que ele NÃO quer:**
- Templates genéricos que qualquer fotógrafo tem
- Sites lentos cheios de plugins
- Design que compete visualmente com as fotos
- Processo complicado de atualização de conteúdo

---

## 3. O Que o Site Precisa Ter

### Funcionalidades obrigatórias (todo pacote)
- [ ] Header fixo com logo + navegação
- [ ] Hero section full-screen (imagem de destaque + headline)
- [ ] Galeria com efeito de hover (zoom suave + overlay com título do projeto)
- [ ] Seção "Sobre" (mini bio + especialidades)
- [ ] Seção de Serviços (o que oferece, para quais categorias de produto)
- [ ] Formulário de Contato funcional (pode usar Formspree.io — gratuito)
- [ ] Footer com links de redes sociais
- [ ] 100% responsivo (mobile, tablet, desktop)
- [ ] Imagens com lazy loading

### Funcionalidades do pacote Standard e acima
- [ ] Galeria categorizada (ex: Cosméticos / Moda / Eletrônicos)
- [ ] Seção de Logos de Clientes ("Já trabalhei com:")
- [ ] Depoimentos de clientes
- [ ] Animações de scroll suave (Intersection Observer API)
- [ ] Dark mode toggle (opcional, mas diferenciador forte)

### Funcionalidades do pacote Premium
- [ ] Case studies completos (3 projetos detalhados com antes/depois)
- [ ] Tabela de Pacotes e Preços do fotógrafo
- [ ] Instagram feed ao vivo (via widget embed — não exige API)
- [ ] Formulário de orçamento estruturado (com campos: tipo de produto, quantidade de SKUs, plataforma de destino)
- [ ] Blog básico (3 posts estáticos em HTML)
- [ ] Meta tags de SEO on-page

---

## 4. Identidade Visual — Padrão do Nicho

Esta é a linguagem visual que o mercado de fotografia de produto entende como "premium". Use como padrão nos seus templates.

### Paleta de Cores (Dark Mode — Default)

```
Fundo principal:     #0A0A0A  (preto profundo)
Fundo secundário:    #111827  (cinza escuro para seções alternadas)
Texto primário:      #F9FAFB  (branco suave)
Texto secundário:    #9CA3AF  (cinza médio para subtítulos/body)
Accent (personalize por cliente): 
  → Dourado/Luxo:    #C9A84C
  → Sage/Clean:      #6B8F71
  → Coral/Moderno:   #E07A5F
  → Azul/Tech:       #3B82F6
```

### Tipografia

```
Títulos (H1, H2):    Playfair Display ou Cormorant Garamond
                     (serif, editorial, premium)
Subtítulos (H3):     DM Sans SemiBold ou Inter SemiBold
Corpo de texto:      Inter Regular ou DM Sans Regular
Fonte de código:     não aplicável neste contexto

Importar via Google Fonts:
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;700&family=Inter:wght@300;400;600&display=swap" rel="stylesheet">
```

### Layout e Espaçamento

```
Container máximo:    1280px
Padding lateral:     clamp(1.5rem, 5vw, 4rem)  ← responsivo automático
Espaço entre seções: 120px desktop / 80px mobile
Gap de galeria:      8px a 16px (grid apertado = sensação editorial)
Bordas:              sem bordas rígidas — use sombras suaves ou separadores de 1px
Border-radius:       4px a 8px (minimalismo — evitar cards "arredondados demais")
```

### Efeitos e Animações

```css
/* Hover na galeria — padrão do nicho */
.gallery-item img {
  transition: transform 0.4s ease;
}
.gallery-item:hover img {
  transform: scale(1.03);
}
.gallery-item .overlay {
  opacity: 0;
  transition: opacity 0.3s ease;
  background: rgba(0,0,0,0.6);
}
.gallery-item:hover .overlay {
  opacity: 1;
}

/* Fade-in ao scroll — use Intersection Observer */
.reveal {
  opacity: 0;
  transform: translateY(30px);
  transition: opacity 0.6s ease, transform 0.6s ease;
}
.reveal.visible {
  opacity: 1;
  transform: translateY(0);
}
```

---

## 5. Stack Técnico — O Que Usar

### O que você produz (e por que é vantagem)

| Tecnologia | Por que usar | Vantagem vs. concorrentes |
|---|---|---|
| **HTML5 semântico** | Base de tudo | Sites mais leves e melhor SEO que WordPress |
| **CSS3 puro** | Estilo e animações | Sem dependências, carregamento instantâneo |
| **Vanilla JavaScript** | Interatividade | Sem jQuery, sem overhead |
| **Formspree.io** | Formulários | Gratuito, simples, sem backend |
| **Google Fonts** | Tipografia | Fácil e sem custo |
| **Unsplash Source** | Imagens demo | Gratuito para uso comercial |

### O que NÃO usar (e por quê)

| Evitar | Motivo |
|---|---|
| WordPress | Pesado, lento, vulnerável, fuga do seu diferencial |
| Bootstrap completo | Carrega CSS desnecessário, visual genérico |
| jQuery | Obsoleto para o que você precisa, aumenta peso |
| GSAP/Three.js (no Basic) | Overkill, deixa o site lento para pacotes simples |
| Wix/Squarespace | Isso é o que você está substituindo — nunca entregue |

### Hospedagem para indicar ao cliente (gratuita)

1. **Netlify** — drag & drop da pasta do site, HTTPS automático ⭐ recomendado
2. **GitHub Pages** — perfeito para quem tem conta GitHub
3. **Vercel** — alternativa sólida, igual ao Netlify em facilidade

---

## 6. Estrutura do Site (Arquitetura de Páginas)

### Pacote Basic (1 página — Landing Page)

```
index.html
  ├── Header (logo + nav âncora)
  ├── Hero (imagem full-screen + headline + CTA)
  ├── Gallery (grid 3 colunas, 12–20 imagens)
  ├── About (foto do fotógrafo + 3–4 linhas de bio)
  ├── Services (3 cards: Produto / Lifestyle / Editorial)
  ├── Contact (formulário Formspree)
  └── Footer
```

### Pacote Standard (até 5 páginas)

```
index.html          → Home (hero + destaques)
portfolio.html      → Galeria categorizada (3 abas/filtros)
about.html          → Bio completa + filosofia + equipamentos
services.html       → Serviços detalhados + logos de clientes
contact.html        → Formulário + links sociais
```

### Pacote Premium (tudo acima +)

```
case-study-1.html   → Projeto detalhado (marca, desafio, resultado)
case-study-2.html
case-study-3.html
pricing.html        → Tabela de pacotes do fotógrafo
blog/               → 3 posts estáticos
  ├── post-1.html
  ├── post-2.html
  └── post-3.html
```

---

## 7. Protótipo: Roteiro do Primeiro Modelo

Este é o passo a passo para criar seu **primeiro template base** antes de qualquer cliente.

### Fase 1 — Planejamento (30 min)

- [ ] Decida a identidade do fotógrafo fictício (nome, especialidade, cidade)
  - Ex: *"Mira Lens Studio — Product Photography for Beauty Brands | New York"*
- [ ] Escolha a paleta accent (dourado, sage, coral, azul)
- [ ] Selecione 12–16 fotos do Unsplash que representem o estilo
- [ ] Escreva 3–5 frases de headline e bio (use IA para ajudar)

### Fase 2 — Vibe Coding do HTML Base (1–2h)

Use seu AI de preferência com este prompt modelo:

```
"Crie um site de portfólio de página única para um fotógrafo de 
produto de e-commerce chamado [NOME]. O design deve ser dark mode 
(fundo #0A0A0A), com tipografia Playfair Display para títulos e 
Inter para corpo. Inclua: header fixo com logo e nav, hero 
full-screen, galeria em grid 3 colunas com hover overlay, seção 
sobre, seção de serviços com 3 cards, e formulário de contato. 
HTML + CSS + JS em arquivo único. Sem frameworks externos. 
Responsivo mobile-first."
```

### Fase 3 — Refinamento Visual (1–2h)

- [ ] Substitua imagens placeholder por fotos reais do Unsplash
- [ ] Ajuste cores do accent para combinar com as fotos escolhidas
- [ ] Revise a tipografia — tamanhos, pesos, espaçamento de linha
- [ ] Adicione animações de scroll (Intersection Observer)
- [ ] Ajuste o espaçamento entre seções (mínimo 80px mobile)
- [ ] Verifique contraste de acessibilidade (texto vs. fundo)

### Fase 4 — Testes de Responsividade (30–45 min)

Abra o Chrome DevTools (F12) → Toggle Device Toolbar e teste:

| Breakpoint | Tamanho | O que verificar |
|---|---|---|
| Mobile pequeno | 375px | Texto não cortado, galeria em 1 coluna, nav colapsada |
| Mobile médio | 414px | Mesmos checks |
| Tablet | 768px | Galeria em 2 colunas, layout intermediário |
| Desktop | 1280px | Layout completo, sem estiramentos |
| Wide | 1440px | Container máximo respeitado |

### Fase 5 — Deploy do Demo (15 min)

- [ ] Crie conta gratuita no Netlify (netlify.com)
- [ ] Faça drag & drop da pasta do site
- [ ] Copie o link público gerado (ex: `mira-lens.netlify.app`)
- [ ] Use esse link nas imagens de capa do gig

---

## 8. Criando os 3 Portfólios Demo Fictícios

Você precisa de **3 demos visualmente distintos** para o portfólio do gig no Fiverr. Isso demonstra versatilidade e cria prova de trabalho sem precisar de clientes reais.

### Demo 1 — Estúdio de Cosméticos/Beleza

```
Nome:         Lumière Studio
Localização:  Los Angeles, CA
Especialidade: Beauty & Skincare Product Photography
Accent:       #C9A84C (dourado)
Estilo:       Dark luxury, imagens de frascos com reflexos metálicos
Unsplash:     buscar "cosmetics photography", "perfume product"
Headline:     "Where skincare meets art."
```

### Demo 2 — Fotografia de Moda/Lifestyle para DTC

```
Nome:         FORME Visual
Localização:  Berlin, DE
Especialidade: Fashion & Apparel for DTC Brands
Accent:       #6B8F71 (sage/verde)
Estilo:       Clean, minimalista, muito espaço negativo
Unsplash:     buscar "fashion product photography", "clothing flatlay"
Headline:     "Product photography that converts browsers into buyers."
```

### Demo 3 — Fotografia de Eletrônicos/Tech

```
Nome:         Aperture.lab
Localização:  Tokyo, JP
Especialidade: Tech & Consumer Electronics Photography
Accent:       #3B82F6 (azul elétrico)
Estilo:       Fundo preto absoluto, iluminação de rim, estética Apple-like
Unsplash:     buscar "electronics photography", "tech product studio"
Headline:     "Precision photography for precision products."
```

---

## 9. Recursos Gratuitos para os Demos

### Imagens (uso comercial gratuito)

| Plataforma | URL | Melhor para |
|---|---|---|
| Unsplash | unsplash.com | Qualidade editorial, enorme variedade |
| Pexels | pexels.com | Boa alternativa, mais neutro |
| StockSnap | stocksnap.io | Menor volume, boa curadoria |

**Termos de busca recomendados no Unsplash:**
- `product photography studio`
- `cosmetics flatlay`
- `tech electronics dark background`
- `fashion clothing minimal`
- `food product packaging`

### Ícones e UI

- **Heroicons** (heroicons.com) — SVG gratuito, estilo limpo
- **Phosphor Icons** (phosphoricons.com) — alternativa excelente
- **Feather Icons** (feathericons.com) — minimalista, ideal para o estilo do nicho

### Fontes

- **Google Fonts** (fonts.google.com) — Playfair Display, Inter, DM Sans, Cormorant

### Formulários

- **Formspree** (formspree.io) — gratuito até 50 submissions/mês, sem backend

### Deploy

- **Netlify** (netlify.com) — gratuito, HTTPS, drag & drop
- **GitHub Pages** (pages.github.com) — gratuito, integrado ao Git

---

## 10. Estrutura dos Pacotes e Preços

### Tabela de Pacotes

| Item | 🥉 Basic ($150) | 🥈 Standard ($320) | 🥇 Premium ($550) |
|---|---|---|---|
| **Nome do pacote** | The Studio Starter | The Pro Portfolio | The Brand Studio |
| Número de páginas | 1 (landing page) | Até 5 páginas | Até 8 páginas |
| Galeria de imagens | 1 galeria (até 20 fotos) | 3 categorias de galeria | 3 categorias + case studies |
| Animações CSS | Básicas (fade hover) | Intermediárias (scroll reveal) | Completas + micro-interações |
| Dark Mode toggle | ❌ | ✅ | ✅ |
| Seção de logos de clientes | ❌ | ✅ | ✅ |
| Depoimentos | ❌ | ✅ (3) | ✅ (5) |
| Case studies | ❌ | ❌ | ✅ (3 projetos) |
| Tabela de preços do fotógrafo | ❌ | ❌ | ✅ |
| Instagram feed embed | ❌ | ❌ | ✅ |
| Formulário de orçamento | Simples | Estruturado | Completo |
| SEO on-page básico | ❌ | ❌ | ✅ |
| Prazo de entrega | 5 dias | 8 dias | 14 dias |
| Revisões incluídas | 2 | 3 | 5 |
| Código-fonte entregue | ✅ | ✅ | ✅ |
| Instruções de hospedagem | ✅ | ✅ | ✅ |

### Gig Extras (Add-ons)

| Extra | Preço |
|---|---|
| Galeria adicional (+ 1 categoria) | +$50 |
| Seção de vídeo / showreel embed | +$80 |
| Seção before/after interativa | +$100 |
| Entrega expressa (50% menos prazo) | +$40 |
| Copy/texto do site escrito por IA + revisão | +$60 |
| Post de blog extra | +$30 por post |

### Regra de ouro para precificação

> **Nunca abaixo de $120.** Preço sinaliza qualidade no Fiverr. Abaixo disso você atrai clientes problemáticos e compete com quem usa templates de $9. Você não está vendendo um template — está vendendo um ativo de negócio personalizado.

---

## 11. Montando o Gig no Fiverr — Passo a Passo

### Pré-requisitos antes de criar o gig

- [ ] 3 demos prontos e hospedados (Netlify ou GitHub Pages)
- [ ] Screenshots de qualidade dos 3 demos em 3 dispositivos (mobile, tablet, desktop)
- [ ] Vídeo de 60–90 segundos navegando pelos demos (use Loom gratuito)
- [ ] Conta no Fiverr criada e perfil 100% preenchido

### Configuração do Gig

**Categoria:** Programming & Tech → Website Development → Website Design  
**Sub-categoria:** Portfolio Website

**Imagens de capa do gig (obrigatórias — 3 imagens + 1 vídeo):**
1. Screenshot do demo mais impactante (wide desktop view)
2. Composição mostrando os 3 demos lado a lado
3. Versão mobile dos demos (mostra responsividade)
4. Vídeo: navegação real pelos sites

**Thumbnail ideal:**
- Fundo escuro (combina com sua estética)
- Texto sobreposto: "Portfolio Websites for Product Photographers"
- Setas ou destaques nos elementos mais bonitos do design

---

## 12. Títulos, Tags e Keywords

### Títulos recomendados (escolha 1 para o gig principal)

**Opção A — Mais direta:**
```
I Will Design a Stunning Dark Portfolio Website for Product Photographers
```

**Opção B — Com palavra de nicho forte:**
```
I Will Build a Custom HTML Portfolio Website for E-Commerce Product Photographers
```

**Opção C — Orientada ao cliente final do fotógrafo:**
```
I Will Create a Professional Portfolio Site for Product Photographers Serving Shopify Brands
```

### Tags (escolha 5 das abaixo — Fiverr permite 5)

```
product photographer website
photography portfolio website
ecommerce photographer site
custom html portfolio
dark mode portfolio website
commercial photographer website
studio photographer website
portfolio website design
```

**Palavras-chave para usar na descrição** (aumentam busca interna):
- product photographer portfolio
- ecommerce photography website
- commercial photography portfolio
- studio website design
- HTML portfolio website
- dark mode website photographer

---

## 13. Texto da Descrição do Gig

Use esta estrutura em inglês (idioma padrão do Fiverr):

```
ARE YOU A PRODUCT PHOTOGRAPHER WHO LOSES CLIENTS 
BECAUSE YOUR WEBSITE DOESN'T MATCH YOUR WORK?

You shoot for premium e-commerce brands.
Your images are stunning.
But your website looks outdated or generic.

That mismatch is costing you contracts every week.

━━━━━━━━━━━━━━━━━━━━━━━━
🎯 WHAT I DO
━━━━━━━━━━━━━━━━━━━━━━━━

I design sleek, dark-mode HTML portfolio websites built 
specifically for product & commercial photographers.

Not templates. Not WordPress. Pure code — fast, custom, 
and built to make your photos the hero of every page.

━━━━━━━━━━━━━━━━━━━━━━━━
✅ WHY HTML BEATS SQUARESPACE
━━━━━━━━━━━━━━━━━━━━━━━━

→ 3x faster loading (no plugins, no bloat)
→ Fully customizable — pixel perfect to your brand
→ You own the code forever (no monthly subscriptions)
→ Better SEO performance out of the box

━━━━━━━━━━━━━━━━━━━━━━━━
📦 WHAT YOU GET (all packages)
━━━━━━━━━━━━━━━━━━━━━━━━

✔ Mobile-first responsive design
✔ Full-screen hero with your best image
✔ High-resolution image gallery with hover effects
✔ Contact / booking form (ready to receive inquiries)
✔ Clean source code delivered to you
✔ Free hosting setup instructions (Netlify/GitHub Pages)

━━━━━━━━━━━━━━━━━━━━━━━━
🔄 MY PROCESS
━━━━━━━━━━━━━━━━━━━━━━━━

Day 1: You share your photos, brand colors, and bio
Day 2–4: I design + build your site
Day 5: First preview + revision round
Final: Clean delivery with all files

━━━━━━━━━━━━━━━━━━━━━━━━
💬 BEFORE YOU ORDER
━━━━━━━━━━━━━━━━━━━━━━━━

Message me first. I want to understand your brand before 
I build a single line of code. I reply within 2 hours.

Let's build a website as good as your photography.
```

---

## 14. Estratégia dos Primeiros 90 Dias

### Semana 1–2: Construção da Base

- [ ] Criar os 3 demos fictícios e hospedar online
- [ ] Criar conta no Fiverr (perfil completo: foto, bio, skills)
- [ ] Gravar vídeo de apresentação dos demos (Loom)
- [ ] Publicar o gig com todas as imagens e o vídeo

### Semana 3–4: Conseguir as Primeiras Reviews

**Estratégia de lançamento:**

- Ofereça 1–2 projetos por **$49–$79** (abaixo do preço final) apenas para conseguir as primeiras 3–5 avaliações positivas
- Anuncie isso na descrição: *"I'm building my portfolio — limited spots at a launch price."*
- Entregue com nível de qualidade Premium mesmo pagando Basic
- Peça avaliação no final: *"If you're happy with the result, a review would mean a lot!"*

**Onde encontrar seus primeiros clientes fora do Fiverr:**

- Reddit: r/photography, r/ecommerce, r/entrepreneur
- Facebook Groups: "Product Photography", "Amazon FBA Sellers"
- Instagram: comente em posts de fotógrafos de produto com portfólio fraco

### Mês 2: Otimização

- [ ] Analise as perguntas mais recebidas → atualize a descrição do gig
- [ ] Suba o preço Basic para $150 após 5 reviews positivas
- [ ] Adicione o pacote Standard formalmente
- [ ] Crie variações do gig (1 gig = Basic, crie 2° gig focado no Premium)

### Mês 3: Escala

- [ ] Ative o pacote Premium ($550)
- [ ] Crie Gig Extras personalizados baseados no que os clientes mais pedem
- [ ] Identifique qual sub-nicho de cliente mais compra (cosméticos? moda? tech?) e especialize ainda mais
- [ ] Peça depoimentos em texto para usar nas imagens do gig

### Meta de receita dos primeiros 90 dias

| Mês | Meta de Vendas | Receita Estimada |
|---|---|---|
| Mês 1 | 3–4 vendas (preço de lançamento $49–79) | $150–$300 |
| Mês 2 | 4–6 vendas ($150 Basic / $320 Standard) | $600–$1.200 |
| Mês 3 | 5–8 vendas (mix de pacotes) | $1.000–$2.500 |

---

## 15. Checklist de Qualidade Antes de Entregar

Execute este checklist **em todo projeto** antes de marcar como entregue:

### HTML e Código
- [ ] HTML validado (use validator.w3.org)
- [ ] Sem erros no console do navegador (F12 → Console)
- [ ] Todas as imagens com atributo `alt` preenchido
- [ ] Meta tags preenchidas (title, description, og:image)
- [ ] Favicon incluído

### Responsividade
- [ ] 375px (iPhone SE) — nada cortado ou sobreposto
- [ ] 768px (iPad) — layout intermediário correto
- [ ] 1280px (desktop padrão) — layout completo
- [ ] 1440px (wide) — sem estiramentos

### Performance
- [ ] Imagens comprimidas (use squoosh.app — gratuito)
- [ ] Lazy loading ativado nas imagens da galeria
- [ ] Teste de velocidade no PageSpeed Insights (meta: 80+)

### Experiência do Usuário
- [ ] Formulário de contato testado (envie um teste real)
- [ ] Todos os links internos funcionando
- [ ] Links externos abrem em nova aba (`target="_blank"`)
- [ ] Scroll suave funcionando
- [ ] Animações não travam em mobile

### Entrega
- [ ] Pasta organizada e nomeada corretamente
- [ ] README.txt incluído com instruções de hospedagem (Netlify)
- [ ] ZIP da pasta criado para envio

---

## 16. Armadilhas e Como Evitar

| Armadilha | Como Evitar |
|---|---|
| **Scope creep** | Defina explicitamente no gig: "Inclui até X revisões. Mudanças de estrutura fora do escopo acordado têm custo adicional." |
| **Imagens do cliente chegando em baixa resolução** | Adicione na FAQ: "Please provide images at minimum 2000px wide for best results." |
| **Cliente sem ideia de hospedagem** | Inclua guia de 1 página de como subir no Netlify. Isso evita 80% das confusões pós-entrega. |
| **Revisões infinitas** | Especifique o número de rodadas de revisão. "Rodada de revisão = uma lista consolidada de mudanças, não múltiplas mensagens separadas." |
| **Site lento por imagens não comprimidas** | Sempre comprima as imagens de demo antes de entregar. Use squoosh.app. Meta: <200kb por imagem da galeria. |
| **Layout quebrado em Safari** | Teste sempre no Safari (use BrowserStack gratuito). Algumas propriedades CSS se comportam diferente no Safari. |
| **Pedir review de forma invasiva** | Uma mensagem direta e educada ao entregar: "Se o resultado superou suas expectativas, ficaria grato por uma avaliação!" — nunca implore. |
| **Precificar muito baixo** | Abaixo de $120 você atrai clientes de baixa qualidade e cria ancoragem de preço difícil de reverter. Não faça. |

---

## 17. Referências Rápidas de Design

### Snippets de Código Essenciais

**CSS — Dark mode base:**
```css
:root {
  --bg-primary: #0A0A0A;
  --bg-secondary: #111827;
  --text-primary: #F9FAFB;
  --text-secondary: #9CA3AF;
  --accent: #C9A84C;
  --max-width: 1280px;
  --section-padding: clamp(80px, 10vw, 120px);
}

body {
  background-color: var(--bg-primary);
  color: var(--text-primary);
  font-family: 'Inter', sans-serif;
}
```

**JS — Intersection Observer (fade-in ao scroll):**
```javascript
const reveals = document.querySelectorAll('.reveal');
const observer = new IntersectionObserver((entries) => {
  entries.forEach(entry => {
    if (entry.isIntersecting) {
      entry.target.classList.add('visible');
    }
  });
}, { threshold: 0.15 });

reveals.forEach(el => observer.observe(el));
```

**HTML — Formulário Formspree:**
```html
<form action="https://formspree.io/f/SEU_ID_AQUI" method="POST">
  <input type="text" name="name" placeholder="Your name" required>
  <input type="email" name="email" placeholder="Your email" required>
  <select name="project_type">
    <option value="cosmetics">Cosmetics / Beauty</option>
    <option value="fashion">Fashion / Apparel</option>
    <option value="tech">Tech / Electronics</option>
    <option value="food">Food & Beverage</option>
    <option value="other">Other</option>
  </select>
  <textarea name="message" placeholder="Tell me about your project"></textarea>
  <button type="submit">Send Message</button>
</form>
```

### Sites de Referência Visual (inspiração de design)

- **awwwards.com** → busque "photography portfolio"
- **dribbble.com** → busque "product photographer website"
- **onepagelove.com** → portfólios de página única
- **behance.net** → busque "photographer portfolio 2025"

### Ferramentas de Produtividade no Vibe Coding

| Ferramenta | Uso | Custo |
|---|---|---|
| Claude / ChatGPT | Gerar HTML/CSS base, escrever copy | Gratuito/Pago |
| Squoosh.app | Compressão de imagens | Gratuito |
| PageSpeed Insights | Teste de performance | Gratuito |
| BrowserStack | Teste cross-browser | Freemium |
| Loom | Gravar vídeos dos demos | Gratuito até 5min |
| Netlify | Deploy dos demos e projetos finais | Gratuito |
| Formspree | Backend de formulários | Gratuito (50/mês) |

---

## RESUMO EXECUTIVO EM 10 PONTOS

1. **Nicho:** Sites de portfólio para fotógrafos de produto/e-commerce
2. **Cliente ideal:** Fotógrafo freelancer ou pequeno estúdio que atende marcas DTC/Shopify/Amazon
3. **Estética padrão:** Dark mode editorial, tipografia serif+sans, galeria com hover overlay
4. **Stack:** HTML + CSS + Vanilla JS — sem frameworks, sem builders
5. **3 demos fictícios** antes do primeiro gig: cosméticos, moda, tech — cada um visualmente distinto
6. **Preços:** Basic $150 / Standard $320 / Premium $550 — nunca abaixo de $120
7. **Gig Fiverr:** Categoria "Website Design", tag principal "product photographer website"
8. **Primeiras vendas:** Ofereça 2–3 slots a $49–79 para conseguir reviews → suba preços
9. **Diferencial:** Código limpo, velocidade, especialização no nicho de fotografia de produto
10. **90 dias:** Meta de $1.000–2.500/mês até o final do terceiro mês com consistência

---

*Documento criado com base em análise de mercado do Fiverr e indústria fotográfica 2025–2026.*  
*Atualize este documento conforme você aprende com os primeiros clientes reais.*
