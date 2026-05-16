# vibeloom-projects

Small static projects prepared for `vibeloom.io` style uploads and simple Vercel deployment.

## Projects

| Folder | Name | Type | Summary |
|---|---|---|---|
| `neon-snake/` | Neon Snake | Game | Neon arcade snake with local best score |
| `gravity-flip/` | Gravity Flip | Game | One-button gravity runner |
| `palette-thief/` | Palette Thief | Design Tool | Extract and explore image palettes |
| `readme-generator/` | README Generator | Web Tool | Fill-in UI for generating README content |
| `typing-boss-fight/` | Typing Boss Fight | Game | 60-second typing battle with combo and boss phases |
| `mood-board-maker/` | Mood Board Maker | Design Tool | Outfit and room mood board generator with vibe presets |

## Stack

- Vanilla `HTML/CSS/JS`
- No build step
- No backend dependency
- Ready to deploy as static sites on Vercel

## Vercel Deployment

Deploy each folder as its own project:

1. Import this repository into Vercel.
2. Create one Vercel project per app folder.
3. Set `Root Directory` to the target folder.
4. Keep framework preset as `Other` or static.
5. Deploy.

Example root directories:

- `typing-boss-fight`
- `mood-board-maker`
- `gravity-flip`
- `neon-snake`

## Notes

- Each app is self-contained in a single `index.html`.
- `localStorage` is used for lightweight persistence in supported projects.
