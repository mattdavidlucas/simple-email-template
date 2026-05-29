# Simple Email Template System

A simple email template system I setup for testing Claude Design.

## Tooling:

- `livereload`: [https://www.npmjs.com/package/livereload](https://www.npmjs.com/package/livereload)
- `sass`: [https://sass-lang.com/install/](https://sass-lang.com/install/)
- `uncss`: [https://www.npmjs.com/package/uncss](https://www.npmjs.com/package/uncss)

## Tooling Commands:

- `livereload`: `livereload`
- `sass`: `sass --watch --no-source-map --style expanded styles.scss:styles.css`
- `uncss`: `uncss --noBanner email-all-components.html > styles.css`

## Tooling Notes:

### `livereload`

A `npm` package that runs a server to monitor changes to an HTML file. Run `livereload` and then open your HTML file in a browser. Anytime you make a change to the HTML file, your browser will automatically reload with the update.

### `sass`

A simple way to manage your primary stylesheet for your email template. You can leverage variables and functions.

### `uncss`

Run your HTML file through this package and `uncss` will remove any unused CSS classes, which is great for reducing the final file size of your final HTML email file.
