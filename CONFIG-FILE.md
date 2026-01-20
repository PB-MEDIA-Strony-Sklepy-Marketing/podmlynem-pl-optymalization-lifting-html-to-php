# 📊 PODSUMOWANIE ANALIZY REPOZYTORIUM

## Projekt: podmlynem.pl - Ośrodek Wypoczynkowy "Pod Młynem"

**Typ projektu:** Landing page / Website hotelowy (HTML → PHP conversion)  
**Stack technologiczny:**

- **Frontend:** HTML5, CSS3, JavaScript (jQuery), Bootstrap, Revolution Slider, Owl Carousel
- **Backend:** PHP (czysty, bez CMS/frameworka), PHPMailer
- **Build tools:** Gulp (obecny w vendor)
- **Assets:** Linea Icons, Simple Line Icons, Google Maps API, Google Fonts

**Aktualny stan:**

- Strona działająca na https://www.podmlynem.pl/
- Podstawowa struktura HTML z vendor libraries
- Prosty formularz kontaktowy z reCAPTCHA v3
- Slider Revolution, Owl Carousel dla galerii
- Responsywność podstawowa (wymaga modernizacji)
- SEO basic (wymaga rozbudowy)

**Cel transformacji:**

1. ✨ Modernizacja UI/UX → premium, nowoczesny design
2. 🔄 Konwersja HTML → czysty PHP (bez CMS)
3. 📈 Optymalizacja SEO + pozycjonowanie
4. ⚡ PageSpeed optimization
5. 🎯 Energy Stepper functionality
6. 🔍 Code review + best practices

---

# 📋 KOMPLETNA LISTA PLIKÓW DO WYGENEROWANIA

## PRIORYTET 1️⃣ - DOKUMENTACJA DLA AI (generuj NAJPIERW)

### Główne pliki AI

1. **`AGENTS.md`** - Definicje agentów AI, ich role i workflows
2. **`CLAUDE.md`** - Instrukcje dla Claude AI Projects
3. **`OLLAMA.md`** - Konfiguracja i prompty dla Ollama
4. **`QWEN.md`** - Instrukcje dla Qwen AI Desktop

### Pliki konfiguracyjne AI

5. **`.claude-plugin`** - Plugin configuration dla Claude
6. **`.claude/config.json`** - Claude project settings
7. **`.copilot/instructions.md`** - GitHub Copilot instructions (update)
8. **`copilot-instructions.md`** - Root level Copilot guide
9. **`.cursorrules`** - Cursor IDE rules i conventions

---

## PRIORYTET 2️⃣ - GITHUB WORKFLOWS & ACTIONS

### .github/workflows/

10. **`.github/workflows/ci.yml`** - Continuous Integration (linting, tests)
11. **`.github/workflows/deploy-production.yml`** - Production deployment do /dist
12. **`.github/workflows/deploy-staging.yml`** - Staging deployment
13. **`.github/workflows/html-validation.yml`** - HTML/CSS/JS validation
14. **`.github/workflows/seo-audit.yml`** - Automated SEO checking
15. **`.github/workflows/pagespeed-audit.yml`** - PageSpeed performance tests
16. **`.github/workflows/lighthouse-ci.yml`** - Lighthouse audits
17. **`.github/workflows/security-scan.yml`** - Security vulnerability scan
18. **`.github/workflows/php-syntax-check.yml`** - PHP code validation
19. **`.github/workflows/image-optimization.yml`** - Automated image compression
20. **`.github/workflows/dependency-update.yml`** - Update vendor libraries
21. **`.github/workflows/code-quality.yml`** - Code quality gates
22. **`.github/workflows/backup.yml`** - Automated backups

### .github/ configuration

23. **`.github/dependabot.yml`** - Dependency management
24. **`.github/CODEOWNERS`** - Code ownership
25. **`.github/PULL_REQUEST_TEMPLATE.md`** - PR template
26. **`.github/ISSUE_TEMPLATE/bug_report.md`** - Bug report template
27. **`.github/ISSUE_TEMPLATE/feature_request.md`** - Feature request template
28. **`.github/ISSUE_TEMPLATE/seo_optimization.md`** - SEO task template

---

## PRIORYTET 3️⃣ - DOKUMENTACJA PROJEKTOWA

### /docs/

29. **`docs/ARCHITECTURE.md`** - Architektura projektu (HTML→PHP flow)
30. **`docs/BRAND-SETTINGS.md`** - Brand identity, kolory, czcionki
31. **`docs/DESIGN-SYSTEM.md`** - Design system, komponenty UI
32. **`docs/SEO-STRATEGY.md`** - Strategia SEO i pozycjonowania
33. **`docs/ROADMAP.md`** - Roadmap projektu i milestones
34. **`docs/API-DOCUMENTATION.md`** - API docs (formularze, mailer)
35. **`docs/DEPLOYMENT.md`** - Deployment procedures
36. **`docs/ENERGY-STEPPER.md`** - Dokumentacja Energy Stepper feature
37. **`docs/CONVERSION-GUIDE.md`** - HTML to PHP conversion guide
38. **`docs/TESTING.md`** - Testing strategy and procedures
39. **`docs/PERFORMANCE-OPTIMIZATION.md`** - PageSpeed optimization guide

