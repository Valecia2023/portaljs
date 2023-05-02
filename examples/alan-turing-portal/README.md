## Intro

This page catalogues datasets annotated for hate speech, online abuse, and offensive language. They may be useful for e.g. training a natural language processing system to detect this language.

Its built on top of [PortalJS](https://portaljs.org/), it allows you to publish datasets, lists of offensive keywords and static pages, all of those are stored as markdown files inside the `content` folder.

- .md files inside `content/datasets/` will appear on the dataset list section of the homepage and be searchable as well as having a individual page in `datasets/<file name>`
- .md files inside `content/keywords/` will appear on the list of offensive keywords section of the homepage as well as having a individual page in `keywords/<file name>`
- .md files inside `content/` will be converted to static pages in the url `/<file name>` eg: `content/about.md` becomes `/about`

This is also a Next.JS project so you can use the following steps to run the website locally.

## Getting started

To get started first install the npm dependencies:

```bash
npm install
```

Next, run the development server:

```bash
npm run dev
```

Finally, open [http://localhost:3000](http://localhost:3000) in your browser to view the website.
