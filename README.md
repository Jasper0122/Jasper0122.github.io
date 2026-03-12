# Jasper Li — Academic Portfolio

Personal academic website for **Zongrong (Jasper) Li**, Ph.D. candidate in GIS at Texas A&M University. Research focuses on GeoAI, Data Fusion, and Human Geography in Urban environments.

## Site Structure

| Path | Purpose |
|------|---------|
| `_data/profile.yml` | Personal info, bio, education, experience, awards, social links |
| `_data/display.yml` | Show/hide homepage sections |
| `_data/navigation.yml` | Navbar pages |
| `_data/authors.yml` | Collaborator names and profile links |
| `_publications/YEAR/` | Add publication entries (Markdown) |
| `_projects/YEAR/` | Add project entries (Markdown) |
| `_news/` | Add news/announcements (Markdown) |
| `assets/images/photos/interst.png` | Research interest diagram (homepage) |
| `assets/images/covers/` | Cover images for publications and projects |
| `assets/css/global.css` | Custom styles |
| `assets/CV/cv.pdf` | CV file |

## Local Preview

```bash
cd E:/Jasper0122.github.io
bundle exec jekyll serve
```

Then open http://127.0.0.1:4000/

## Claude Skill

This project includes a Claude Code slash command for quick context loading:

```
/site-context
```

Reads all key files and summarizes the site structure and common editing tasks.