### README files

40. **`README.md`** - Main project README (update/create)
41. **`docs/README.agents.md`** - Agent documentation index
42. **`docs/README.collections.md`** - Collections documentation
43. **`docs/README.instructions.md`** - Instructions index
44. **`docs/README.prompts.md`** - Prompts library index
45. **`docs/README.skills.md`** - Skills documentation

---

## PRIORYTET 4️⃣ - GITHUB AGENTS & INSTRUCTIONS

### .github/agents/

46. **`.github/agents/frontend-optimizer.agent.md`** - Frontend optimization agent
47. **`.github/agents/seo-specialist.agent.md`** - SEO optimization agent
48. **`.github/agents/php-converter.agent.md`** - HTML→PHP conversion agent
49. **`.github/agents/code-reviewer.agent.md`** - Code review agent
50. **`.github/agents/performance-tester.agent.md`** - Performance testing agent

### .github/instructions/

51. **`.github/instructions/html-to-php-conversion.instructions.md`** - HTML→PHP steps
52. **`.github/instructions/seo-optimization.instructions.md`** - SEO workflows
53. **`.github/instructions/frontend-modernization.instructions.md`** - UI/UX updates
54. **`.github/instructions/deployment.instructions.md`** - Deployment procedures
55. **`.github/instructions/testing.instructions.md`** - Testing guidelines
56. **`.github/instructions/code-review.instructions.md`** - Review checklist

### .github/prompts/

57. **`.github/prompts/frontend-design.prompt.md`** - Frontend design prompts
58. **`.github/prompts/seo-content.prompt.md`** - SEO content generation
59. **`.github/prompts/php-refactoring.prompt.md`** - PHP refactoring prompts
60. **`.github/prompts/performance-audit.prompt.md`** - Performance analysis
61. **`.github/prompts/accessibility.prompt.md`** - WCAG compliance prompts

### .github/prompt-snippets/

62. **`.github/prompt-snippets/seo-meta-tags.snippet.md`** - SEO meta snippets
63. **`.github/prompt-snippets/schema-markup.snippet.md`** - Schema.org snippets
64. **`.github/prompt-snippets/php-templates.snippet.md`** - PHP template snippets
65. **`.github/prompt-snippets/css-modern.snippet.md`** - Modern CSS patterns

### .github/chatmodes/

66. **`.github/chatmodes/seo-mode.chatmode.md`** - SEO focused chat mode
67. **`.github/chatmodes/development-mode.chatmode.md`** - Development chat mode
68. **`.github/chatmodes/review-mode.chatmode.md`** - Code review mode

### .github/knowledge/

69. **`.github/knowledge/podmlynem-brand.knowledge.md`** - Brand knowledge base
70. **`.github/knowledge/seo-keywords.knowledge.md`** - SEO keywords database
71. **`.github/knowledge/php-best-practices.knowledge.md`** - PHP patterns
72. **`.github/knowledge/hotel-industry.knowledge.md`** - Hotel/turystyka insights

### .github/mcp/

73. **`.github/mcp/php-server.mcp.json`** - PHP MCP server config
74. **`.github/mcp/seo-tools.mcp.json`** - SEO tools MCP config
75. **`.github/mcp/image-optimizer.mcp.json`** - Image optimization MCP

---

## PRIORYTET 5️⃣ - BUILD & DEVELOPMENT TOOLS

### Root configuration files

76. **`package.json`** - NPM dependencies i scripts
77. **`gulpfile.js`** - Gulp build tasks (update existing)
78. **`webpack.config.js`** - Webpack bundling configuration
79. **`.npmrc`** - NPM configuration
80. **`.nvmrc`** - Node version specification
81. **`composer.json`** - PHP dependencies (optional)

### Docker & containerization

82. **`docker-compose.yml`** - Docker development environment
83. **`Dockerfile`** - PHP/Apache container
84. **`.dockerignore`** - Docker ignore patterns
85. **`docker/nginx/nginx.conf`** - Nginx config (alternative)
86. **`docker/php/php.ini`** - PHP configuration

### MCP Configuration

87. **`mcp.json`** - MCP servers registry
88. **`.mcp/servers.json`** - MCP servers detailed config

---

## PRIORYTET 6️⃣ - CODE QUALITY & TESTING

### Linting & Formatting

