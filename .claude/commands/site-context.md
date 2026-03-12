# Site Context — Jasper's Academic Portfolio

Read the following key files to fully understand the site before making any changes:

1. `E:/Jasper0122.github.io/_config.yml` — Jekyll config, collections, plugins
2. `E:/Jasper0122.github.io/_data/profile.yml` — All personal info: bio, education, experience, awards, social links, portrait, research interest image
3. `E:/Jasper0122.github.io/_data/display.yml` — Which homepage sections are shown/hidden
4. `E:/Jasper0122.github.io/_data/navigation.yml` — Navbar pages
5. `E:/Jasper0122.github.io/_data/authors.yml` — Collaborator names and links
6. `E:/Jasper0122.github.io/index.html` — Homepage layout and section order
7. `E:/Jasper0122.github.io/_includes/widgets/profile_card.html` — Main profile widget (bio, photo, research interest image)
8. `E:/Jasper0122.github.io/_includes/widgets/publication_item.html` — How publications are rendered
9. `E:/Jasper0122.github.io/_includes/widgets/project_item.html` — How projects are rendered

After reading, summarize to the user:
- What the site is (Jasper Li's academic portfolio — GIS/GeoAI PhD at Texas A&M)
- The key files to edit for common tasks:
  - **Personal info / bio / photo**: `_data/profile.yml`
  - **Research interest image**: `assets/images/photos/interst.png` (referenced in `_data/profile.yml`)
  - **Add a publication**: create a `.md` file in `_publications/YEAR/`
  - **Add a project**: create a `.md` file in `_projects/YEAR/`
  - **Add news**: create a `.md` file in `_news/`
  - **Show/hide homepage sections**: `_data/display.yml`
  - **Navigation**: `_data/navigation.yml`
  - **Styles**: `assets/css/global.css`
- How to preview locally: `cd E:/Jasper0122.github.io && bundle exec jekyll serve` → http://127.0.0.1:4000/
