# deep.ventures website

this is the [deep.ventures](https://www.deep.ventures) website developed in hugo and hosted on netlify

## bootstrap theme

this website defines a bootstrap theme, sources in **themes/deep-ventures/src/scss** and needs to be compiled with the following:

```bash
cd themes/deep-ventures
npm install
npm run css
```

you should then find the compiled css output in ***themes/deep-ventures/static/css/*

## hugo theme

this website defines a hugo theme, sources in **themes/deep-ventures** structured as follows (directories are relative to the theme root):

- `layouts/index.html` main file importing all partials
- `layouts/section/*` static pages linked from index


## hugo static

to run locally:

```bash
brew install hugo
hugo server
```
