# bardsen.gg

The personal homepage and digital desktop of Dani Baardsen.

`bardsen.gg` is a Windows 98-inspired personal hub for browsing Dani's social, gaming, development, media, fitness, and homelab profiles. It is designed as a small interactive desktop rather than a conventional landing page.

## Features

- Retro Windows-style Explorer window containing categorized social accounts
- Search across all listed profiles
- Sticky Explorer search bar that remains visible while browsing
- Notepad-style About Me window with rotating profile images
- Dialup contact form with keyboard submission support
- Taskbar controls for moving Explorer, Dialup, and Notepad into focus
- Responsive layouts for desktop, tablet, and phone screens
- No framework or build step required

## Project Structure

```text
.
├── index.html       # Complete website, styles, and client-side behavior
├── pfp/             # Profile images used by the Notepad window
├── package.json     # Minimal project metadata
└── LICENSE          # Proprietary usage terms
```

Profile images are discovered automatically from `pfp/`. Add numbered files such as `5.png`, `6.jpg`, or `7.webp` and they will be included on the next page load without editing `index.html`.

## Run Locally

Because this is a static site, it can be opened directly in a browser:

```text
index.html
```

For local development, serve the project directory with any static HTTP server. For example, with Python installed:

```sh
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Deployment

The site can be deployed to GitHub Pages, Cloudflare Pages, Netlify, or any static host. Configure the custom domain through the hosting provider and keep the repository private if the source should not be publicly accessible.

## Author

**Dani Baardsen**

- Website: [bardsen.gg](https://bardsen.gg)
- GitHub: [@bardtini](https://github.com/bardtini)

## License

This is a proprietary project. Copyright (c) 2026 Dani Baardsen. All rights reserved.

The source code, design, written content, images, and other project assets may not be copied, modified, distributed, republished, or reused without prior written permission. See [LICENSE](LICENSE) for the complete terms.
