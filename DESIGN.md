# DESIGN.md

Owner-written direction for the `Drenzzz/Drenzzz` profile README. The agent formats; the owner decides.

- **Identity:** playful dev. A builder with a light tone, not a corporate vendor page.
- **Personality:** practical and honest. Tools that do their job and get out of the way.
- **Palette (Tokyo Night, brand reason):** base `#1a1b26`, ink `#c0caf5`, blue `#7aa2f7`, purple `#bb9af7`, green `#9ece6a`, muted body `#a9b1d6`. Kept because it is the owner's existing identity across site and editor, not because dark looks tech. Muted `#565f89` is banned for text (fails WCAG AA at 2.76:1 on base).
- **Typography:** system sans for names and prose (readability first), monospace only for the terminal-voice motif (kicker, proof labels). Never large monospace headings for pure aesthetics.
- **Mood:** calm confidence. One focal point per screen (the name), one deliberate accent (gradient underline under the name), whitespace as structure.
- **Motif:** terminal voice in words, never a fake terminal window. No background grids, no traffic-light dots, no left-stripe decoration.
- **Dial:** ENERGY 2 / RHYTHM 2 / MOTION 1 (README is static; MOTION 1 is the honest value).

## Why log (R-31, one line each)

- Palette stays Tokyo Night: owner-confirmed brand identity.
- Hero is pure typography: fake terminal windows are forbidden (R-05) and the real proof is the repo list. The eyebrow label above the name was cut (R-09: a pill that repeats what the headline says); the right column stays because it carries the flagship repos, not decoration.
- Gradient appears once (name underline): hierarchy separator, not page decoration (R-01).
- About and Featured work mirror the owner's CV: same focus (Go, TypeScript, JavaScript), same five projects, same stack strings. Internship line and the CV's third-person voice are dropped so the README keeps its own voice. The CV's "300+ stars" is not shown; live GitHub numbers are (R-17).
- Hero is a real shell transcript, not a terminal window: the prompt and `whoami` output are the owner's own (`drenzzz@Rozelith /megaproyek/drenzzz main`), Nerd Font glyphs stripped because they render as tofu outside a Nerd Font, and there is no title bar, no traffic-light dots, no panel border, and no fake window chrome. R-05 forbids a fake terminal costume; a genuine prompt from a genuine shell is the owner's own terminal voice, which the DESIGN.md motif already asks for. This is a deliberate, recorded call, not an accident.
- The hero carries no flagship list: the Featured work table below holds the five CV projects with their real stack strings, so repeating them in the hero would only dilute the focal point. Canvas is 420px wide rather than 1200 because SVG is vector and the rendered size is what matters: a 1200px hero on a 360px phone scales the prompt to 6px, while 420px keeps it legible at 0.86x.
- Colour is capped at two hues plus one accent (R-29): blue for `user@host` and the role line, green for `main` and `$` as terminal state markers, ink for the name and command, and the blue-to-purple rule under the name as the single deliberate accent. Both themes clear WCAG AA; the light-theme green is darkened to `#3b8343` because the dark-theme `#9ece6a` only reaches 4.20:1 on white.
- Stack uses one local SVG badge strip with technology icons from thesvg: owner override, colored labels scan faster than icon-only marks for dev peers. All 22 CV skills are present, grouped and ordered as the CV lists them, with a monospace group kicker (the terminal-voice motif). Chip color is the brand color and each label is AA-checked against its chip (lowest 4.53:1, TypeScript on white). Elysia and Fiber ship no mono icon and their marks do not read at badge size; the owner chose to keep them as-is.
- Featured work is a table: owner override, project/what/stack comparison scans faster than prose for recruiters; rows follow the CV order.
- All stats come from live GitHub widgets: no invented numbers (R-17).
