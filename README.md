GopherCon Singapore 2023
===

The international Go programming language conference for Singapore and Southeast Asia!

Built with [Hugo](https://gohugo.io/)

Development
---

1. [Install Hugo](https://gohugo.io/overview/installing/)
  - On Mac, `brew update && brew install hugo`.
2. Run `hugo server`.
3. Load `localhost:1313` in the web browser.

Development with CSS
---
The `gopherconsg-2023` theme uses uses TailwindCSS so additional setup is required if updating styles.

1. `cd themes/gopherconsg-2023`
2. `npm install`
3. `npm run watch`
   
This will watch `./tailwind.css` for changes and automatically build to `./assets/style.css`. This `style.css` file is what Hugo uses in the production step below.

Production
---
1. Run `hugo`.
2. The static site will be generated in `public/`.

Updating Site Content
---
Most of the site text content (speakers, schedule etc) is stored as **TOML** files in `data/` folder.

Any related images should be placed in `assets/images` and linked accordingly in the respective TOML.