# Website — workflow

This is the source for [www.mveng.fyi](https://www.mveng.fyi), the MVeng
landing page (Jekyll + Chirpy theme). Unlike `blog`, this isn't a feed of
dated posts — it's one evolving page (hero, about, now, expertise, writing,
contact) plus a couple of nav tabs, and it's this repo's root that Jekyll
builds from directly (no `docs/` subfolder).

## Layout

```
website/
├── index.md            the actual live page content (layout: page) — hero,
│                          about, now, expertise, writing, contact sections
├── content.md           gitignored scratch notes — raw updates, corrections,
│                          things to add or cut, ahead of getting Claude
│                          involved. Never published, never committed.
├── _tabs/                nav tabs (currently just blog.md, which redirects
│                          to the external blog — see site.blog_url below)
├── assets/
│   ├── css/                theme override (jekyll-theme-chirpy.scss)
│   └── img/                logo.svg, etc.
├── _config.yml           site config — url, blog_url, theme settings
├── CNAME                 custom domain (www.mveng.fyi)
└── Gemfile               Jekyll + Chirpy gem, at repo root (this is where
                             `bundle exec jekyll serve` runs from)
```

## Workflow

1. **Jot the update.** Add whatever's changing to `content.md` in rough
   form — new background info, something to correct, a section to cut.
   It's gitignored on purpose: it's a local Dropbox-only scratch pad, not
   part of the site, so there's no pressure to write it cleanly.

   Same two habits as the blog's staging notes are worth keeping here:
   - **Flag TBDs instead of burying them in prose** — a stray guessed date
     or number risks getting smoothed into a plausible-but-made-up fact
     when Claude edits the page.
   - **Say what to remove, not just what to add** — `index.md` is a living
     page, not an append-only log, so calling out content that no longer
     fits is as important as calling out what's new.

2. **Bring Claude in.** Point Claude at `content.md` (and whichever
   section(s) of `index.md` are affected) and ask it to fold the update
   in. Claude edits `index.md` (or `_tabs/*.md`, `_config.yml`, etc.)
   directly — there's no separate staging copy step like `blog` has,
   since this is a single page living directly in the repo Jekyll builds.

3. **Run the test server.** From `mveng/website`:
   ```
   bundle exec jekyll serve
   ```
   (first time only, if it complains about missing gems: `bundle install`
   first). It prints a `http://127.0.0.1:4000/...` URL — open that and
   review the actual rendered page. Leave it running and edit-rebuild-
   refresh as needed; `Ctrl+C` stops it. `bundle exec jekyll build` (no
   `serve`) does a one-shot build into `_site/` instead.

4. **Publish.** `git add` the changed files, commit, and push to
   `origin/main`. `.github/workflows/pages.yml` builds and deploys
   automatically on push — no manual build step needed. Check the repo's
   **Actions** tab if a change doesn't show up within a minute or two.

## Editing later

There's no "small fix vs. bigger rewrite" distinction here the way there is
for blog posts — `index.md` is a living profile page, not a dated,
shareable/linkable post, so editing it in place is always the right move.
Keep it current as things change (new work, updated "now" section, etc.)
rather than treating any version of it as final.

One thing to remember: `content.md` only exists in this local Dropbox
copy — it's gitignored, so it isn't backed up by git the way everything
else here is.
