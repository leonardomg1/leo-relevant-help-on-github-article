# Help the World in Small Commits: How to Find Open Source Projects That Need Translation and Support on GitHub

![Open Source Guides illustration about open source contribution](https://opensource.guide/assets/images/cards/contribute.png)

> **A practical guide to digital philanthropy for anyone who wants to help open source projects, but doesn't know where to start.**

[![GitHub](https://img.shields.io/badge/GitHub-Open%20Source-181717?logo=github)](https://github.com/)
[![Contributions](https://img.shields.io/badge/contributions-documentation%20%7C%20translation%20%7C%20i18n-blue)](#simple-ways-to-help)
[![English](https://img.shields.io/badge/language-English-blue)](#start-with-translations)

<!--
SEO keywords:
how to contribute open source, contribute on GitHub, open source projects to help, open source translation,
GitHub good first issue, help wanted GitHub, i18n GitHub, localization GitHub, digital philanthropy,
technological volunteering, open source documentation
-->

## An open door for anyone who wants to help

Many people would like to **help open source projects**, but get stuck on the same question: **where do I start?**

A person opens GitHub, finds thousands of repositories, sees technical discussions, old issues, branches, pull requests, configuration files, and thinks they might not be ready yet. But contributing to open source doesn't only start with code. It also starts with **clarity**, **documentation**, **translation**, **organization**, and the courage to make something more accessible for someone else.

A well-done translation can allow a student to understand a tool. A fix in a README can save hours of frustration. A well-written issue can help a tired maintainer locate a real problem. A simple example can transform an intimidating project into something usable.

This is also **digital philanthropy**: donating time, attention, and knowledge to expand other people's access to technology.

## Pre-configured searches to find where to help

Below are linkable searches on GitHub to find projects showing signs of internationalization, documentation, or requests for help. The idea is not to find just any repository, but to locate places where a small contribution can make a real difference.

### 1. Projects with translation files but no Brazilian Portuguese (pt-BR)

| Goal | Search Link |
|---|---|
| Search for `locales` with English but without `pt-BR` | [`locales en.json NOT pt-BR`](https://github.com/search?q=locales+en.json+NOT+pt-BR&type=code) |
| Search for `i18n` with English but without `pt-BR` | [`i18n en.json NOT pt-BR`](https://github.com/search?q=i18n+en.json+NOT+pt-BR&type=code) |
| Search for English translations without Portuguese | [`translations en NOT pt-BR`](https://github.com/search?q=translations+en+NOT+pt-BR&type=code) |
| Search for common internationalization folders | [`locales OR i18n OR translations OR lang NOT pt-BR`](https://github.com/search?q=%28locales+OR+i18n+OR+translations+OR+lang%29+NOT+pt-BR&type=code) |
| Search for projects with Chinese but without pt-BR | [`zh-CN NOT pt-BR localization`](https://github.com/search?q=zh-CN+NOT+pt-BR+localization&type=code) |

> [!TIP]
> Searching for `README.pt-BR.md` usually finds projects that **already have** a translation into Brazilian Portuguese. This can be useful for discovering projects that accept translations, but it is not the best search to locate gaps.

### 2. Active projects with stars and open to help

| Goal | Search Link |
|---|---|
| Translation/i18n projects with 50 to 1000 stars and `help wanted` | [`i18n OR localization OR translation + stars:50..1000 + help-wanted-issues`](https://github.com/search?q=%28i18n+OR+localization+OR+translation%29+stars%3A50..1000+pushed%3A%3E2025-01-01+archived%3Afalse+help-wanted-issues%3A%3E0&type=repositories) |
| Translation/i18n projects with `good first issue` | [`i18n OR localization OR translation + good-first-issues`](https://github.com/search?q=%28i18n+OR+localization+OR+translation%29+stars%3A50..1000+pushed%3A%3E2025-01-01+archived%3Afalse+good-first-issues%3A%3E0&type=repositories) |
| Recent projects related to documentation | [`documentation + stars:50..1000 + help wanted`](https://github.com/search?q=documentation+stars%3A50..1000+pushed%3A%3E2025-01-01+archived%3Afalse+help-wanted-issues%3A%3E0&type=repositories) |
| Projects with the internationalization topic | [`topic:i18n + help-wanted-issues`](https://github.com/search?q=topic%3Ai18n+stars%3A50..1000+pushed%3A%3E2025-01-01+archived%3Afalse+help-wanted-issues%3A%3E0&type=repositories) |

### 3. Open issues looking for help

| Goal | Search Link |
|---|---|
| Open translation issues | [`is:issue is:open translation`](https://github.com/search?q=is%3Aissue+is%3Aopen+translation&type=issues) |
| Open localization issues | [`is:issue is:open localization`](https://github.com/search?q=is%3Aissue+is%3Aopen+localization&type=issues) |
| Issues with `help wanted` and translation | [`label:"help wanted" translation`](https://github.com/search?q=is%3Aissue+is%3Aopen+label%3A%22help+wanted%22+translation&type=issues) |
| Issues with `good first issue` and i18n | [`label:"good first issue" i18n`](https://github.com/search?q=is%3Aissue+is%3Aopen+label%3A%22good+first+issue%22+i18n&type=issues) |
| Issues about Brazilian Portuguese | [`pt-BR OR "Brazilian Portuguese"`](https://github.com/search?q=is%3Aissue+is%3Aopen+%28pt-BR+OR+%22Brazilian+Portuguese%22%29&type=issues) |

## Start with translations

Translation is one of the most accessible ways to contribute because it doesn't initially require a deep understanding of code. Still, it demands something precious: **caring for others**.

Translating a project is not just converting words. It is reducing the distance between an idea and a person who might not otherwise access it. It allows more people to learn, test, use, critique, and improve what has been built.

You can help by translating:

- `README.md`;
- pages inside `docs/`;
- `locales/*.json` files;
- `i18n/*.json` files;
- UI strings;
- tutorials;
- usage examples;
- installation guides;
- error messages;
- contribution instructions.

> [!IMPORTANT]
> Do not start translating an entire project without observing the context. In open source communities, **respecting the process** is just as important as good intentions.

## Simple ways to help

Not all contributions need to be code. Many projects need help in areas that are often forgotten but make a huge difference for new users.

### Improve documentation

Poor documentation drives people away. Clear documentation welcomes them. You can help by reviewing instructions, fixing broken links, improving examples, and simplifying first-time use.

### Open a useful issue

A useful issue describes the problem, shows where it happens, explains how to reproduce it, and avoids blame. A good issue saves a lot of time for the project maintainers.

### Test instructions

Many READMEs promise a step-by-step installation that no longer works. Installing the project from scratch and reporting where the instructions fail is a genuine contribution.

### Translate a small part

An initial `README.pt-BR.md`, a single page in `docs/pt-BR/`, or a `locales/pt-BR.json` file is often enough to pave the way.

### Improve examples

Simple examples help beginners. Sometimes a project has a powerful tool but lacks friendly examples for newcomers.

## How to choose a good project

Before donating your time, check if the project shows signs of life and welcoming.

Look for:

- recent commits;
- answered issues;
- reviewed pull requests;
- a `LICENSE` file;
- a `README.md` file;
- a `CONTRIBUTING.md` file;
- a `CODE_OF_CONDUCT.md` file;
- labels like `help wanted`, `good first issue`, `documentation`, `translation`, `i18n`, or `localization`;
- maintainers who respond politely;
- recent and constructive discussions.

Avoid starting with projects that are abandoned, hostile, unlicensed, or ignore contributions. Solidarity also requires discernment.

## How to approach without stepping on toes

When you find an opportunity, start small. Read the README. Look for contribution guidelines. Check if an issue is already open. Then, write a simple and respectful message.

### Issue template to offer translation

```markdown
Hello!

I noticed that the project has an internationalization/documentation structure,
but I couldn't find a translation for Brazilian Portuguese.

I would love to contribute with an initial small translation, starting with one of these options:

- README.pt-BR.md
- a page in docs/pt-BR/
- a locales/pt-BR.json file

Do you accept this type of contribution?
Is there a translation style guide or standard I should follow?

Thank you for your hard work on this project.
```

### Small pull request template

```markdown
## What was done

Adds an initial translation for Brazilian Portuguese.

## Modified files

- README.pt-BR.md

## Notes

Kept the content faithful to the original README, adapting only necessary terms
for clarity in Brazilian Portuguese.

## Type of contribution

- [x] Documentation
- [x] Translation
- [ ] Code
```

## A 30-minute roadmap

> [!NOTE]
> The goal is not to do everything at once. The goal is to find a small, honest, and achievable contribution.

1. Open one of the searches in this article.
2. Choose an active project.
3. Verify there is a `README.md`, `LICENSE`, and recent activity.
4. Look for folders like `locales/`, `i18n/`, `translations/`, `lang/`, or `docs/`.
5. Check if `pt-BR`, `Portuguese`, or `Brazilian Portuguese` already exists.
6. Check for issues with `help wanted`, `good first issue`, `translation`, or `documentation`.
7. Open a polite issue or submit a small PR.
8. Be grateful for any feedback, even if your contribution needs adjustments.

## Useful keywords for new searches

Use these words on GitHub, in search engines, or in issue curation tools:

| Intent | Keywords |
|---|---|
| Find projects to help | `open source`, `contribute`, `contributing`, `help wanted`, `good first issue` |
| Find translation | `translation`, `translations`, `localization`, `i18n`, `locale`, `locales`, `lang` |
| Find Brazilian Portuguese | `pt-BR`, `Brazilian Portuguese`, `Portuguese Brazil`, `Português Brasileiro` |
| Find documentation | `documentation`, `docs`, `README`, `tutorial`, `getting started` |
| Find welcoming projects | `first timers only`, `beginner friendly`, `new contributors`, `community` |

## The human value of a small contribution

Open source is built by people. People with limited time, different backgrounds, different languages, and different levels of experience.

When you translate a page, improve a sentence, fix an example, or explain an installation, you are helping someone who might never appear to thank you. Maybe it's a student. Maybe it's someone transitioning careers. Maybe it's someone in another country, struggling to learn. Maybe it's an overworked maintainer, happy that someone took care of a forgotten part of the project.

A small contribution is not small when it removes a barrier.

A commit can be a bridge.  
A translation can be a door.  
Better documentation can be an invitation.

## Suggested images to use in the repository

The images below are from GitHub's Open Source Guides and can help make the repository look visually welcoming:

- [Image about open source contribution](https://opensource.guide/assets/images/cards/contribute.png)
- [Image about open source community](https://opensource.guide/assets/images/cards/building.png)
- [Image about first steps in open source](https://opensource.guide/assets/images/cards/beginner.png)
- [Image about finding users for projects](https://opensource.guide/assets/images/cards/finding.png)

## Professional benefit as a result

This article didn't start by talking about resumes because the most beautiful motivation here is different: **to help**.

But it's true that contributing to open source can also be positive professionally. Over time, your public contributions show communication, consistency, care, collaboration, attention to detail, and the ability to work in a community.

The best reputation is the one that is born as a consequence of real help.

## Visit also

Learn about other projects and initiatives at:

**https://github.com/leonardomg1**

## Useful references

- [GitHub Docs — Finding ways to contribute to open source on GitHub](https://docs.github.com/en/get-started/exploring-projects-on-github/finding-ways-to-contribute-to-open-source-on-github)
- [GitHub Docs — Search for repositories](https://docs.github.com/en/search-github/searching-on-github/searching-for-repositories)
- [GitHub Docs — Understanding GitHub Code Search syntax](https://docs.github.com/en/search-github/github-code-search/understanding-github-code-search-syntax)
- [GitHub Docs — Managing labels](https://docs.github.com/en/issues/using-labels-and-milestones-to-track-work/managing-labels)
- [Open Source Guides — How to Contribute to Open Source](https://opensource.guide/how-to-contribute/)
- [GitHub Open Source Guides Repository](https://github.com/github/opensource.guide)
