# Prompt para Landing Page Digital Premium

**Crie uma landing page / cartão de visita digital PREMIUM e ultra-profissional para MSS Climatização e Refrigeração usando HTML, CSS e JavaScript vanilla moderno.**

## Identidade Visual e Branding

**Nome da Empresa:** MSS Climatização e Refrigeração
**Segmento:** Climatização Industrial e Refrigeração
**Tagline:** "Profissionais capacitados especialistas em Climatização"

**Paleta de Cores:**
- Azul primário: #0052CC (navy profundo)
- Azul secundário: #0078D4 (azul vibrante)
- Azul claro: #5AB9EA (cyan)
- Branco: #FFFFFF
- Background: #0A1929 (azul escuro para contraste premium)
- Cinza claro: #F5F7FA
- Texto claro: #FFFFFF
- Texto escuro: #1A1A1A

**Elementos Visuais:**
- Engrenagem com floco de neve (símbolo principal)
- Gradientes modernos e vibrantes
- Glassmorphism effects
- Partículas ou flocos de neve animados no background (sutil)
- Ícones: snowflake, gear, thermometer

## Estrutura da Landing Page

**Arquivo Único:** index.html (com CSS e JS inline para facilitar deploy)

**Layout:** Design vertical centralizado, responsivo, com efeitos modernos

### Seções Detalhadas:

