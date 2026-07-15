# lucaguerneri.github.io

Teaching materials site. Plain HTML — no build step, no dependencies.

## Structure

```
index.html          homepage, links to the three years
style.css           all styling lives here, one file
year-3/index.html   Third Year
year-4/index.html   Fourth Year
year-5/index.html   Fifth Year
```

Material files (.docx, .pptx, .pdf) go **inside the year folder**, next to that
year's `index.html`. The links in the HTML are plain filenames, so
`year-5/hard-times-handout.docx` is linked simply as `hard-times-handout.docx`.

## Adding a new unit

1. Drop the files into the right year folder.
2. Open that year's `index.html`.
3. Copy an existing `<li class="unit"> … </li>` block, paste it in the right
   chronological position, and change the date, title, description, and links.

That's the whole workflow.

## File naming

Lowercase, hyphens, no spaces, no accents. `hard-times-handout.docx`, never
`Hard Times — Handout (def).docx`. Spaces and accents break URLs.

## What does not go here

Teacher booklets, answer keys, and Fila A/B test papers. This site is public:
anything in the repository is downloadable whether or not it is linked.
