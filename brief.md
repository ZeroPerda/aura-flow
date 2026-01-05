# Project Brief: Aura Flow

## 1. Informações Principais
* **Nome da Empresa:** Aura Flow
* **Indústria:** Marketing Digital, SEO e Branding (Agência de Performance)
* **Localização:** Brasil (Atuação Digital/Global)
* **Idioma:** Português (BR)

## 2. Definição do Produto
* **O que estamos construindo?**
    * Uma Landing Page de alta conversão para uma agência de marketing digital premium. O design transmite autoridade, luxo e tecnologia.
* **Para quem é? (Público-Alvo)**
    * Donos de empresas, startups e prestadores de serviços que querem escalar suas vendas online e sentem que seu posicionamento atual é amador. Eles valorizam estética refinada e resultados (ROI).
* **Qual é o objetivo? (Call to Action)**
    * Objetivo Primário: Preenchimento do formulário de "Fale com um Especialista" ou contato via WhatsApp.
    * Objetivo Secundário: Construção de autoridade através de portfólio e prova social (números/resultados).

## 3. Requisitos Tecnológicos (Setup "Antigravity")
* **Framework:** Vanilla HTML5 + JavaScript (ES6).
* **Estilização:** TailwindCSS (via CDN `script src`) para estilização rápida.
* **Configuração Tailwind:** Customização no `<script>` para incluir as cores da marca (Primary Gold: `#D4AF37`) e fontes customizadas.
* **Backend:** Nenhum (Site Estático) ou Supabase (caso decida armazenar os leads do formulário futuramente).
* **Deploy:** Google Stitch / Hospedagem Estática.
* **Restrições:** Tudo deve rodar em um único `index.html` (ou estrutura simples de pasta) sem build steps complexos (sem npm/yarn).

## 4. Visão Geral das Seções (Estrutura Atual)
A página segue esta ordem lógica de conversão:

1.  **Top Bar (Oferta):**
    * Faixa fixa no topo com contagem regressiva visual ou oferta relâmpago ("Desconto Massivo na Criação de Site").
    * *Tech:* Z-index alto, animação de `ping`.

2.  **Navigation Bar (Sticky):**
    * Logo "AF" (Aura Flow) com efeito de brilho.
    * Links de navegação (Serviços, Processo, Portfólio, Sobre).
    * Botão CTA "Começar Agora" com gradiente dourado.
    * Toggle de Modo Claro/Escuro (Dark/Light Mode).

3.  **Hero Section (Impacto):**
    * Headline forte: "Construímos Marcas que Dominam o Mercado".
    * Subheadline focada em dor/solução (visibilidade e conversão).
    * Botões duplos: "Fale com um Especialista" e "Ver Projetos".
    * Prova Social visual: Avatares de clientes + Rating 5 estrelas.
    * *Visual:* Background com elementos flutuantes e Dashboard 3D sugerindo crescimento (+400%).

4.  **Stats Bar (Prova Lógica):**
    * Grid com dados rápidos: ROI (4x), Prazo (2 sem), Clientes (120+), Suporte (24/7).
    * *Visual:* Glassmorphism (fundo translúcido).

5.  **Serviços (O que entregamos):**
    * Cards interativos com ícones grandes e numeração (01, 02, 03).
    * 1. Branding & UI/UX.
    * 2. Web Development (Destaque "Popular").
    * 3. SEO & GMB (Google Meu Negócio).

6.  **Processo (Jornada do Cliente):**
    * Linha do tempo passo-a-passo: Descoberta -> Design -> Lançamento.
    * Imagem de equipe trabalhando com barra de progresso visual ("Em Dia").

7.  **Portfólio (Cases de Sucesso):**
    * Grid de projetos recentes com imagens de alta qualidade.
    * Tags de categoria (Gaming, E-commerce, Corporate, SaaS).
    * Efeito de hover revelando detalhes.

8.  **Liderança (Sobre Nós):**
    * Apresentação dos sócios (CEO e Head de Design) para humanizar a agência ("Carlos Mendes" e "Ana Silva").
    * Citações de autoridade.

9.  **Contato (Conversão Final):**
    * Informações de Email e Telefone.
    * Formulário completo (Nome, Email, Interesse, Mensagem).
    * *Visual:* Card flutuante sobre o mapa/fundo.

10. **Footer:**
    * Copyright, Redes Sociais e repetição do Logo.

## 5. Design & Vibe (Moodboard)
* **Estilo Visual:** "Luxury Tech". Uso de fundos escuros (Dark Mode), texturas de fibra de carbono, efeitos de vidro (blur) e iluminação neon/dourada.
* **Paleta de Cores:**
    * **Primária:** Gold (`#D4AF37`, `#F2D879`, `#B4941F`) - Gradientes metálicos.
    * **Fundo:** Dark (`#050505`, `#111111`) e Light (`#F8F9FA`).
* **Tipografia:**
    * Títulos: *Space Grotesk* (Tecnológico/Moderno).
    * Corpo: *Inter* (Legibilidade).
    * Detalhes/Acentos: *Playfair Display* (Itálico para elegância).
* **Tom de Voz:** Confiante, direto, profissional, mas agressivo em vendas ("Dominar o mercado", "Simples assim").

## 6. Requisitos Adicionais
* **Responsividade:** O site deve funcionar perfeitamente em Desktop, Tablet e Mobile.
* **Performance:** Imagens otimizadas e código limpo para carregamento rápido (SEO).
* **Interatividade:** Hover effects nos botões, animações suaves de entrada e transição de cores.