**1. Hero Section (Impacto Imediato)**
- Background: Gradiente azul profundo (#0A1929 → #0052CC) com padrão sutil de flocos/engrenagens animados
- Logo MSS centralizada (usar SVG inline se possível)
- Título principal: "MSS Climatização e Refrigeração" 
  * Fonte: Poppins/Montserrat Bold, 48-64px
  * Efeito: Gradiente no texto ou glow sutil
- Subtítulo: "Profissionais Capacitados Especialistas em Climatização"
  * Fonte: Inter/Roboto, 18-24px, opacidade 0.9
- Ícone de floco de neve com animação de rotação suave (CSS animation)
- Efeito parallax sutil no scroll (opcional)

**2. Serviços em Cards Premium**
- 4 cards com glassmorphism effect:
  * Climatização Industrial (ícone: ar condicionado)
  * Refrigeração (ícone: snowflake)
  * Manutenção Preventiva (ícone: tools/gear)
  * Instalação de Dutos (ícone: duct/pipe)
- Cada card:
  * Background: rgba(255, 255, 255, 0.1) com backdrop-filter: blur(10px)
  * Border: 1px solid rgba(255, 255, 255, 0.18)
  * Hover: scale(1.05) + brilho aumentado
  * Padding generoso, border-radius 16px
  * Ícone no topo (font-size: 48px)
  * Título do serviço abaixo

**3. Call-to-Action Section (DESTAQUE MÁXIMO)**
- Background: Gradiente diferente ou card destacado
- Título: "Entre em Contato Agora" (fonte grande e bold)
- Descrição curta: "Solicite um orçamento sem compromisso"

**DOIS BOTÕES PRINCIPAIS (design premium):**

**Botão WhatsApp:**
```css
- Background: Linear gradient(135deg, #25D366, #128C7E)
- Largura: min 280px, padding 20px 40px
- Border-radius: 50px (pill shape)
- Font-size: 18px, font-weight 600
- Ícone WhatsApp à esquerda (usar SVG ou Font Awesome)
- Texto: "💬 Falar no WhatsApp"
- Box-shadow: 0 8px 32px rgba(37, 211, 102, 0.3)
- Hover: 
  * Transform: translateY(-4px) scale(1.02)
  * Box-shadow aumentada
  * Brilho pulsante
- Link: https://wa.me/5521990930825
```

**Botão Email:**
```css
- Background: Linear gradient(135deg, #0078D4, #0052CC)
- Mesmas especificações de tamanho do WhatsApp
- Ícone de envelope à esquerda
- Texto: "✉️ Enviar E-mail"
- Box-shadow: 0 8px 32px rgba(0, 82, 204, 0.3)
- Hover: Mesmos efeitos do WhatsApp
- Link: mailto:comercialmssclimatizacao@gmail.com
```

**Espaçamento:** 24px entre os botões (vertical no mobile, horizontal no desktop)

**Informações de Contato Exibidas:**
```
Abaixo dos botões, em cards pequenos ou lista estilizada:
📞 (21) 99093-0825
📧 comercialmssclimatizacao@gmail.com
```

**4. Footer Elegante**
- Background: rgba(0, 0, 0, 0.3)
- Logo MSS pequena
- Copyright: "© 2025 MSS Climatização e Refrigeração"
- Padding generoso

## Especificações Técnicas Premium

**CSS Moderno (usar técnicas avançadas):**
- CSS Grid e Flexbox para layout
- Custom properties (variáveis CSS) para cores
- Backdrop-filter para glassmorphism
- CSS animations para micro-interações
- Smooth scroll behavior
- Transition timing functions personalizadas (cubic-bezier)

**Animações e Efeitos:**
1. **Fade-in progressivo** ao carregar (usar Intersection Observer)
2. **Partículas de floco de neve** no background (canvas ou CSS puro)
3. **Hover effects** nos botões:
   - Scale + translateY
   - Box-shadow aumentada
   - Pulse sutil no ícone
4. **Scroll reveal** para cards de serviços
5. **Floating animation** sutil no logo/ícone principal
6. **Ripple effect** ao clicar nos botões (opcional)

**Fontes (Google Fonts):**
```html
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@600;700;800&family=Inter:wght@400;500;600&display=swap" rel="stylesheet">
```

**Ícones:**
- Font Awesome CDN ou SVG inline para melhor performance
- Ícones específicos: WhatsApp, envelope, snowflake, gear, tools

**Responsividade Perfeita:**
- Mobile (< 768px):
  * Botões full-width
  * Cards empilhados
  * Fonte reduzida proporcionalmente
  * Padding ajustado
- Tablet (768px - 1024px):
  * 2 colunas para cards
  * Botões podem ficar lado a lado
- Desktop (> 1024px):
  * Max-width: 1200px, centralizado
  * 4 colunas para cards
  * Espaçamento generoso
  * Botões lado a lado

**Performance e Otimização:**
- CSS e JS inline (tudo em um arquivo)
- SVG inline para ícones críticos
- Lazy loading para imagens (se houver)
- Minificar CSS/JS
- Meta tags para compartilhamento (Open Graph)

**Acessibilidade:**
- Contraste WCAG AA ou superior
- Alt text em todas as imagens
- Focus states visíveis
- Semantic HTML (header, main, section, footer)
- ARIA labels quando necessário

## Efeitos Premium Específicos

**Glassmorphism nos Cards:**
```css
background: rgba(255, 255, 255, 0.1);
backdrop-filter: blur(10px);
border: 1px solid rgba(255, 255, 255, 0.18);
box-shadow: 0 8px 32px 0 rgba(31, 38, 135, 0.37);
```

**Gradiente Animado no Background (opcional):**
```css
background: linear-gradient(-45deg, #0A1929, #0052CC, #0078D4, #0A1929);
background-size: 400% 400%;
animation: gradientShift 15s ease infinite;
```

**Partículas/Flocos de Neve:**
- Usar CSS puro ou Canvas JavaScript
- 20-30 partículas pequenas
- Movimento vertical lento
- Opacidade baixa (0.1 - 0.3)
- Diferentes tamanhos e velocidades

## Código Estruturado

**Estrutura do HTML:**
```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MSS Climatização e Refrigeração | Especialistas em HVAC</title>
    <meta name="description" content="Profissionais capacitados em climatização industrial e refrigeração. Orçamento rápido via WhatsApp.">
    <!-- Open Graph para compartilhamento -->
    <meta property="og:title" content="MSS Climatização e Refrigeração">
    <meta property="og:description" content="Especialistas em climatização industrial">
    <style>
        /* TODO: CSS inline aqui */
    </style>
</head>
<body>
    <!-- TODO: Estrutura da página -->
    <script>
        // TODO: JavaScript para animações
    </script>
</body>
</html>
```

## Objetivo Final

Criar uma landing page que seja:
1. **Visualmente impressionante** - Design moderno que "WOW" o visitante
2. **Ultra-profissional** - Transmite confiança e expertise técnica
3. **Conversão otimizada** - Botões impossíveis de ignorar
4. **Performance perfeita** - Carregamento instantâneo
5. **Mobile-first** - Funciona perfeitamente em qualquer dispositivo
6. **Fácil de hospedar** - Um arquivo, deploy em segundos

A página deve ser tão bonita e profissional que pareça ter sido feita por uma agência premium, mas mantendo a simplicidade técnica de HTML/CSS/JS puro.

**Entregue o código completo e funcional, pronto para fazer upload e usar.**