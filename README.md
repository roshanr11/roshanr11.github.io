# roshanr11.github.io

Personal academic website for Roshan Ram, served by GitHub Pages at https://roshanr11.github.io.

It is a single static page with no build step:

- `index.html`: all content (about, papers, experience, writing, fun facts)
- `style.css`: styles, with light and dark themes
- `assets/img/`: profile photo and favicons

## Common edits

- **Substack:** set `SUBSTACK_URL` near the bottom of `index.html`. While it is empty, the Substack link and the Writing section stay hidden.
- **New paper:** copy one `<li class="paper">` block in `index.html`. Write the full author list; "Roshan Ram" is bolded automatically, and lists longer than six names collapse behind a "+N more" button.
- **Photo:** replace `assets/img/roshan_pfp.jpeg` (square images work best).
