# FocusMediaPlayer Website

A responsive static product site for FocusMediaPlayer. Built with plain HTML, CSS and a small amount of JavaScript; no build tools, package manager, analytics, external image dependencies, or JavaScript framework are required.

## Preview locally
Open `index.html` in a modern browser.

## Installer download
The primary download buttons point to the v1.0.0 GitHub release asset:

`https://github.com/Chayanethic/focusmediaplayer/releases/download/v1.0.0/FocusMediaPlayerSetup.exe`

Before publishing, confirm the release is public and the asset is uploaded with the exact filename `FocusMediaPlayerSetup.exe`. If you publish a new version, update the URLs in `index.html` and the release details accordingly.

## Deploy
Upload the contents of this folder (including `index.html` and `privacy.html`) to a static host such as GitHub Pages, Cloudflare Pages, or Netlify. For GitHub Pages, you can put the site in the repository root or configure Pages to use the folder/branch where these files live. A custom domain is optional.

## Before public launch
- Test every download link and the installer on a clean Windows 10/11 x64 machine.
- Confirm all feature descriptions match the released build.
- Review `privacy.html` for your actual hosting setup and application behavior.
- The installer is not automatically trusted just because it is hosted on GitHub; unsigned applications may still show Windows reputation or Smart App Control warnings.
- Review redistribution obligations for bundled VLC libraries/plugins before distributing broadly.

## Design notes
The player interface artwork is made with inline SVG and CSS so it loads quickly and does not depend on remote stock images. It is explicitly described as illustrative rather than a literal screenshot of the application.
