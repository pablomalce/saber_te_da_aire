# Saber te da aire

Static, multi-page front end for "Saber te da aire", a Spanish-language patient-awareness site about asthma and COPD (EPOC) aimed at readers in Argentina.

## Context

Built between October 2020 (first commit) and February 2021 (last commit). The page content identifies the program as a GSK initiative, with copyright notices and legal footers in place. The repository does not record who commissioned the build; treat it as an early front-end client project, kept here as a code sample. Brand names, logos and campaign images belong to their owners.

## What it does

- Home page with banners that link to the asthma and COPD sections, a patient story section and Instagram calls to action.
- `asma.html` and `epoc.html`: symptom, trigger, diagnosis and myth/fact content built from images and embedded Instagram posts. `asma 2.html` and `asma 3.html` are unlinked layout drafts of the asthma page.
- `especialistas.html`: links to the specialist directories of two Argentine medical associations.
- About, terms and conditions, and privacy policy pages.
- Small anti-clickjacking script in the page head, plus the client's tag-manager include.

## Stack

Plain HTML and CSS (one global stylesheet plus per-component files in `css/components/`), Bootstrap 4.5 with jQuery 3.5 and Popper from CDNs, Font Awesome and Instagram embeds. There is no build step, package manifest or tests.

## Run it

Open `index.html` in a browser, or serve the folder with any static server, for example `python3 -m http.server`. You need a network connection for the CDN assets and Instagram embeds.

Note: the `img/` folder includes several large animated GIFs (up to about 16 MB each), so the clone is about 150 MB.

## Status

Archived early client project (2020–2021). Not maintained.
