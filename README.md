# Jekyll Starter Tailwind
[![All Contributors](https://img.shields.io/badge/all_contributors-4-orange.svg?style=flat-square)](#contributors)
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Ftaylorbryant%2Fjekyll-starter-tailwind.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2Ftaylorbryant%2Fjekyll-starter-tailwind?ref=badge_shield)

A starter kit for using [Tailwind](https://tailwindcss.com) with [Jekyll](https://jekyllrb.com/) that includes:
* A barebones Jekyll starter theme
* A Gulpfile that does the following:

    * Compiles Tailwind
    * Strips out unused CSS using [Purgecss](http://www.purgecss.com/)
    * Runs [Autoprefixer](https://github.com/postcss/autoprefixer)
    * Minifies your CSS
    * Generate a CSS sourcemap
    * Compiles Jekyll
    * Runs [Browsersync](https://www.browsersync.io/) for local development

## What is Tailwind?
>"Tailwind is a utility-first CSS framework for rapidly building custom user interfaces."
–[Tailwind](https://tailwindcss.com)

## What is Jekyll?
>"Jekyll is a simple, blog-aware, static site generator perfect for personal, project, or organization sites. Think of it like a file-based CMS, without all the complexity. Jekyll takes your content, renders Markdown and Liquid templates, and spits out a complete, static website ready to be served by Apache, Nginx or another web server. Jekyll is the engine behind GitHub Pages, which you can use to host sites right from your GitHub repositories."
–[Jekyll](https://jekyllrb.com/)

## Requirements
* [Bundler](http://bundler.io/)
* [Jekyll](https://jekyllrb.com/)
* [Node.js](https://nodejs.org/en/)
* [npm](https://www.npmjs.com/)
* [Ruby](https://www.ruby-lang.org/en/)

## Get started
* `bundle install` to install Ruby gems
* `npm ci` to install npm packages listed in `package-lock.json`
* `npm run start` to compile the site with development settings and run BrowserSync

## Build your site
* `npm run build:dev` to compile the site with development settings
* `npm run build` to compile the site for production


## Deploy
[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/taylorbryant/jekyll-starter-tailwind)

Note: By default, Netlify uses `jekyll build` as the build command. Make sure to change this to `npm run build`.

## License
[MIT](https://github.com/taylorbryant/jekyll-starter-tailwind/blob/master/LICENSE.md)


[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Ftaylorbryant%2Fjekyll-starter-tailwind.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2Ftaylorbryant%2Fjekyll-starter-tailwind?ref=badge_large)

## How you can help
Enjoying Jekyll Starter Tailwind and want to help? You can:
* [Create an issue](https://github.com/taylorbryant/jekyll-starter-tailwind/issues/new) with some constructive criticism
* [Submit a pull request](https://github.com/taylorbryant/jekyll-starter-tailwind/compare) with some improvements to the project

## Contributors

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore -->
<table><tr><td align="center"><a href="http://phproberto.com"><img src="https://avatars0.githubusercontent.com/u/1119272?v=4" width="100px;" alt="Roberto Segura"/><br /><sub><b>Roberto Segura</b></sub></a><br /><a href="https://github.com/Oddstronaut/jekyll-starter-tailwind/commits?author=phproberto" title="Code">💻</a></td><td align="center"><a href="https://github.com/benmp"><img src="https://avatars3.githubusercontent.com/u/9081154?v=4" width="100px;" alt="benmp"/><br /><sub><b>benmp</b></sub></a><br /><a href="https://github.com/Oddstronaut/jekyll-starter-tailwind/commits?author=benmp" title="Code">💻</a></td><td align="center"><a href="https://github.com/jd4no"><img src="https://avatars0.githubusercontent.com/u/15043675?v=4" width="100px;" alt="Joey Defourneaux"/><br /><sub><b>Joey Defourneaux</b></sub></a><br /><a href="https://github.com/Oddstronaut/jekyll-starter-tailwind/commits?author=jd4no" title="Code">💻</a></td><td align="center"><a href="https://shime.sh"><img src="https://avatars3.githubusercontent.com/u/703563?v=4" width="100px;" alt="Hrvoje Šimić"/><br /><sub><b>Hrvoje Šimić</b></sub></a><br /><a href="https://github.com/Oddstronaut/jekyll-starter-tailwind/commits?author=shime" title="Code">💻</a></td></tr></table>

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!