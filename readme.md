# Kagi Custom CSS
My personal collection of Kagi custom css rules.
Some of these were constructed by me (though likely inspired by something else), some were copied from other Kagi themes (and possibly modified). I'll do my best to add comments linking to where I found the rule or inspiration.

## How to use
1. Open Kagi's [Custom CSS settings page](https://kagi.com/settings?p=custom_css)
1. Turn on `Enable Custom CSS`
1. Copy the contents of `src/kagi-custom.css` into the text box at the bottom of the settings page

## Minify & Transpile
I've set up a LightningCSS task for minification and transpilation should it ever be needed.
To adjust the transpilation target, adjust `.browserslistrc` (see https://github.com/browserslist/browserslist#query-composition).

To run LightningCSS:

```bash
# once, to install lightningcss-cli
npm install

# run the actual task
npm run build
```
