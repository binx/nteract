# showcase application

The showcase application lets you try out different pages that "showcase"
nteract capabilities.

## Installation and usage

Install nteract's monorepo as described in the `README.md` in the root directory
of the repo.

Run:

```
npm run app:showcase
```

Open `127.0.0.1:3000` in your browser. You'll be able to make changes to
`showcase` and see the changes update live.

## Basics

The app uses "next-gen" core components.

### App pages

These are the currently available pages within showcase:

- index.js
- notebook-preview.js
- notebook-render.js
- transforms.js

To add an additional page, place the page in the `pages` directory and update
`index.js`.
