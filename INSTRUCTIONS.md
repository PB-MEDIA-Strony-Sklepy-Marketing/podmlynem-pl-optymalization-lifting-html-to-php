# PROJECT INSTRUCTIONS: Modernization "Pod Młynem"

## 1. ROLE & CONTEXT

**Role:** Senior Fullstack Web Developer (AI Agent).
**Project:** Modernization of vacation homes website "Domy wypoczynkowe Pod Młynem" (https://podmlynem.pl/).
**Goal:** Transform existing HTML/PHP into a premium, mobile-first, high-performance web application using modern PHP, Tailwind CSS, and optimized assets.
**Language:** Polish (PL).
**Brand:** Premium, Nature, Relaxation, Eco-Health.

## 2. TECH STACK & VERSIONS

- **Backend:** PHP 8.5+ (Modular structure: `header.php`, `footer.php`, `components/`).
- **Styling:** Tailwind CSS (Latest v3.4+) via CDN or Build Process (prefer Build for production).
- **Frameworks:** Bootstrap 5.3+ (Only if necessary for grid compatibility, otherwise prioritize Tailwind).
- **Animations:** AOS (Animate On Scroll) - Latest version.
- **Icons:** Google Material Design Icons (Font/Material Symbols).
- **Fonts:** Google Fonts (Premium selection: e.g., 'Playfair Display' for headers, 'Lato' for body).
- **Images:** Unsplash (Direct links), Format: AVIF/WebP with JPG fallback.
- **Environment:** Linux Mint, Docker Compose, Git Bash.
- **Version Control:** Git, GitHub Repository.

## 3. DESIGN & UI/UX GUIDELINES

- **Style:** Premium, Modern, Dynamic.
- **Mobile-First:** All CSS must be written mobile-first, scaling up to desktop.
- **Effects:**
  - Smooth Scroll (`html { scroll-behavior: smooth; }`).
  - Parallax backgrounds on key sections.
  - Hover effects on buttons, cards, and images (scale, shadow, brightness).
  - Gradients & Animated Backgrounds for premium feel.
  - Transitions: `transition-all duration-300 ease-in-out`.
- **Components:** Modular blocks (Shortcodes/Includes) for reusability.
- **Navigation:** Sticky Header on scroll.
- **Breadcrumbs:** Enabled on all subpages, **disabled** on Home Page.

## 4. CONTENT & SEO STRATEGY

- **Copywriting:** SEO-optimized, extensive text content, keywords saturated (natural flow).
- **Meta Tags:** Unique Title, Description, Keywords per page.
- **Open Graph:** Full OG tags for social sharing (Facebook, LinkedIn).
- **Schema.org:** JSON-LD structured data (LocalBusiness, LodgingBusiness).
- **Accessibility:** All images must have `alt` attributes. ARIA labels for interactive elements.
- **Links:** Fetch and validate all internal/external URLs.

## 5. PERFORMANCE & OPTIMIZATION

- **Lighthouse Score:** Target 90+ (Mobile & Desktop).
- **Images:** Lazy loading (`loading="lazy"`), `srcset` for responsiveness, AVIF format.
- **Assets:** Minify CSS/JS, defer non-critical JS.
- **Code:** DRY principle, modular PHP, no inline styles (use Tailwind classes).
- **Caching:** Implement browser caching headers in PHP/Apache/Nginx config.

## 6. SITE STRUCTURE & NAVIGATION

**Menu Items (Sticky):**

1. Strona Główna
2. O firmie
3. Cennik - Oferta pobytu
4. Galeria
5. Kontakt
6. Program prozdrowotny
7. Polityka Prywatności & RODO
8. Przyjęcia
9. FAQ & Pytania

**Footer:** Contact info, Social links, Quick links, Copyright.

## 7. SPECIFIC PAGE REQUIREMENTS

### 7.1. Home Page (`index.php`)

- **Hero Section:** Premium Slider (Full width, high-res Unsplash images, overlay text, CTA).
- **No Breadcrumbs.**
- **Sections:** Intro, Offers Preview, Gallery Preview, Testimonials, CTA.

### 7.2. Program Prozdrowotny (`program-prozdrowotny.php`)

- **Theme:** "Podążaj szlakiem nagród z energostepperem".
- **Key Features:**
  - Eco-friendly energy generation (lighting via stepper).
  - Microclimate benefits (immunity).
  - Wholegrain flour from own mill (fiber, digestion).
  - Firm dishes (grain soup, "sakwa młynarza").
  - Integration fun in the mill.
- **Design:** Highlighted section, distinct background pattern, interactive elements showing energy generation.

### 7.3. Contact (`kontakt.php`)

- **Data:**
  - Address: ul. Bobrownicka 56, 57-330 Szczytna k/Polanicy Zdr.
  - Email: osrodek@podmlynem.pl
  - Phone: +48 512 855 062, (74) 868 30 21
- **Map:** Google Maps embed.
- **Form:** Secure contact form (PHP validation, sanitization).

## 8. WORKFLOW & QA

1. **Plan:** Generate file structure tree before coding.
2. **Code:** Write type-safe, error-handled PHP (early returns, guard clauses).
3. **Test:** Validate HTML/CSS, check mobile responsiveness, test Lighthouse.
4. **Git:** Commit changes with descriptive messages.
5. **Debug:** Check PHP syntax errors, console logs, broken links.

## 9. ASSET LINKS (REFERENCE)

- **AOS:** `https://michalsnik.github.io/aos/`
- **Material Icons:** `https://fonts.google.com/icons`
- **Google Fonts:** `https://fonts.google.com/`
- **Unsplash:** `https://unsplash.com/`
- **Tailwind:** `https://github.com/tailwindlabs/tailwindcss`
- **Repo:** `https://github.com/PB-MEDIA-Strony-Sklepy-Marketing/podmlynem-pl-optymalization-lifting-html-to-php`

## 10. EXECUTION RULES

- **No Theory:** Provide implementation steps and code only.
- **Security:** Sanitize all PHP inputs (`htmlspecialchars`, `filter_input`).
- **Error Handling:** Custom error pages (404, 500).
- **Consistency:** Use `:root` CSS variables for brand colors in global CSS only.
- **Iteration:** Work in modules. Complete one section before moving to the next.

---

**END OF INSTRUCTIONS**
