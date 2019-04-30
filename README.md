# Ceritanya Developer Website

[![Netlify Status](https://api.netlify.com/api/v1/badges/ce2f05dd-11a9-43ad-98bd-f0b4dc4365b2/deploy-status)](https://app.netlify.com/sites/ceritanyadeveloper/deploys)

This website is for [Ceritanya Developer Podcast](https://ceritanyadeveloper.com), an Indonesia Podcast interview awesome software developers about their past, present and their future. We talk about their first computer, first programming language and first job as a developer. Build with [Reptar](http://reptar.github.io/) as static site generator and [tachyons](http://tachyons.io) as the css framework.

Help me improve this website 🙇‍♂️.

## Installation

First, clone this repo.

```sh
git clone https://github.com/rizafahmi/ceritanya-developer-reptar.git
```

Then install `reptar` command line globally.

```sh
npm install -g reptar
```

Go to the directory. And install dependencies.

```sh
cd ceritanya-developer-reptar
npm install
```

Build and watch `reptar` and change things!

```sh
reptar build && reptar watch
```

## Directory Structure

```sh
$ tree -L 1
.
├── README.md
├── _posts
├── _site
├── _templates
├── node_modules
├── package-lock.json
├── package.json
├── reptar.config.js
└── subscribed.md
```

Start with `_templates` directory to change the layout of the website. And I thank you 🙇‍♂️.
