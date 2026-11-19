# Zainab Iftikhar — Architect & Project Manager

Portfolio website for Zainab Iftikhar, licensed architectural designer and project manager (Buraidah, KSA · Lahore, Pakistan).

A single static page (`index.html`) with no build step. Images are in `assets/img/` and her CV is in `assets/`.

## Run locally

Open `index.html` in a browser, or serve the folder:

```bash
npx http-server@14.1.1 . -p 5180 -c-1
```

## Enquiry form

By default the form opens the visitor's email app. To send enquiries straight to Zainab's inbox, get a free access key at [web3forms.com](https://web3forms.com) and paste it into `FORM_ACCESS_KEY` near the bottom of `index.html`.

## Adding project photos

Project cards without photos use a blueprint-style placeholder (`.bp`). To use a real photo, replace that block inside the card with an `<img>` pointing to a file in `assets/img/`.
