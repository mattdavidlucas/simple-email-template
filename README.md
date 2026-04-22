# Simple Email Template

A simple starter email template for your next campaign.

## Tooling:

- `livereload`: [https://www.npmjs.com/package/livereload](https://www.npmjs.com/package/livereload)
- `sass`: [https://sass-lang.com/install/](https://sass-lang.com/install/)
- `uncss`: [https://www.npmjs.com/package/uncss](https://www.npmjs.com/package/uncss)

## Tooling Commands:

- `livereload`: `livereload [path] [options]`
- `sass`: `sass --watch --no-source-map --style expanded styles.scss:styles.css`
- `uncss`: `uncss email-shell.html > styles.css`

## Tooling Notes:

### `livereload`

A `npm` package that runs a server to monitor changes to an HTML file. Run `livereload` and then open your HTML file in a browser. Anytime you make a change to the HTML file, your browser will automatically reload with the update.

### `sass`

A simple way to manage your primary stylesheet for your email template. You can leverage variables and functions.

### `uncss`

Run your HTML file through this package and `uncss` will remove any unused CSS classes, which is great for reducing the final file size of your final HTML email file.

## To Do's:

- [ ] Update `email-shell.html` to use 2026 code
- [ ] Set up typography hierarchy (`h1`, `h2`, `h3`, `h4`, `p`, `small`)
- [ ] Set up image hierarchy (full width, 2 col (50:50), 2 col (75:25))
- [ ] Set up container hierarchy (row)
- [ ] Set up column structures: 1 col, 2 col (50:50), 2 col (75:25)
- [ ] Create `in-progress` directory for in-progress email files
- [ ] Create `output` directory for final, production ready email files
- [ ] Create agent skill for generating emails
