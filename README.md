# AntennaCore website

A simple static company page focused on beamsteering chips and phased array antennas. Contact: info@antennacore.com.

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

- `index.html`: page text, contact links, and concept illustration.
- `styles.css`: responsive layout and styling.
- `assets/antennacore-logo.svg`: supplied approved logo, copied without modification.

The array illustration is a schematic concept, not a photograph of hardware. The site uses no external fonts, scripts, analytics, or forms.