89. **`.eslintrc.json`** - ESLint configuration
90. **`.prettierrc`** - Prettier code formatting
91. **`.stylelintrc.json`** - CSS/SCSS linting
92. **`.editorconfig`** - Editor configuration
93. **`phpcs.xml`** - PHP Code Sniffer rules
94. **`.php-cs-fixer.php`** - PHP CS Fixer config

### Testing

95. **`phpunit.xml`** - PHPUnit test configuration
96. **`tests/Unit/MailerTest.php`** - PHPMailer unit tests
97. **`tests/Integration/FormTest.php`** - Form integration tests
98. **`tests/e2e/ContactFormE2E.spec.js`** - End-to-end tests (Playwright)
99. **`playwright.config.js`** - Playwright configuration
100. **`jest.config.js`** - Jest testing framework

### Pre-commit hooks

101. **`.pre-commit-config.yaml`** - Pre-commit hooks
102. **`.husky/pre-commit`** - Husky pre-commit hook
103. **`.husky/pre-push`** - Husky pre-push validation

---

## PRIORYTET 7️⃣ - SEO & CONTENT TEMPLATES

### /templates/

104. **`templates/meta-tags-template.html`** - Meta tags master template
105. **`templates/schema-markup-hotel.json`** - Schema.org Hotel/LocalBusiness
106. **`templates/schema-markup-breadcrumb.json`** - Breadcrumb schema
107. **`templates/schema-markup-review.json`** - Review/Rating schema
108. **`templates/opengraph-template.html`** - OpenGraph meta template
109. **`templates/twitter-card-template.html`** - Twitter Card template
110. **`templates/sitemap-template.xml`** - XML sitemap template
111. **`templates/robots-template.txt`** - robots.txt template
112. **`templates/htaccess-security.txt`** - .htaccess security rules
113. **`templates/htaccess-seo.txt`** - .htaccess SEO optimizations
114. **`templates/blog-post-template.md`** - Blog post content template
115. **`templates/php-header-template.php`** - PHP header component
116. **`templates/php-footer-template.php`** - PHP footer component
117. **`templates/php-navigation-template.php`** - PHP navigation template
118. **`templates/php-contact-form-template.php`** - Form template

---

## PRIORYTET 8️⃣ - COLLECTIONS & PROMPTS LIBRARY

### /collections/

119. **`collections/seo-prompts.collection.md`** - SEO prompts collection
120. **`collections/design-patterns.collection.md`** - UI/UX patterns
121. **`collections/php-snippets.collection.md`** - PHP code snippets
122. **`collections/css-utilities.collection.md`** - CSS utility classes
123. **`collections/js-helpers.collection.md`** - JavaScript helpers
124. **`collections/accessibility-checks.collection.md`** - A11y checklist
125. **`collections/performance-tips.collection.md`** - Performance optimization

### /prompts/ (update existing)

126. **`prompts/seo-content-generator.prompt.md`** - SEO content creation
127. **`prompts/image-alt-generator.prompt.md`** - Alt text generation
128. **`prompts/meta-description-generator.prompt.md`** - Meta descriptions
129. **`prompts/heading-optimizer.prompt.md`** - H1-H6 optimization
130. **`prompts/internal-linking.prompt.md`** - Internal linking strategy
131. **`prompts/keyword-research.prompt.md`** - Keyword research prompts

---

## PRIORYTET 9️⃣ - VS CODE & IDE CONFIGURATION

### .vscode/

132. **`.vscode/settings.json`** - VS Code workspace settings
133. **`.vscode/extensions.json`** - Recommended extensions
134. **`.vscode/tasks.json`** - Build tasks
135. **`.vscode/launch.json`** - Debug configurations
136. **`.vscode/snippets/php.code-snippets`** - PHP snippets
137. **`.vscode/snippets/html.code-snippets`** - HTML snippets
138. **`.vscode/snippets/javascript.code-snippets`** - JS snippets

---

## PRIORYTET 🔟 - SCHEMAS & VALIDATION

### /.schemas/

139. **`.schemas/mcp-server-schema.json`** - MCP server JSON schema
140. **`.schemas/agent-schema.json`** - Agent definition schema
141. **`.schemas/prompt-schema.json`** - Prompt template schema
142. **`.schemas/instruction-schema.json`** - Instruction file schema
143. **`.schemas/package-schema.json`** - Package.json validation

---

## PRIORYTET 1️⃣1️⃣ - DEPLOYMENT & INFRASTRUCTURE

### Deployment scripts

144. **`scripts/deploy-production.sh`** - Production deployment script
145. **`scripts/deploy-staging.sh`** - Staging deployment script
146. **`scripts/build.sh`** - Build automation script
147. **`scripts/optimize-images.sh`** - Image optimization script
148. **`scripts/generate-sitemap.php`** - Dynamic sitemap generator
149. **`scripts/minify-assets.sh`** - CSS/JS minification
150. **`scripts/backup.sh`** - Backup automation
151. **`scripts/setup-dev.sh`** - Development environment setup
152. **`scripts/test.sh`** - Run all tests

