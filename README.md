[![Netlify Status](https://api.netlify.com/api/v1/badges/bbf28a84-4bdb-407b-a2fa-32628d27fa3d/deploy-status)](https://app.netlify.com/sites/eleventy-netlify-boilerplate/deploys)

# My Personal Site 

![2020-website-redesign](https://user-images.githubusercontent.com/1427548/93402366-705a1e80-f839-11ea-90c5-25be326face5.png)

My personal website, blog and portfolio.

- PostCSS
- Dark mode support
- Theme switcher

Built with [Eleventy](https://www.11ty.io/), an awesome 
static site generator. Proudly hosted and deployed with [Netlify](https://www.netlify.com).

## Local development

### 1. Clone this repository:

```
git clone https://github.com/derekshirk/personal-site-2023.git
```

### 2. Navigate to the directory

```
cd personal-site-2023
```

Specifically have a look at `.eleventy.js` to see if you want to configure any 
Eleventy options differently.

### 3. Install dependencies

```
npm install
```

### 4. Edit _data/metadata.json

This file contains your site title and author details.

### 5. Run Eleventy (builds the site)

```
npx eleventy
```

Use --serve to start up a hot-reloading local web server.

```
npx eleventy --serve
```

Or in debug mode:
```
DEBUG=* npx eleventy
```

## Bug reports, feature requests, etc

This is an ongoing project and I welcome contributions. 
Feel free to submit a [PR](https://github.com/derekshirk/personal-site-2023/pulls) for feature requests or create an [issue](https://github.com/derekshirk/personal-site-2023/issues) to report bugs.

## Deploy to Netlify

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/derekshirk/personal-site-2023&stack=cms)