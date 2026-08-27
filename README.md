# Five16 Films Website

<img width="1890" height="946" alt="image" src="https://github.com/user-attachments/assets/351e2055-a0fd-4be6-bc68-4186d3bd4d5c" />



## Project Overview

This project is a Webflow-exported static website for **Five16 Films**, an independent film production company.

The website presents the feature film **Apples and Airplanes**, including its story, production information, cast, company information, press resources, and contact details.

## Project Structure

```text
/
├── index.html
├── css/
│   ├── normalize.css
│   ├── webflow.css
│   └── five16films-54c2aafe25d29cfbe701eb0ad64.webflow.css
├── js/
│   └── webflow.js
├── images/
│   ├── site images and graphics
│   ├── responsive image variants
│   ├── favicon.ico
│   └── webclip.png
└── fonts/
    ├── Cormorant font files
    └── Inter font files
```

## Main Page

The current export contains the main homepage in:

`index.html`

The page includes:

- Five16 Films branding
- Apples and Airplanes hero section
- Film synopsis
- Production information
- Cast section
- Sarafina King profile
- Five16 Films company story
- Press & EPK section
- Press contact information
- Screening / ticket notification section
- Footer and copyright information

## Film Information

**Title:** Apples and Airplanes  
**Genre:** Romantic Comedy  
**Release:** Fall 2026  
**Written & Produced by:** Sarafina King  
**Production:** Five 16 Films  
**Directed by:** Camilo Diaz  
**Music:** Bazzi

## Cast

- Sarafina King — Olivia Green
- Jake Lockett — André Pagnelli
- Fivel Stewart — Alexa
- Dominic Burgess — Jean-Luc
- Lara Silva — Kelsi
- French Stewart — Bob

## External Links

The site currently contains:

- IMDb link for Sarafina King
- Instagram link for Sarafina King
- Email contact: `press@five16films.com`

## How to Run Locally

Because this is a static Webflow export, no Node.js, React, or backend server is required.

### Option 1 — Open Directly

Open `index.html` in a browser.

### Option 2 — VS Code Live Server

1. Open the extracted project folder in VS Code.
2. Install/use the **Live Server** extension.
3. Right-click `index.html`.
4. Select **Open with Live Server**.

Using a local server is recommended for testing links, assets, and browser behavior.

## Deployment

Upload the complete extracted project while keeping the folder structure unchanged.

Make sure these paths remain valid:

- `css/...`
- `js/...`
- `images/...`
- `fonts/...`

Do not upload only `index.html`; the CSS, JavaScript, images, and fonts are required for the website to render correctly.

## Important Notes

### Webflow Export

This project is an exported Webflow website. The CSS and JavaScript contain Webflow-generated classes and interactions.

Avoid renaming or moving the existing asset folders unless all corresponding paths in `index.html` and the CSS files are updated.

### Images

The `images/` folder contains both original images and Webflow-generated responsive variants such as:

- `-p-500`
- `-p-800`
- `-p-1080`
- `-p-1600`

These variants are referenced by responsive `srcset` attributes in the HTML.

### Fonts

The project includes local Cormorant and Inter font files. Keep the `fonts/` folder available when deploying the site.

### Contact Email

The press/contact email currently used by the website is:

`press@five16films.com`

Verify this mailbox before launch.

## Before Production Launch

Check the following:

- [ ] Test the website on desktop and mobile.
- [ ] Test all navigation links.
- [ ] Test IMDb and Instagram links.
- [ ] Test the press email link.
- [ ] Verify all film information and cast names.
- [ ] Verify the Fall 2026 release information.
- [ ] Replace any placeholder `#` links with final destinations.
- [ ] Confirm EPK, Key Art, and Production Stills download links.
- [ ] Confirm the ticket notification functionality.
- [ ] Check image loading and responsive behavior.
- [ ] Add/verify SEO title and meta description.
- [ ] Test the favicon.
- [ ] Test the site on the final hosting/domain.
- [ ] Check the page on Chrome, Safari, Firefox, and mobile browsers.

## Current Limitations

The exported project contains placeholder `#` links in some areas, particularly around press/resource actions. These should be connected to the final EPK, key art, production stills, or relevant destinations before launch.

The project is a static Webflow export, so functionality that depends on Webflow-hosted services or CMS features may need to be recreated or connected separately after deployment.

## Credits

Website content and branding are presented for Five16 Films and the feature film **Apples and Airplanes**.

Copyright © 2026 Five 16 Films LLC. All Rights Reserved.
