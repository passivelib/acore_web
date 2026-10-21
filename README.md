# AntennaCore website

A simple static company website focused on beamsteering chips and phased array antennas. Contact: info@antennacore.com.

## Preview locally

From this directory, run:

```sh
python3 -m http.server 8000
```

Open http://localhost:8000 in your browser. No dependencies or build step are required.

## GitHub Pages

Upload the **contents of `git_src`** to the root of your GitHub Pages repository. In the repository's **Settings → Pages**, choose **Deploy from a branch**, select your publishing branch and **/ (root)**, and save.

All asset paths are relative, so the page supports both a project URL and a custom domain. Hosting the site on a custom domain requires separate DNS and GitHub Pages domain configuration.

## Editing

- `index.html`: Home page, technology overview, beamsteering illustration and founder introduction.
- `about.html`: About Us page with founder biographies and portraits.
- `contacts.html`: Contacts page with company location, an embedded Google Map, founder portraits and a plain-text email address.
- `antennacore.css`: responsive layout and styling.
- `assets/arndt-ott.png` and `assets/milenko-milicevic.jpg`: supplied founder portraits.
- `assets/antennacore-logo.svg`: supplied approved logo, copied without modification.

The array schematic, supplied chip image and generated larger antenna array image are concept illustrations, not photographs of finished AntennaCore products. The site uses no external fonts, analytics, or forms. The Contacts page embeds Google Maps, which requires an internet connection; the address and a separate directions link remain available alongside it. The beamsteering illustration sweeps automatically using CSS and is conceptual, not a simulated radiation pattern. It stays still when reduced motion is preferred. No JavaScript is required.

## Publishing updates

Publish all HTML files, `antennacore.css`, and the complete `assets/` directory together. The stylesheet was renamed from `styles.css` to prevent browsers from reusing the earlier cached stylesheet. Make sure the new CSS file is included in the published repository.

If the hosted page differs from the local preview, confirm the latest GitHub Pages deployment completed for the branch you published, then reload the page. Keep the repository's original file and folder names: asset paths are case-sensitive.