### Makefile

153. **`Makefile`** - Build automation commands

---

## PRIORYTET 1️⃣2️⃣ - GIT & VERSION CONTROL

### Git configuration

154. **`.gitignore`** - Git ignore patterns (update)
155. **`.gitattributes`** - Git attributes
156. **`.gitmessage`** - Commit message template

---

## PRIORYTET 1️⃣3️⃣ - SECURITY & COMPLIANCE

### Security files

157. **`SECURITY.md`** - Security policy
158. **`.snyk`** - Snyk security configuration
159. **`security/csp-policy.txt`** - Content Security Policy
160. **`security/cors-config.txt`** - CORS configuration

---

## PRIORYTET 1️⃣4️⃣ - LICENSE & LEGAL

161. **`LICENSE`** - Project license
162. **`CONTRIBUTING.md`** - Contribution guidelines
163. **`CODE_OF_CONDUCT.md`** - Code of conduct

---

## PRIORYTET 1️⃣5️⃣ - CHANGELOG & VERSIONING

164. **`CHANGELOG.md`** - Project changelog
165. **`.versionrc`** - Version bump configuration

---

## PRIORYTET 1️⃣6️⃣ - CONTENT & TEXT FILES

### /text/ (content source files)

166. **`text/homepage-content.txt`** - Homepage copy source
167. **`text/about-content.txt`** - O firmie content
168. **`text/contact-content.txt`** - Kontakt page content
169. **`text/seo-keywords.txt`** - SEO keywords database
170. **`text/meta-descriptions.txt`** - All meta descriptions
171. **`text/alt-texts.txt`** - Image alt text database

---

## PRIORYTET 1️⃣7️⃣ - ENGLISH TRANSLATIONS (jeśli potrzebne)

### /eng/

172. **`eng/README.md`** - English README
173. **`eng/ARCHITECTURE.md`** - Architecture docs (EN)
174. **`eng/CONTRIBUTING.md`** - Contributing guide (EN)

---

## PRIORYTET 1️⃣8️⃣ - SPECIFIC PROJECT FILES

### Energy Stepper Feature

175. **`src/js/energy-stepper.js`** - Energy Stepper implementation
176. **`src/css/energy-stepper.css`** - Energy Stepper styles
177. **`docs/energy-stepper-api.md`** - Energy Stepper API docs

### PHP Conversion

178. **`src/php/config.php`** - PHP configuration
179. **`src/php/database.php`** - Database connection (if needed)
180. **`src/php/helpers.php`** - PHP helper functions
181. **`src/php/includes/header.php`** - Header include
182. **`src/php/includes/footer.php`** - Footer include
183. **`src/php/includes/navigation.php`** - Navigation include
184. **`src/php/contact-handler.php`** - Contact form handler

### SEO Files

185. **`dist/sitemap.xml`** - XML sitemap
186. **`dist/robots.txt`** - Robots.txt
187. **`dist/.htaccess`** - Apache configuration
188. **`dist/humans.txt`** - Humans.txt file

---

## PRIORYTET 1️⃣9️⃣ - MONITORING & ANALYTICS

189. **`monitoring/lighthouse-config.js`** - Lighthouse CI config
190. **`monitoring/sentry-config.js`** - Sentry error tracking
191. **`analytics/gtm-config.js`** - Google Tag Manager setup

---

## PRIORYTET 2️⃣0️⃣ - ADDITIONAL CONFIGURATIONS

### Performance

192. **`.browserslistrc`** - Supported browsers
193. **`imagemin.config.js`** - Image optimization config
194. **`critical.config.js`** - Critical CSS config

### Utility

195. **`.env.example`** - Environment variables template
196. **`.env.development`** - Dev environment
197. **`.env.production`** - Production environment

---

# 📊 PODSUMOWANIE STATYSTYK

**Łączna liczba plików do wygenerowania: 197**

**Podział według kategorii:**

- 🤖 AI & Agents: 25 plików
- ⚙️ GitHub Workflows & Actions: 22 pliki
- 📖 Dokumentacja: 27 plików
- 🔧 Build & Development: 21 plików
- ✅ Testing & Quality: 15 plików
- 🎯 SEO & Templates: 31 plików
- 💻 IDE & Editor: 8 plików
- 🚀 Deployment: 12 plików
- 🔒 Security: 8 plików
- 📝 Content: 10 plików
- 🌐 Internationalization: 3 pliki
- 📊 Monitoring: 6 plików
- ⚡ Performance: 9 plików

---

**Czy chcesz, abym teraz wygenerował pełną zawartość tych plików w kolejności priorytetów? Zacznę od PRIORYTET 1️⃣ (AI Documentation) i będę kontynuował przez wszystkie kategorie.**
