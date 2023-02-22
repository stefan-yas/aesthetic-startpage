# Aesthetic Startpage

A beatiful terminal-based startpage for your browser, built with Astro and Markdown.

![render.gif](https://github.com/stefan-yas/aesthetic-startpage/blob/main/public/render.gif)

## Customization

```
git clone https://github.com/stefan-yas/aesthetic-startpage.git
cd aesthetic-startpage
npm i
npm run dev
```

Once you've installed the project dependencies and started the dev server, go into the `src/content` folder and edit the `.md` files with your own shortcuts. You'll need to provide your own images for shortcut icons.

## Install

Once you've customized your startpage, you'll likely want to use it as your new tab in your browser of choice. You can do this by hosting your startpage somewhere and pointing your new tab to that URL. I use [New Tab Redirect](https://chrome.google.com/webstore/detail/new-tab-redirect/icpgjfneehieebagbmdbhnlpiopdcmna) for displaying the start page when I open a new tab. [Vercel](https://vercel.com) for hosting.

## Usage

| Command                     | Action                  |
| :-------------------------- | :---------------------- |
| `ctrl + C`                  | Clears the terminal     |
| `s:`                        | Searches Stack Overflow |
| `r:`                        | Searches Reddit         |
| `help`                      | Help menu               |
| Typed links                 | Open in the same tab    |
| Anything that isn't a match | Searches Google         |

## To-do

- ~~Fix minor dark-mode issues~~ 🌕
- ~~Standardize icons~~ 🌕
- ~~Optimize terminal UX~~ 🌕
- ~~Add more example terminal commands~~ 🌕
