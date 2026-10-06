# Borozdov Whiteboard

A theme from the Borozdov collection. Two faces — light **Mist**, deep plum ink on lavender
mist, and dark **Plum**, the same board after hours. A creative studio notebook where the
ink is the fill, lavender draws every edge and one vivid violet marks links.

![Borozdov Whiteboard in light mode](https://raw.githubusercontent.com/borozdov-obsidian-themes/whiteboard/main/screenshots/light.png)

![Borozdov Whiteboard in dark mode](https://raw.githubusercontent.com/borozdov-obsidian-themes/whiteboard/main/screenshots/dark.png)

## Principles

- **Plum is the ink.** A near-black purple is the text, the heading colour, the main
  button, a checked task and a toggle — it carries the brand and the action at once.
  Nothing on the page is neutral grey; every grey leans plum.
- **Lavender draws the edges.** Hairlines, dividers and card rims are lavender mist;
  lavender wash carries tags and the open file; a blush bloom is the highlighter.
- **One vivid violet.** The brightest chromatic in the system marks links and the caret,
  and nothing else.
- **A wide geometric display.** Whiteboard Sans ExtraBold for the title and the two largest
  headings; the platform's own sans for everything else, with small labels tracked far open.

## Features

- Light and dark modes, following Settings → Appearance → Base color scheme
- Callouts as soft-white cards with a lavender hairline and the title in the type's colour
- Tags and property values as lavender pills with plum text
- Floating panels with a plum-tinted lift on the light face
- Quiet editing: no focus ring around the note, its title or form fields while you type;
  property names read as labels, not boxed fields
- Text colours meet WCAG contrast on both faces
- The phone layout keeps the same colours and shapes
- No `!important`: every rule can be overridden with a CSS snippet

## Installation

**From the community directory, as a variant:** this theme ships inside **Borozdov
Palette**. Install Borozdov Palette under Settings → Appearance → Themes → Manage, then
the [Style Settings](https://github.com/mgmeyers/obsidian-style-settings) plugin, and
choose **Whiteboard** under Style Settings → Borozdov Palette → Variant. The variant
brings this theme's palette, type and corners; its own layout, and its embedded font if it
has one, come with the full theme below.

**The full theme, by hand:** download `manifest.json` and `theme.css` from the
[latest release](https://github.com/borozdov-obsidian-themes/whiteboard/releases/latest)
into `<vault>/.obsidian/themes/Borozdov Whiteboard/`, then choose Borozdov Whiteboard under
Settings → Appearance → Themes.

## Font

Whiteboard Sans is embedded in `theme.css` as base64 WOFF2 under the SIL Open Font License
1.1 — see [`fonts/OFL.txt`](fonts/OFL.txt). It is a Latin and Cyrillic subset of Raleway
ExtraBold (© 2010–2013 Matt McInerney, Pablo Impallari, Rodrigo Fuenzalida), renamed because
a modified copy may not use the original's Reserved Font Name. One weight, for the title and
the two largest headings only.

## License

MIT — see [LICENSE](LICENSE).

---

**По-русски.** Тема из коллекции Borozdov. Два лика: светлый «Дымка» — тёмно-сливовые
чернила на лавандовой дымке, и тёмный «Слива» — та же доска после работы. Блокнот творческой
студии, где чернила — это и заливка, лаванда рисует каждую грань, а один яркий фиолетовый
отмечает ссылки. Заголовки — Whiteboard Sans ExtraBold. В каталоге тема живёт вариантом Borozdov Palette: установите Borozdov Palette и плагин Style Settings, затем выберите Whiteboard в Style Settings → Borozdov Palette → Variant. Целиком, со своей вёрсткой, тема ставится вручную из последнего релиза репозитория.
