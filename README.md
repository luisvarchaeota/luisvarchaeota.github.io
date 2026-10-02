# Luis E. Valentin-Alvarado academic website

Personal research website for Luis E. Valentin-Alvarado, Ph.D.

This site uses plain HTML and CSS. It needs no build step or ChatGPT service to run. GitHub Pages can serve these files directly.

## Website and repository

- Website: https://luisvarchaeota.github.io/
- Repository: https://github.com/luisvarchaeota/luisvarchaeota.github.io
- Publishing branch: `main`, repository root (`/`).
- GitHub Pages settings: https://github.com/luisvarchaeota/luisvarchaeota.github.io/settings/pages

The `.nojekyll` file tells GitHub Pages to serve the HTML, CSS, and images directly. Changes committed to `main` automatically update the website after GitHub finishes deploying them.

This repository and its history are public. Use the email-only public CV and keep private application documents or unrelated research files outside the repository.

## Update text and publications

1. Open `index.html` in GitHub and select the pencil button to edit it.
2. Find the relevant section: `home`, `research`, `publications`, `about`, `teaching`, `talks`, `outreach`, or `connect`.
3. Edit the wording between the HTML tags. Preserve the surrounding tags and link destinations.
4. Select **Commit changes** to save. Changes to the Pages publishing branch automatically update the website.

For a new publication, copy one complete existing `<li>` inside the publication list and update its year, journal, title, authors, and DOI links. Keep the list in the desired order.

## Replace the downloadable CV

Export the revised CV as a PDF. Replace `assets/Luis_Valentin-Alvarado_CV.pdf` with the new PDF using the same filename so the existing download links continue working. Use the version intended for public sharing.

## Add fieldwork photographs or paper figures

Upload each image to `assets`, using a short filename with no spaces. Add an image and caption in the relevant section of `index.html`. For example:

```html
<figure>
  <img src="assets/fieldwork.jpg"
       alt="Describe what is visible in this photograph"
       loading="lazy" style="max-width:100%;height:auto">
  <figcaption>Location, research context, and photograph credit.</figcaption>
</figure>
```

Use photographs and figures you have permission to share, with the appropriate credit. Keep captions factual and make the image description useful to visitors using a screen reader.

## Change the visual style

The colors, fonts, spacing, and responsive layout are defined in `styles.css`. Keep a copy of the previous version or use GitHub's commit history to recover an earlier version.

## Add a personal domain later

After registering a domain, verify it with GitHub and configure it in **Settings → Pages → Custom domain**, following GitHub's instructions. Add a `CNAME` file only after the exact domain has been chosen and configured.

## Reference

- [Create a GitHub Pages site](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site)
- [Configure the publishing source](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)
- [Use a custom domain](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/about-custom-domains-and-github-pages)
