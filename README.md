# Adnan Shahid — academic website

Academic website for Adnan Shahid, built with the HugoBlox Academic CV template.

## Local preview

Install Hugo Extended 0.169.0, Go, Node.js 22, and pnpm 10.14.0, then run:

```sh
pnpm install
hugo server
```

Open the local URL printed by Hugo.

## GitHub Pages deployment

The workflows in `.github/workflows/` build the site and deploy it to GitHub Pages whenever a commit is pushed to `main`. In the repository’s **Settings → Pages**, set **Build and deployment → Source** to **GitHub Actions**. The production site URL is <https://adnanshahid84.github.io/>.

## Site content

Edit the Markdown files in `content/` and profile details in `data/authors/me.yaml`. The public CV page is a web-formatted academic profile. The private source CV is not part of this repository. Phone numbers, street addresses, and reference contact details are excluded.

The [publications page](content/publications/_index.md) includes the complete CV publication list, grouped by category and year, plus newer preprints. Keep its category counts and Markdown reference links in sync when adding entries. Link IEEE papers directly to their verified IEEE Xplore document pages rather than UGent bibliography records. For other publications, prefer verified publisher, DOI, preprint, or institutional repository links; label search links explicitly when a public record cannot be verified.

## Template

Based on [HugoBlox Academic CV](https://github.com/HugoBlox/hugo-theme-academic-cv), licensed under MIT.
