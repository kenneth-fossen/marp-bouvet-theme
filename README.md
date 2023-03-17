# Marp Theme for Bouvet

## Resources

[Marp.app](https://marp.app)

[Marp - Vscode](https://marketplace.visualstudio.com/items?itemName=marp-team.marp-vscode)

[Marp Github](https://github.com/marp-team/marp)

## Guide for creating themes

[Marp - How to create a theme](https://github.com/marp-team/marp/discussions/115)

## Todo

- [x] Create CSS Frontpage
- [ ] Create CSS Header for Bovuet
- [x] Use correct font
- [x] Pagination
  Shows the number of slides left (1/2). It can be turned off.

## Definition of Done

- [ ] Users can create a presentation similar to the official Bouvet presentation template.

## Bugs

- Small background line at the front page
- Missing logo on Second slide and out

## How to use

- Install the Marp VSCode extension.
- Open settings
  - Find `Marp for VSCode`
  - `Markdown: Marp: Themes` add the following URL:
  - https://raw.githubusercontent.com/kenneth-fossen/marp-bouvet-theme/main/theme.css

## Create presentations

Create a Markdown file ending in `.md` and add this to the file and you can use the Bouvet template in Marp.

```markdown
---
marp: true
theme: bouvet
---
<!-- _class: lead -->

# PRESENTASJONS-MAL

---
```