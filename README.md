# A collection of Hugo themes
This is a collection of cool hugo themes, ready to be cloned and deployed unto GitHub Pages.

## How to add a new theme
1. Download a .zip of the theme that you want to add
2. Create a new hugo website using `hugo new site [theme-name]`
3. Replace the generated hugo website content with `exampleSite` content from the theme (including `go.mod` and `go.sum`)
4. Place the theme unzipped folder into `themes`
5. Run `hugo server` to ensure the website builds
6. If the theme doesn't come with a deployment pipeline create or copy one using the `.github/workflows/deploy.yml` path
