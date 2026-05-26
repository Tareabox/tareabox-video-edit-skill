# tareabox-video-edit (Claude Code Skill)

> ⚠️ **Skill experimental en desarrollo activo.** Set de instrucciones para IA creado por Natalie Digital que ayuda a instalar HyperFrames + el catálogo Tareabox. Funciona con **cualquier IA que entienda markdown** (Claude Code, Cursor, Cline, Codex, ChatGPT, etc). Cambia constantemente a medida que itero — no es producto final, es un experimento público. 100% comunidad, NO oficial de Heygen ni de Anthropic.

## Qué hace esta skill

Cuando tu IA tiene esta skill cargada y le decís algo como *"haceme un video con tareabox"* o *"instalá hyperframes"*, la skill le explica a la IA:

1. Cómo instalar **HyperFrames** ([heygen-com/hyperframes](https://github.com/heygen-com/hyperframes)) en el proyecto del usuario
2. Cómo conectar el proyecto al **registry público de Tareabox** ([Tareabox/tareabox-catalog-free](https://github.com/Tareabox/tareabox-catalog-free))
3. Cómo instalar bloques específicos del catálogo (100+ disponibles)
4. Cómo montar el video paso a paso, sin que el usuario tenga que saber código

Ideal para no-developers que quieren hacer videos con templates listos sin tocar HTML.

## Instalación

Esta skill es un archivo markdown — funciona con **cualquier IA que pueda leer instrucciones**: Claude Code, Cursor, Cline, Codex, Aider, Continue, ChatGPT, etc. Cada herramienta tiene su propia forma de cargarlo, pero la IA misma sabe cómo usarlo una vez que tiene acceso.

```bash
git clone https://github.com/Tareabox/tareabox-video-edit-skill
```

Después, dependiendo de tu IDE / cliente IA:

- **Claude Code:** copialo a `~/.claude/skills/tareabox-video-edit/` y reiniciá
- **Cualquier otra IA:** abrí `SKILL.md` y pegalo en el system prompt / rules / context de tu IDE, o simplemente arrastralo al chat. La IA va a entender qué hacer.

Si no estás seguro cómo, pegále esto a tu IA: *"Tomá las instrucciones de este SKILL.md como tus reglas para esta sesión"* — la IA se encarga del resto.

## Cómo usarla

Una vez instalada, abrí tu IDE/IA preferida y decile algo como:

- *"Haceme un video con un texto kinético sobre 'productividad'"*
- *"Instalá tareabox en este proyecto"*
- *"Quiero un chat de iMessage animado con estos mensajes"*

La IA va a usar la skill para guiarte paso a paso, en tu idioma.

## Disclaimer

- ⚠️ **Experimental + en desarrollo activo** — cambia frecuentemente, no es producción
- 🔄 **Puede romper backward compat** entre versiones sin warning
- 🚫 **No me hago responsable** si algo no anda como esperás
- 🚫 **No tengo obligación de dar soporte** o aceptar PRs (aunque sugerencias son bienvenidas)
- ⚖️ HyperFrames es marca registrada de **Heygen Inc.** — soy **aficionada, no afiliada** 😄
- ⚖️ Tareabox Catalog se distribuye bajo su propia licencia (ver el repo del catálogo)
- ⚖️ Esta skill se distribuye bajo MIT (ver [LICENSE](LICENSE))

## Créditos

- **HyperFrames** — framework Apache 2.0 by [Heygen](https://github.com/heygen-com/hyperframes)
- **Tareabox catalog** — 100+ blocks by [Natalie Digital](https://github.com/Tareabox/tareabox-catalog-free)
- **Claude Code** — by Anthropic

Made with ❤️ by [Natalie Digital](https://nataliedigital.com) · [tareabox.com](https://tareabox.com)
