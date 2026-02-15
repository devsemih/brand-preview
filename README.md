<div align="center">

# BrandScope

**Free, open-source social media mockup generator and brand name preview tool.**

Preview how your brand looks across Instagram, TikTok, X/Twitter, YouTube, Threads, and LinkedIn — all in one page.

[![Live Demo](https://img.shields.io/badge/demo-live-brightgreen?style=for-the-badge)](https://devsemih.github.io/brand-preview)
[![GitHub Stars](https://img.shields.io/github/stars/devsemih/brand-preview?style=for-the-badge&logo=github)](https://github.com/devsemih/brand-preview/stargazers)
[![License: MIT](https://img.shields.io/badge/license-MIT-blue?style=for-the-badge)](LICENSE)
[![GitHub Pages](https://img.shields.io/badge/hosted%20on-GitHub%20Pages-222?style=for-the-badge&logo=github)](https://devsemih.github.io/brand-preview)
[![Zero Dependencies](https://img.shields.io/badge/dependencies-zero-orange?style=for-the-badge)](#tech-stack)

[Live Demo](https://devsemih.github.io/brand-preview) | [Report Bug](https://github.com/devsemih/brand-preview/issues) | [Request Feature](https://github.com/devsemih/brand-preview/issues)

</div>

---

## What is BrandScope?

**BrandScope** is a free, single-page web tool that generates **realistic social media profile mockups** for your brand. Whether you are launching a new startup, renaming a company, or brainstorming side-project ideas, BrandScope lets you instantly visualize how your brand name, username, bio, and logo will appear across six major social media platforms.

It also includes a built-in **username availability checker** so you can verify whether your desired handle is already taken — before you commit to a name.

No sign-up. No backend. No dependencies. Just open the page and start previewing.

---

## Features

- **Realistic Social Media Profile Mockups** — Pixel-accurate profile previews for **Instagram**, **TikTok**, **X (Twitter)**, **YouTube**, **Threads**, and **LinkedIn**.
- **Username Availability Checker** — Automatically checks GitHub username availability via the GitHub API. For other platforms (Instagram, TikTok, X, YouTube, Threads, LinkedIn, Pinterest), one-click links open the profile URL so you can manually verify and mark the result.
- **Logo Upload** — Upload a PNG or JPG logo and see it applied as the profile picture across every platform mockup instantly.
- **Random Follower & Engagement Stats** — Each preview generates random but realistic follower counts, post counts, and engagement numbers. Hit "Shuffle" to regenerate them.
- **Toggle Platforms On/Off** — Show or hide individual platform previews with toggle chips. Focus only on the platforms that matter to you.
- **Verified Badge Toggle** — Enable or disable the verified/blue checkmark badge across all platform mockups with a single click.
- **Live Preview** — All mockups update in real time as you type your brand name, username, bio, category, and website.
- **Fully Responsive** — Works on desktop, tablet, and mobile screens.
- **Zero Dependencies** — The entire tool is a single HTML file. No frameworks, no build tools, no npm packages.
- **Dark Mode UI** — A carefully designed dark interface with warm tones that keeps the focus on your brand previews.

---

## Screenshots

> Screenshots will be added here. Contributions welcome!

| Social Media Mockups | Username Checker | Configuration Panel |
|:---:|:---:|:---:|
| *Coming soon* | *Coming soon* | *Coming soon* |

---

## Live Demo

Try BrandScope right now — no installation required:

**[https://devsemih.github.io/brand-preview](https://devsemih.github.io/brand-preview)**

---

## How to Use

### Online (Recommended)

1. Visit **[devsemih.github.io/brand-preview](https://devsemih.github.io/brand-preview)**.
2. Enter your **brand name** — the username field auto-populates.
3. Fill in your **bio**, **category**, and **website**.
4. Optionally **upload a logo** (PNG/JPG) to use as the profile picture.
5. Toggle the **verified badge** and individual **platforms** on or off.
6. Scroll down to see realistic mockups for each platform.
7. Use the **username availability checker** to verify if your handle is free on GitHub and other platforms.

### Local / Offline

Since BrandScope is a single HTML file with zero dependencies, you can run it locally:

```bash
git clone https://github.com/devsemih/brand-preview.git
cd brand-preview
open index.html
```

Or simply download `index.html` and open it in any modern browser. That is it — no server, no build step.

---

## Supported Platforms

| Platform | Mockup | Auto-Check |
|----------|:------:|:----------:|
| Instagram | Yes | Manual |
| TikTok | Yes | Manual |
| X / Twitter | Yes | Manual |
| YouTube | Yes | Manual |
| Threads | Yes | Manual |
| LinkedIn | Yes | Manual |
| GitHub | — | Automatic (API) |
| Pinterest | — | Manual |

---

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Markup & Logic | Single HTML file (HTML + CSS + vanilla JavaScript) |
| Fonts | [Outfit](https://fonts.google.com/specimen/Outfit) + [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono) via Google Fonts |
| API | GitHub REST API (for username availability check) |
| Hosting | GitHub Pages |
| Dependencies | **None** |

BrandScope is intentionally built as a **single self-contained HTML file** with no external JavaScript libraries, no CSS frameworks, and no build tools. This keeps it fast, portable, and easy to fork or modify.

---

## Use Cases

- **Startup founders** — Preview your brand identity across social platforms before launch.
- **Freelancers & agencies** — Present social media branding concepts to clients with realistic mockups.
- **Social media managers** — Quickly visualize how a rebrand or new account will look.
- **Side-project builders** — Check username availability across platforms in one place.
- **Content creators** — See how your personal brand appears on every major platform.

---

## Contributing

Contributions, issues, and feature requests are welcome! Here is how you can help:

1. **Fork** the repository.
2. **Create** a feature branch: `git checkout -b feature/amazing-feature`
3. **Commit** your changes: `git commit -m "Add amazing feature"`
4. **Push** to the branch: `git push origin feature/amazing-feature`
5. **Open** a Pull Request.

### Ideas for Contributions

- Add more platform mockups (Snapchat, Facebook, Bluesky, Mastodon, etc.)
- Add screenshot/export functionality (download mockups as images)
- Improve username availability auto-checking for more platforms
- Add light mode theme toggle
- Localization / i18n support for additional languages
- Accessibility improvements

---

## License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

You are free to use, modify, and distribute this tool for personal and commercial purposes.

---

## Acknowledgements

- Profile mockup designs inspired by the official Instagram, TikTok, X, YouTube, Threads, and LinkedIn mobile apps.
- Built with vanilla HTML, CSS, and JavaScript — no frameworks needed.

---

<div align="center">

**If you find BrandScope useful, consider giving it a star!**

[![GitHub Stars](https://img.shields.io/github/stars/devsemih/brand-preview?style=social)](https://github.com/devsemih/brand-preview)

Made with care by [@devsemih](https://github.com/devsemih)

</div>
