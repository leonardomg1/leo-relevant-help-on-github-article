# Ayuda al mundo en pequeños commits: cómo encontrar proyectos open source que necesitan traducción y apoyo en GitHub

![Ilustración de Open Source Guides sobre contribución open source](https://opensource.guide/assets/images/cards/contribute.png)

> **Una guía práctica de filantropía digital para quienes desean colaborar con proyectos open source, pero aún não sabem por dónde empezar.**

[![GitHub](https://img.shields.io/badge/GitHub-Open%20Source-181717?logo=github)](https://github.com/)
[![Contribuciones](https://img.shields.io/badge/contribuciones-documentación%20%7C%20traducción%20%7C%20i18n-blue)](#formas-sencillas-de-ayudar)
[![Español](https://img.shields.io/badge/idioma-es-red)](#comienza-por-las-traducciones)

<!--
SEO keywords:
cómo contribuir open source, contribuir en GitHub, proyectos open source para ayudar, traducción open source,
GitHub good first issue, help wanted GitHub, i18n GitHub, localization GitHub, filantropía digital,
voluntariado tecnológico, documentación open source
-->

## Una puerta abierta para quienes quieren ayudar

A mucha gente le gustaría **ayudar en proyectos open source**, mas se bloquea ante la misma pregunta: **¿por dónde empiezo?**

Abren GitHub, encuentran miles de repositorios, ven conversaciones técnicas, issues antiguas, branches, pull requests, archivos de configuración, y piensan que tal vez aún no están listos. Pero contribuir con open source no comienza únicamente en el código. También empieza en la **claridad**, la **documentación**, la **traducción**, la **organización** y en la valentía de hacer algo más accesible para otra persona.

Una traducción bien hecha puede permitir que un estudiante entienda una herramienta. Una corrección en un README puede ahorrar horas de frustración. Una issue bien escrita puede ayudar a un mantenedor cansado a localizar un problema real. Un ejemplo sencillo puede transformar un proyecto intimidante en algo utilizable.

Esto también é **filantropía digital**: donar tiempo, atención y conocimiento para ampliar el acceso de otras personas a la tecnología.

## Búsquedas listas para encontrar dónde ayudar

A continuación se presentan búsquedas linkeables en GitHub para encontrar proyectos que tengan indicios de internacionalización, documentación o pedidos de ayuda. La idea no es encontrar cualquier repositorio, sino ubicar lugares donde una pequeña contribución tenga un valor real.

### 1. Proyectos con archivos de idioma pero sin español (es) o portugués (pt-BR)

| Objetivo | Búsqueda |
|---|---|
| Buscar `locales` con inglés y sin `pt-BR` ni `es` | [`locales en.json NOT pt-BR NOT es`](https://github.com/search?q=locales+en.json+NOT+pt-BR+NOT+es&type=code) |
| Buscar `i18n` con inglés y sin `pt-BR` ni `es` | [`i18n en.json NOT pt-BR NOT es`](https://github.com/search?q=i18n+en.json+NOT+pt-BR+NOT+es&type=code) |
| Buscar traducciones al inglés sin español | [`translations en NOT es`](https://github.com/search?q=translations+en+NOT+es&type=code) |
| Buscar carpetas comunes de internacionalización | [`locales OR i18n OR translations OR lang NOT es`](https://github.com/search?q=%28locales+OR+i18n+OR+translations+OR+lang%29+NOT+es&type=code) |
| Buscar proyectos con chino y sin español | [`zh-CN NOT es localization`](https://github.com/search?q=zh-CN+NOT+es+localization&type=code) |

> [!TIP]
> Buscar por `README.es.md` normalmente encuentra proyectos que **ya poseen** traducción al español. Esto puede ser útil para descubrir proyectos que aceptan traducciones, pero no es la mejor búsqueda para encontrar vacíos.

### 2. Proyectos activos, con estrellas y apertura a recibir ayuda

| Objetivo | Búsqueda |
|---|---|
| Proyectos de traducción/i18n con 50 a 1000 estrellas y `help wanted` | [`i18n OR localization OR translation + stars:50..1000 + help-wanted-issues`](https://github.com/search?q=%28i18n+OR+localization+OR+translation%29+stars%3A50..1000+pushed%3A%3E2025-01-01+archived%3Afalse+help-wanted-issues%3A%3E0&type=repositories) |
| Proyectos de traducción/i18n com `good first issue` | [`i18n OR localization OR translation + good-first-issues`](https://github.com/search?q=%28i18n+OR+localization+OR+translation%29+stars%3A50..1000+pushed%3A%3E2025-01-01+archived%3Afalse+good-first-issues%3A%3E0&type=repositories) |
| Proyectos recientes vinculados a documentación | [`documentation + stars:50..1000 + help wanted`](https://github.com/search?q=documentation+stars%3A50..1000+pushed%3A%3E2025-01-01+archived%3Afalse+help-wanted-issues%3A%3E0&type=repositories) |
| Proyectos con tópico de internacionalización | [`topic:i18n + help-wanted-issues`](https://github.com/search?q=topic%3Ai18n+stars%3A50..1000+pushed%3A%3E2025-01-01+archived%3Afalse+help-wanted-issues%3A%3E0&type=repositories) |

### 3. Issues abiertas buscando ayuda

| Objetivo | Búsqueda |
|---|---|
| Issues abiertas de traducción | [`is:issue is:open translation`](https://github.com/search?q=is%3Aissue+is%3Aopen+translation&type=issues) |
| Issues abiertas de localización | [`is:issue is:open localization`](https://github.com/search?q=is%3Aissue+is%3Aopen+localization&type=issues) |
| Issues con `help wanted` y traducción | [`label:"help wanted" translation`](https://github.com/search?q=is%3Aissue+is%3Aopen+label%3A%22help+wanted%22+translation&type=issues) |
| Issues con `good first issue` e i18n | [`label:"good first issue" i18n`](https://github.com/search?q=is%3Aissue+is%3Aopen+label%3A%22good+first+issue%22+i18n&type=issues) |
| Issues sobre español | [`es OR Spanish`](https://github.com/search?q=is%3Aissue+is%3Aopen+%28es+OR+Spanish%29&type=issues) |

## Comienza por las traducciones

La traducción es una de las formas más accesibles de contribuir porque no exige, al principio, un dominio profundo del código. Aún así, exige algo valioso: **cuidado por el otro**.

Traducir un proyecto no es solo convertir palabras. Es acortar la distancia entre una idea y una persona que tal vez no podría acceder a ella. Es permitir que más gente aprenda, pruebe, use, critique y mejore aquello que fue construido.

Puedes ayudar traduciendo:

- `README.md`;
- páginas dentro de `docs/`;
- archivos `locales/*.json`;
- archivos `i18n/*.json`;
- mensajes de interfaz;
- tutoriales;
- ejemplos de uso;
- guías de instalación;
- mensajes de error;
- instrucciones de contribución.

> [!IMPORTANT]
> No comiences traduciendo un proyecto entero sin antes observar el contexto. En comunidades open source, **el respeto al proceso** es tan importante como la buena voluntad.

## Formas sencillas de ayudar

No toda contribución tiene que ser código. Muchos proyectos necesitan ayuda en áreas que suelen quedar olvidadas, pero que marcan una enorme diferencia para nuevos usuarios.

### Mejorar documentación

Una mala documentación aleja a las personas. Una documentación clara las acoge. Puedes ayudar revisando instrucciones, corrigiendo enlaces rotos, mejorando ejemplos y simplificando el primer uso.

### Abrir una issue útil

Una issue útil describe el problema, muestra dónde ocurre, explica cómo reproducirlo y evita acusaciones. Una buena issue le ahorra tiempo a quien mantiene el proyecto.

### Probar instrucciones

Muchos READMEs prometen un paso a paso que ya no funciona. Instalar el proyecto desde cero e informar en qué parte de la instrucción falla es una contribución real.

### Traducir una pequeña parte

Un `README.es.md` inicial, una página en `docs/es/` o un archivo `locales/es.json` ya puede ser suficiente para abrir camino.

### Mejorar ejemplos

Los ejemplos sencillos ayudan a los principiantes. A veces el proyecto tiene una herramienta poderosa, pero ningún ejemplo didáctico para quien va llegando.

## Cómo elegir un buen proyecto

Antes de donar tu tiempo, observa si el proyecto tiene señales de vida y acogida.

Busca:

- commits recientes;
- issues respondidas;
- pull requests revisados;
- archivo `LICENSE`;
- archivo `README.md`;
- archivo `CONTRIBUTING.md`;
- archivo `CODE_OF_CONDUCT.md`;
- etiquetas como `help wanted`, `good first issue`, `documentation`, `translation`, `i18n` o `localization`;
- mantenedores que responden con educación;
- discusiones recientes y constructivas.

Evita comenzar en proyectos abandonados, agresivos, sin licencia o con muchas contribuciones ignoradas. La solidaridad también necesita discernimiento.

## Cómo acercarse sin atropellar el proyecto

Cuando encuentres una oportunidad, empieza pequeño. Lee el README. Busca reglas de contribución. Mira si ya existe una issue abierta. Después, escribe un mensaje sencillo y respetuoso.

### Modelo de issue para ofrecer traducción

```markdown
¡Hola!

Noté que el proyecto posee estructura de internacionalización/documentación,
pero no encontré una traducción al español.

Me gustaría contribuir con una primera traducción pequeña, comenzando por una de estas opciones:

- README.es.md
- una página en docs/es/
- un archivo locales/es.json

¿Aceptan este tipo de contribuciones?
¿Existe algún patrón de traducción o guía que deba seguir?

Gracias por su trabajo en este proyecto.
```

### Modelo de pull request pequeño

```markdown
## Qué se hizo

Agrega una traducción inicial al español.

## Archivos modificados

- README.es.md

## Observaciones

Mantuve el contenido fiel al README original, adaptando solo los términos necesarios
para mayor claridad en español.

## Tipo de contribución

- [x] Documentación
- [x] Traducción
- [ ] Código
```

## Una ruta de 30 minutos

> [!NOTE]
> El objetivo no es hacerlo todo a la vez. El objetivo es encontrar una contribución pequeña, honesta y posible.

1. Abre una de las búsquedas de este artículo.
2. Elige un proyecto activo.
3. Verifica que haya `README.md`, `LICENSE` y alguna actividad reciente.
4. Busca carpetas como `locales/`, `i18n/`, `translations/`, `lang/` o `docs/`.
5. Revisa si ya existe `es`, `Spanish` o `Español`.
6. Confirma si hay issues con `help wanted`, `good first issue`, `translation` o `documentation`.
7. Abre una issue educada o envía un PR pequeño.
8. Agradece cualquier respuesta, incluso si tu contribución necesita ajustes.

## Palabras clave útiles para nuevas búsquedas

Usa estas palabras en GitHub, en motores de búsqueda o en herramientas de curaduría de issues:

| Intención | Palabras clave |
|---|---|
| Encontrar proyectos para ayudar | `open source`, `contribute`, `contributing`, `help wanted`, `good first issue` |
| Encontrar traducción | `translation`, `translations`, `localization`, `i18n`, `locale`, `locales`, `lang` |
| Encontrar español | `es`, `Spanish`, `Español` |
| Encontrar documentación | `documentation`, `docs`, `README`, `tutorial`, `getting started` |
| Encontrar proyectos acogedores | `first timers only`, `beginner friendly`, `new contributors`, `community` |

## El valor humano de una pequeña contribución

El open source está hecho por personas. Personas con tiempo limitado, contextos diferentes, idiomas distintos y niveles diversos de experiencia.

Cuando traduces una página, mejoras una frase, corriges un ejemplo o explicas una instalación, estás ayudando a alguien que tal vez nunca aparezca a agradecerte. Quizá sea un estudiante. Quizá sea una persona en transición de carrera. Quizá sea alguien en otro país, intentando aprender con dificultad. Quizá sea un mantenedor sobrecargado, feliz de que alguien haya cuidado una parte olvidada del proyecto.

La contribución pequeña no es pequeña cuando elimina una barrera.

Un commit puede ser un puente.  
Una traducción puede ser una puerta.  
Una mejor documentación puede ser una invitación.

## Imágenes sugeridas para usar en el repositorio

Las imágenes de abajo son de GitHub Open Source Guides y pueden ayudar a que el repositorio se vea visualmente más acogedor:

- [Imagen sobre contribución open source](https://opensource.guide/assets/images/cards/contribute.png)
- [Imagen sobre comunidad open source](https://opensource.guide/assets/images/cards/building.png)
- [Imagen sobre primeros pasos en open source](https://opensource.guide/assets/images/cards/beginner.png)
- [Imagen sobre encontrar usuarios para proyectos](https://opensource.guide/assets/images/cards/finding.png)

## Beneficio profesional como consecuencia

Este artículo no comenzó hablando de currículums porque la motivación más bonita aquí es otra: **ayudar**.

Pero es verdad que contribuir en open source también puede ser positivo profesionalmente. Con el tiempo, tus contribuciones públicas demuestran comunicación, constancia, cuidado, colaboración, atención a los detalles y capacidad de trabajar en comunidad.

La mejor reputación es aquella que nace como consecuencia de una ayuda real.

## Visite también

Conozca otros proyectos e iniciativas en:

**https://github.com/leonardomg1**

## Referências úteis

- [GitHub Docs — Finding ways to contribute to open source on GitHub](https://docs.github.com/en/get-started/exploring-projects-on-github/finding-ways-to-contribute-to-open-source-on-github)
- [GitHub Docs — Search for repositories](https://docs.github.com/en/search-github/searching-on-github/searching-for-repositories)
- [GitHub Docs — Understanding GitHub Code Search syntax](https://docs.github.com/en/search-github/github-code-search/understanding-github-code-search-syntax)
- [GitHub Docs — Managing labels](https://docs.github.com/en/issues/using-labels-and-milestones-to-track-work/managing-labels)
- [Open Source Guides — How to Contribute to Open Source](https://opensource.guide/how-to-contribute/)
- [GitHub Open Source Guides Repository](https://github.com/github/opensource.guide)
