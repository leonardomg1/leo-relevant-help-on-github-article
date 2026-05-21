# Ajude o mundo em pequenos commits: como encontrar projetos open source que precisam de tradução e apoio no GitHub

![Ilustração do Open Source Guides sobre contribuição open source](https://opensource.guide/assets/images/cards/contribute.png)

> **Um guia prático de filantropia digital para quem quer ajudar projetos open source, mas ainda não sabe por onde começar.**

[![GitHub](https://img.shields.io/badge/GitHub-Open%20Source-181717?logo=github)](https://github.com/)
[![Contribuições](https://img.shields.io/badge/contribuições-documentação%20%7C%20tradução%20%7C%20i18n-blue)](#formas-simples-de-ajudar)
[![Português do Brasil](https://img.shields.io/badge/idioma-pt--BR-green)](#comece-pelas-traduções)

<!--
SEO keywords:
como contribuir open source, contribuir no GitHub, projetos open source para ajudar, tradução open source,
GitHub good first issue, help wanted GitHub, i18n GitHub, localization GitHub, pt-BR open source,
filantropia digital, voluntariado tecnológico, documentação open source
-->

## Uma porta aberta para quem quer ajudar

Muita gente gostaria de **ajudar projetos open source**, mas trava diante da mesma pergunta: **por onde começo?**

A pessoa abre o GitHub, encontra milhares de repositórios, vê conversas técnicas, issues antigas, branches, pull requests, arquivos de configuração, e pensa que talvez ainda não esteja pronta. Mas contribuir com open source não começa apenas no código. Também começa na **clareza**, na **documentação**, na **tradução**, na **organização** e na coragem de tornar algo mais acessível para outra pessoa.

Uma tradução bem feita pode permitir que um estudante entenda uma ferramenta. Uma correção em um README pode economizar horas de frustração. Uma issue bem escrita pode ajudar um mantenedor cansado a localizar um problema real. Um exemplo simples pode transformar um projeto intimidante em algo utilizável.

Isso também é **filantropia digital**: doar tempo, atenção e conhecimento para ampliar o acesso de outras pessoas à tecnologia.

## Pesquisas prontas para encontrar onde ajudar

Abaixo estão buscas linkáveis no GitHub para encontrar projetos que tenham sinais de internacionalização, documentação ou pedidos de ajuda. A ideia não é encontrar qualquer repositório, mas encontrar lugares onde uma contribuição pequena possa ter valor real.

### 1. Projetos com arquivos de idioma, mas sem pt-BR aparente

| Objetivo | Busca |
|---|---|
| Procurar `locales` com inglês e sem `pt-BR` | [`locales en.json NOT pt-BR`](https://github.com/search?q=locales+en.json+NOT+pt-BR&type=code) |
| Procurar `i18n` com inglês e sem `pt-BR` | [`i18n en.json NOT pt-BR`](https://github.com/search?q=i18n+en.json+NOT+pt-BR&type=code) |
| Procurar traduções em inglês sem português | [`translations en NOT pt-BR`](https://github.com/search?q=translations+en+NOT+pt-BR&type=code) |
| Procurar pastas comuns de internacionalização | [`locales OR i18n OR translations OR lang NOT pt-BR`](https://github.com/search?q=%28locales+OR+i18n+OR+translations+OR+lang%29+NOT+pt-BR&type=code) |
| Procurar projetos com chinês e sem pt-BR | [`zh-CN NOT pt-BR localization`](https://github.com/search?q=zh-CN+NOT+pt-BR+localization&type=code) |

> [!TIP]
> Procurar por `README.pt-BR.md` normalmente encontra projetos que **já possuem** tradução para português brasileiro. Isso pode ser útil para descobrir projetos que aceitam traduções, mas não é a melhor busca para encontrar lacunas.

### 2. Projetos ativos, com estrelas e abertura para ajuda

| Objetivo | Busca |
|---|---|
| Projetos de tradução/i18n com 50 a 1000 estrelas e `help wanted` | [`i18n OR localization OR translation + stars:50..1000 + help-wanted-issues`](https://github.com/search?q=%28i18n+OR+localization+OR+translation%29+stars%3A50..1000+pushed%3A%3E2025-01-01+archived%3Afalse+help-wanted-issues%3A%3E0&type=repositories) |
| Projetos de tradução/i18n com `good first issue` | [`i18n OR localization OR translation + good-first-issues`](https://github.com/search?q=%28i18n+OR+localization+OR+translation%29+stars%3A50..1000+pushed%3A%3E2025-01-01+archived%3Afalse+good-first-issues%3A%3E0&type=repositories) |
| Projetos recentes ligados a documentação | [`documentation + stars:50..1000 + help wanted`](https://github.com/search?q=documentation+stars%3A50..1000+pushed%3A%3E2025-01-01+archived%3Afalse+help-wanted-issues%3A%3E0&type=repositories) |
| Projetos com tópico de internacionalização | [`topic:i18n + help-wanted-issues`](https://github.com/search?q=topic%3Ai18n+stars%3A50..1000+pushed%3A%3E2025-01-01+archived%3Afalse+help-wanted-issues%3A%3E0&type=repositories) |

### 3. Issues abertas procurando ajuda

| Objetivo | Busca |
|---|---|
| Issues abertas de tradução | [`is:issue is:open translation`](https://github.com/search?q=is%3Aissue+is%3Aopen+translation&type=issues) |
| Issues abertas de localização | [`is:issue is:open localization`](https://github.com/search?q=is%3Aissue+is%3Aopen+localization&type=issues) |
| Issues com `help wanted` e tradução | [`label:"help wanted" translation`](https://github.com/search?q=is%3Aissue+is%3Aopen+label%3A%22help+wanted%22+translation&type=issues) |
| Issues com `good first issue` e i18n | [`label:"good first issue" i18n`](https://github.com/search?q=is%3Aissue+is%3Aopen+label%3A%22good+first+issue%22+i18n&type=issues) |
| Issues sobre português brasileiro | [`pt-BR OR "Brazilian Portuguese"`](https://github.com/search?q=is%3Aissue+is%3Aopen+%28pt-BR+OR+%22Brazilian+Portuguese%22%29&type=issues) |

## Comece pelas traduções

A tradução é uma das formas mais acessíveis de contribuir porque não exige, no início, domínio profundo do código. Ainda assim, ela exige algo precioso: **cuidado com o outro**.

Traduzir um projeto não é apenas converter palavras. É reduzir a distância entre uma ideia e uma pessoa que talvez não pudesse acessá-la. É permitir que mais gente aprenda, teste, use, critique e melhore aquilo que foi construído.

Você pode ajudar traduzindo:

- `README.md`;
- páginas dentro de `docs/`;
- arquivos `locales/*.json`;
- arquivos `i18n/*.json`;
- mensagens de interface;
- tutoriais;
- exemplos de uso;
- guias de instalação;
- mensagens de erro;
- instruções de contribuição.

> [!IMPORTANT]
> Não comece traduzindo um projeto inteiro sem observar o contexto. Em comunidades open source, **respeito ao processo** é tão importante quanto a boa vontade.

## Formas simples de ajudar

Nem toda contribuição precisa ser código. Muitos projetos precisam de ajuda em áreas que costumam ficar esquecidas, mas que fazem enorme diferença para novos usuários.

### Melhorar documentação

Documentação ruim afasta pessoas. Documentação clara acolhe. Você pode ajudar revisando instruções, corrigindo links quebrados, melhorando exemplos e deixando o primeiro uso mais simples.

### Abrir uma issue útil

Uma issue útil descreve o problema, mostra onde ele acontece, explica como reproduzir e evita acusações. Uma boa issue economiza tempo de quem mantém o projeto.

### Testar instruções

Muitos READMEs prometem um passo a passo que já não funciona. Instalar o projeto do zero e relatar onde a instrução falha é uma contribuição real.

### Traduzir uma pequena parte

Um `README.pt-BR.md` inicial, uma página em `docs/pt-BR/` ou um arquivo `locales/pt-BR.json` já pode ser suficiente para abrir caminho.

### Melhorar exemplos

Exemplos simples ajudam pessoas iniciantes. Às vezes o projeto tem uma ferramenta poderosa, mas nenhum exemplo didático para quem está chegando.

## Como escolher um bom projeto

Antes de doar seu tempo, observe se o projeto tem sinais de vida e acolhimento.

Procure por:

- commits recentes;
- issues respondidas;
- pull requests revisados;
- arquivo `LICENSE`;
- arquivo `README.md`;
- arquivo `CONTRIBUTING.md`;
- arquivo `CODE_OF_CONDUCT.md`;
- labels como `help wanted`, `good first issue`, `documentation`, `translation`, `i18n` ou `localization`;
- mantenedores que respondem com educação;
- discussões recentes e construtivas.

Evite começar por projetos abandonados, agressivos, sem licença ou com muitas contribuições ignoradas. Solidariedade também precisa de discernimento.

## Como se aproximar sem atropelar o projeto

Quando encontrar uma oportunidade, comece pequeno. Leia o README. Procure regras de contribuição. Veja se já existe uma issue aberta. Depois, escreva uma mensagem simples e respeitosa.

### Modelo de issue para oferecer tradução

```markdown
Olá!

Percebi que o projeto possui estrutura de internacionalização/documentação,
mas não encontrei uma tradução para português brasileiro.

Gostaria de contribuir com uma primeira tradução pequena, começando por uma destas opções:

- README.pt-BR.md
- uma página em docs/pt-BR/
- um arquivo locales/pt-BR.json

Vocês aceitam esse tipo de contribuição?
Existe algum padrão de tradução ou guia que eu deva seguir?

Obrigado pelo trabalho de vocês neste projeto.
```

### Modelo de pull request pequeno

```markdown
## O que foi feito

Adiciona uma tradução inicial para português brasileiro.

## Arquivos alterados

- README.pt-BR.md

## Observações

Mantive o conteúdo fiel ao README original, adaptando apenas termos necessários
para clareza em português brasileiro.

## Tipo de contribuição

- [x] Documentação
- [x] Tradução
- [ ] Código
```

## Um roteiro de 30 minutos

> [!NOTE]
> O objetivo não é fazer tudo de uma vez. O objetivo é encontrar uma contribuição pequena, honesta e possível.

1. Abra uma das buscas deste artigo.
2. Escolha um projeto ativo.
3. Verifique se há `README.md`, `LICENSE` e alguma atividade recente.
4. Procure pastas como `locales/`, `i18n/`, `translations/`, `lang/` ou `docs/`.
5. Veja se já existe `pt-BR`, `Portuguese` ou `Brazilian Portuguese`.
6. Confira se há issues com `help wanted`, `good first issue`, `translation` ou `documentation`.
7. Abra uma issue educada ou envie um PR pequeno.
8. Agradeça qualquer retorno, mesmo se a contribuição precisar de ajustes.

## Palavras-chave úteis para novas buscas

Use estas palavras no GitHub, em mecanismos de busca ou em ferramentas de curadoria de issues:

| Intenção | Palavras-chave |
|---|---|
| Encontrar projetos para ajudar | `open source`, `contribute`, `contributing`, `help wanted`, `good first issue` |
| Encontrar tradução | `translation`, `translations`, `localization`, `i18n`, `locale`, `locales`, `lang` |
| Encontrar português brasileiro | `pt-BR`, `Brazilian Portuguese`, `Portuguese Brazil`, `Português Brasileiro` |
| Encontrar documentação | `documentation`, `docs`, `README`, `tutorial`, `getting started` |
| Encontrar projetos acolhedores | `first timers only`, `beginner friendly`, `new contributors`, `community` |

## O valor humano de uma pequena contribuição

Open source é feito por pessoas. Pessoas com tempo limitado, contextos diferentes, idiomas diferentes e níveis diferentes de experiência.

Quando você traduz uma página, melhora uma frase, corrige um exemplo ou explica uma instalação, você está ajudando alguém que talvez nunca apareça para agradecer. Talvez seja um estudante. Talvez seja uma pessoa em transição de carreira. Talvez seja alguém em outro país, tentando aprender com dificuldade. Talvez seja um mantenedor sobrecarregado, feliz por alguém ter cuidado de uma parte esquecida do projeto.

A contribuição pequena não é pequena quando ela remove uma barreira.

Um commit pode ser uma ponte.  
Uma tradução pode ser uma porta.  
Uma documentação melhor pode ser um convite.

## Imagens sugeridas para usar no repositório

As imagens abaixo são do GitHub Open Source Guides e podem ajudar a deixar o repositório visualmente mais acolhedor:

- [Imagem sobre contribuição open source](https://opensource.guide/assets/images/cards/contribute.png)
- [Imagem sobre comunidade open source](https://opensource.guide/assets/images/cards/building.png)
- [Imagem sobre primeiros passos em open source](https://opensource.guide/assets/images/cards/beginner.png)
- [Imagem sobre encontrar usuários para projetos](https://opensource.guide/assets/images/cards/finding.png)

## Benefício profissional como consequência

Este artigo não começou falando de currículo porque a motivação mais bonita aqui é outra: **ajudar**.

But é verdade que contribuir com open source também pode ser positivo profissionalmente. Com o tempo, suas contribuições públicas mostram comunicação, constância, cuidado, colaboração, atenção a detalhes e capacidade de trabalhar em comunidade.

A melhor reputação é aquela que nasce como consequência de uma ajuda real.

## Visite também

Conheça outros projetos e iniciativas em:

**https://github.com/leonardomg1**

## Referências úteis

- [GitHub Docs — Finding ways to contribute to open source on GitHub](https://docs.github.com/en/get-started/exploring-projects-on-github/finding-ways-to-contribute-to-open-source-on-github)
- [GitHub Docs — Search for repositories](https://docs.github.com/en/search-github/searching-on-github/searching-for-repositories)
- [GitHub Docs — Understanding GitHub Code Search syntax](https://docs.github.com/en/search-github/github-code-search/understanding-github-code-search-syntax)
- [GitHub Docs — Managing labels](https://docs.github.com/en/issues/using-labels-and-milestones-to-track-work/managing-labels)
- [Open Source Guides — How to Contribute to Open Source](https://opensource.guide/how-to-contribute/)
- [GitHub Open Source Guides Repository](https://github.com/github/opensource.guide)
