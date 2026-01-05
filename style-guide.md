# Style Guide: Aura Flow

## 1. Tipografia (Typography)
O projeto utiliza três famílias de fontes distintas para criar a hierarquia "Luxo Tecnológico".

### Font Families
* **Display (Títulos):** `Space Grotesk` (Sans-serif)
    * *Uso:* Headlines (H1, H2, H3), Números grandes.
    * *Pesos:* 400, 500, 600, 700.
    * *Class:* `font-display`
* **Body (Corpo):** `Inter` (Sans-serif)
    * *Uso:* Parágrafos, menus, botões, textos longos.
    * *Pesos:* 300, 400, 500, 600.
    * *Class:* `font-body`
* **Accent (Detalhes):** `Playfair Display` (Serif)
    * *Uso:* Palavras de destaque, itálicos em headlines ("Marcas", "Status").
    * *Estilo:* Geralmente usado em *Italic*.
    * *Class:* `font-accent`

---

## 2. Paleta de Cores (Color Palette)
Sistema de cores adaptável para **Dark Mode** (padrão luxo) e **Light Mode**.

### Primary (Gold / Ouro)
Gradientes metálicos usados para CTAs e destaques.
* **Gold (Base):** `#D4AF37` -> `text-primary` / `bg-primary`
* **Gold Light:** `#F2D879` -> `text-primary-light`
* **Gold Dark:** `#B4941F` -> `text-primary-dark`
* **Gold Gradient:** `linear-gradient(135deg, #D4AF37 0%, #F2D879 50%, #B4941F 100%)`
    * *Class:* `bg-gold-gradient` ou `text-gradient-gold`

### Backgrounds (Fundos)
* **Light Mode:**
    * Base: `#F8F9FA` (`bg-background-light`)
    * Surface: `#FFFFFF` (`bg-surface-light`)
* **Dark Mode (Principal):**
    * Base: `#050505` (`bg-background-dark`)
    * Surface: `#111111` (`bg-surface-dark`)
    * Lighter Surface: `#1A1A1A` (`bg-surface-dark-lighter`) - Usado em cards.

### Text (Texto)
* **Light Mode:**
    * Principal: `#1F2937` (`text-text-light`)
    * Muted: `#6B7280` (`text-muted-light`)
* **Dark Mode:**
    * Principal: `#E5E7EB` (`text-text-dark`)
    * Muted: `#9CA3AF` (`text-muted-dark`)

---

## 3. Elementos de UI (UI Components)

### Botões (Buttons)
1.  **Primary (CTA):**
    * Background: `bg-gold-gradient`
    * Text: `text-black` (Preto para contraste no ouro)
    * Shape: `rounded-full`
    * Shadow: `shadow-[0_4px_14px_0_rgba(212,175,55,0.39)]`
2.  **Secondary (Outline):**
    * Border: `border border-gray-300 dark:border-white/20`
    * Hover: `hover:border-primary hover:text-primary`

### Cards (Cartões)
* **Estilo:** Glassmorphism ou Solid Dark.
* **Borda:** Sutil `border border-white/5` ou `border-gray-200`.
* **Border Radius:**
    * Padrão: `rounded-2xl` ou `rounded-3xl`.
* **Hover:** `hover:border-primary/50` (efeito de brilho na borda).

### Inputs (Formulários)
* **Background:** `bg-gray-100` (Light) ou levemente transparente no Dark.
* **Focus:** `focus:ring-2 focus:ring-primary` (Anel dourado ao digitar).
* **Shape:** `rounded-lg`.

---

## 4. Efeitos Especiais (FX)

### Sombras (Glows)
O design utiliza sombras coloridas para simular neon/luz.
* **Gold Glow:** `shadow-[0_0_20px_rgba(212,175,55,0.15)]`
* **Blur de Fundo:** `backdrop-blur-xl` (usado na Navbar).

### Ícones
* **Biblioteca:** Material Icons Outlined
* **Import:** `<link href="https://fonts.googleapis.com/icon?family=Material+Icons+Outlined" rel="stylesheet"/>`
* **Uso:** `<span class="material-icons-outlined">rocket_launch</span>`

### Animações (Tailwind)
* `animate-pulse`: Para backgrounds sutis.
* `animate-ping`: Para notificações/ofertas urgentes.
* `group-hover:translate-x-1`: Setas movendo ao passar o mouse.