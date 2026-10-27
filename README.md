# Andreas Nøhr: tools site

Plain HTML and CSS, no build step. Open any `.html` file in a browser to see it.

## Files to publish

```
index.html  contact.html  404.html  README.md
tools/index.html  tools/zookeeper.html
assets/css/style.css
assets/img/*
```

Do **not** upload `zookeeper/` (the Unity package source), the `Andreas Nøhr*.htm` / `*_files` folders
(saved Squarespace pages), `SITEMAP.md`, `CLAUDE.md` or `.claude/`.

## Edit

- Colours, font and spacing: the variables at the top of `assets/css/style.css`.
- Header, nav and footer are copied into every page. Change one, change them all.
- Purple is only for ZooKeeper: `class="zookeeper"` on a page or card switches the accent to purple.
- Add a tool: copy `tools/zookeeper.html`, edit it, add a card to `tools/index.html`.
- Asset Store link: search `zookeeper.html` for `TODO`.

## Publish on GitHub Pages

1. On github.com: **New repository**. Name it `andreas-nohr` (or `username.github.io` for a root address). Public. No README/licence.
2. **Add file > Upload files**. Open the `upload_to_github` folder, select everything inside it (not the folder itself) and drag it in. **Commit changes**.
3. **Settings > Pages**. Source: **Deploy from a branch**. Branch: `main`, folder `/ (root)`. Save.
4. After a minute the site is at `https://username.github.io/andreas-nohr/`.
5. Give that address (or a custom domain under Settings > Pages) to the Unity Asset Store as your publisher website.

Updating: upload the changed file again with the same name and commit.
