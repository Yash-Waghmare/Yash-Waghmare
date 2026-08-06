# AGENTS.md

## Cursor Cloud specific instructions

This repository is a **GitHub special profile repository** (`Yash-Waghmare/Yash-Waghmare`). Its only tracked file is `README.md`, which GitHub renders on the owner's profile page. There is intentionally **no application code, package manager, build system, automated tests, or lint configuration**.

Implications for development:

- There is nothing to install, build, run, or test in the traditional sense. The update script is a no-op because there are no dependencies.
- The "product" is the rendered `README.md`. The real rendering is done by GitHub (GitHub-Flavored Markdown plus GitHub-specific features such as `:shortcode:` emoji).
- To preview locally, render `README.md` to HTML with any Markdown renderer (e.g. `npx marked`) and open it in a browser. Note that a local renderer will NOT reproduce GitHub's `:emoji:` shortcodes, and the badge/icon/stats images are hosted on external CDNs (`img.shields.io`, `github.com/devicons/...`, `github-readme-stats.vercel.app`, etc.), so they only load with internet access. Broken images/emoji in a local preview are expected and are not environment defects.
