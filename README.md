# Minho Hwang — Academic Website

Personal academic website powered by GitHub Pages + Jekyll. The homepage and printable CV share the same data files.

## Main data files

- `_data/profile.yml` — name, contact, photo, website links, research themes
- `_data/education.yml` — education and theses
- `_data/experience.yml` — professional affiliations
- `_data/awards.yml` — honors and awards
- `_data/service.yml` — professional service
- `_data/talks.yml` — invited talks
- `_data/publications.yml` — journal and conference publications
- `_data/patents.yml` — patents
- `_data/site.yml` — homepage-only extras such as news and teaching

## Profile photo

The homepage reads the path in `_data/profile.yml`:

`photo: /assets/img/profile.JPG`

The actual image file must exist at `assets/img/profile.JPG`.

## Hyperlinks

Most records have an optional `url` field. Leave it blank to render plain text, or paste a URL to make the item clickable. Links change color on hover.

## CV / PDF

Open `https://gkgkgk1215.github.io/cv/` and use **Print → Save as PDF**. The print stylesheet is formatted for A4.

## GitHub Pages

Publishing source:
- Branch: `master`
- Folder: `/(root)`
