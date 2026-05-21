# Links e Consultas de Busca no GitHub

Este arquivo compila as consultas avançadas de busca no GitHub abordadas no artigo principal para facilitar a cópia rápida e o acesso direto.

## 1. Localização e Internacionalização (i18n)

### Sem Tradução pt-BR Existente
* **Buscar por pastas/arquivos de locales em inglês que não contenham português:**
  [locales en.json NOT pt-BR](https://github.com/search?q=locales+en.json+NOT+pt-BR&type=code)
  *Query:* `locales en.json NOT pt-BR`

* **Buscar por estruturas i18n em inglês sem correspondente em português:**
  [i18n en.json NOT pt-BR](https://github.com/search?q=i18n+en.json+NOT+pt-BR&type=code)
  *Query:* `i18n en.json NOT pt-BR`

* **Pastas comuns de tradução em geral excluindo pt-BR:**
  [locales OR i18n OR translations OR lang NOT pt-BR](https://github.com/search?q=%28locales+OR+i18n+OR+translations+OR+lang%29+NOT+pt-BR&type=code)
  *Query:* `(locales OR i18n OR translations OR lang) NOT pt-BR`

---

## 2. Projetos Ativos e Abertos a Contribuições

* **Projetos i18n com 50-1000 estrelas e issues ativas de ajuda (`help-wanted`):**
  [Link direto](https://github.com/search?q=%28i18n+OR+localization+OR+translation%29+stars%3A50..1000+pushed%3A%3E2025-01-01+archived%3Afalse+help-wanted-issues%3A%3E0&type=repositories)
  *Query:* `(i18n OR localization OR translation) stars:50..1000 pushed:>2025-01-01 archived:false help-wanted-issues:>0`

* **Projetos i18n com issues amigáveis para iniciantes (`good-first-issue`):**
  [Link direto](https://github.com/search?q=%28i18n+OR+localization+OR+translation%29+stars%3A50..1000+pushed%3A%3E2025-01-01+archived%3Afalse+good-first-issues%3A%3E0&type=repositories)
  *Query:* `(i18n OR localization OR translation) stars:50..1000 pushed:>2025-01-01 archived:false good-first-issues:>0`

---

## 3. Issues Abertas Especificamente de Tradução

* **Issues com label `help wanted` contendo "translation":**
  [Link direto](https://github.com/search?q=is%3Aissue+is%3Aopen+label%3A%22help+wanted%22+translation&type=issues)
  *Query:* `is:issue is:open label:"help wanted" translation`

* **Issues com label `good first issue` e "i18n":**
  [Link direto](https://github.com/search?q=is%3Aissue+is%3Aopen+label%3A%22good+first+issue%22+i18n&type=issues)
  *Query:* `is:issue is:open label:"good first issue" i18n`
