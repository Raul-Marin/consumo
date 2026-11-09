# Consumo design system import

Source: Raul-Marin/consumo, main, commit 744c7f334f9bd5b902f6f52b8db2ce3e45dff56c.
Read through the connected GitHub account. No local folder was accessed in this continuation.

## Imported files
- app/globals.css: complete 596-line style block from public/index.html, unchanged. Includes all 15 named colors, 3 remote font faces, type sizes, spacing, radii, family/density selectors, responsive rules, hover/focus/disabled styles, shimmer, and reduced-motion support. No CSS imports or Tailwind configuration exist in the source.
- package.json: source manifest, formatting normalized. The source start script refers to server.js, which is intentionally not imported into this design file.
- design-system/source-tokens.json: source default variables, family/density option names, and light/dark palette presets extracted from source JavaScript.

## Canvas coverage
Design System page: colors, typography, spacing/radius/motion, original inline SVGs, buttons/disabled state, segmented controls, font field and color controls, status/plan badges, feedback, usage card, meter tones, history folds, list row, chart, loading state, theme editor, settings, and a representative account selection page.

The source has zero React component exports. Component coverage is 0 of 0; no synthetic components were created. Original class-based UI is documented as editable HTML examples rather than registered React components.

## Assets
All three font URLs were preserved in @font-face. They remain externally hosted rather than copied locally. Source SVG paths for Cursor, Claude, Codex, theme, settings, drag handle, and the Shift+R footer mark are retained on canvas. No images are referenced by the UI. docs/cover.png is a repository documentation image and was not imported.

## Adaptations and omissions
Source classes and CSS variables are used for samples. Scaffold-only layout uses inline geometry because the source does not use Tailwind. HTML class attributes were converted to className, SVG attribute names to JSX spelling, and field values to defaultValue where required.

The account page uses the source's ready-session copy, account hints, logos, layout, and control order. All three accounts are shown selected. Runtime probe details were replaced by their source account hints. Usage numbers and chart history are labeled sample data. Backend account detection, authentication/session access, API calls, localStorage, refresh timers, drag behavior, theme switching, and Google Fonts search logic were not executed or ported. Presets are documented; controls are static. Server code and configuration are not design assets.

## Verification
Confirmed imported CSS variables and font declarations through project reads. Confirmed no component exports in the source tree or destination registry. Visually checked the complete reference page and the account screen through canvas screenshots. Colors, source fonts, icons, borders, spacing, chart, and page layout render. No missing UI image assets were reported.

## GitHub export
The exported styles.css contains the imported source styles. The Lunagraph-only import of its empty styles.css was removed. source-tokens.json contains the extracted variables and presets. This folder documents the design; the editable canvas remains in Lunagraph.
