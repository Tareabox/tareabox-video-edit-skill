# tareabox-video-edit (Claude Code Skill)

> ⚠️ **Skill experimental en desarrollo activo.** Herramienta personal creada por Natalie Digital que le pide a Claude Code que instale HyperFrames + el catálogo Tareabox. Cambia constantemente a medida que itero — no es producto final, es un experimento público. 100% comunidad, NO oficial de Heygen ni de Anthropic.

## Qué hace esta skill

Cuando la tenés instalada y le decís a Claude algo como *"haceme un video con tareabox"* o *"instalá hyperframes"*, esta skill le explica a Claude:

1. Cómo instalar **HyperFrames** ([heygen-com/hyperframes](https://github.com/heygen-com/hyperframes)) en el proyecto del usuario
2. Cómo conectar el proyecto al **registry público de Tareabox** ([Tareabox/tareabox-catalog-free](https://github.com/Tareabox/tareabox-catalog-free))
3. Cómo instalar bloques específicos del catálogo (100+ disponibles)
4. Cómo montar el video paso a paso, sin que el usuario tenga que saber código

Ideal para no-developers que quieren hacer videos con templates listos sin tocar HTML.

## Instalación

```bash
# 1. Cloná o descargá este folder
git clone https://github.com/<your-fork>/tareabox-video-edit

# 2. Movelo a tu carpeta de skills de Claude Code
mv tareabox-video-edit ~/.claude/skills/

# 3. Reiniciá Claude Code
```

(O bien, copialo a la carpeta de skills de tu cliente IA preferido.)

## Cómo usarla

Una vez instalada, abrí Claude Code y decile algo como:

- *"Haceme un video con un texto kinético sobre 'productividad'"*
- *"Instalá tareabox en este proyecto"*
- *"Quiero un chat de iMessage animado con estos mensajes"*

Claude va a usar la skill para guiarte paso a paso.

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
