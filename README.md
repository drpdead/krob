<h1 align="center">
  Kirk Ward Robinson *dot* com
</h1>
<h2 align="center">
  Author Page and Blog
</h2>
<p align="center">
  kirkwardrobinson.com is an author page and blog for prolific author: Kirk Ward Robinson. 
  Built with [Hugo](https://github.com/gohugoio/hugo) site-generator and the cut, pasted, reworked, edited, troubleshot, tested, used as evidence for atheism, a abandoned, trashed, restored, lost, found, fork of the template/theme [Corporio](https://github.com/AminZibayi/Corporio).
</p>

<p align="center">
  <a href="https://github.com/AminZibayi/Corporio/blob/master/LICENSE">
    <img src="https://img.shields.io/github/license/AminZibayi/Corporio?style=flat-square" alt="GitHub">
  </a>
  <a href="https://github.com/AminZibayi/Corporio/releases">
    <img src="https://img.shields.io/github/v/release/AminZibayi/Corporio?include_prereleases&style=flat-square"alt="GitHub release (latest SemVer including pre-releases)">
  </a>
  <a href="https://www.npmjs.com/package/@hyas/core">
    <img src="https://img.shields.io/npm/v/@hyas/core?style=flat-square" alt="npm (scoped)">
  </a>
  <a href="https://github.com/AminZibayi/Corporio/actions?query=workflow%3A%22Hyas+CI%22">
    <img src="https://img.shields.io/github/workflow/status/AminZibayi/Corporio/Hyas%20CI/master?style=flat-square" alt="GitHub Workflow Status (branch)">
  </a>
  <a href="https://app.netlify.com/sites/hyas/deploys">
    <img src="https://img.shields.io/netlify/895a161c-86be-48a2-8c57-a8c5d68cd1a4?style=flat-square" alt="Netlify">
  </a>
</p>

![kirkwardrobinson.com](https://github.com/drpdead/krob/blob/master/assets/images/farmlogo.png)

<h5 align="center"> 
  colored & coded by dropDeadDesigns
</h5>

- [Demo](#demo)
- [Website Features](#website-features)
- [Documentation](#documentation)
- [Contributing](#contributing)
- [Communities](#communities)
- [License](#license)

## Demo

- [Template Demo](https://corporio.onrender.com/)
- Demo Site COMING SOON!

## Website Features

Eight features of kirkwardrobinson.com

1. **Security aware**. Will have A+ scores on [Mozilla Observatory](https://observatory.mozilla.org/analyze/corporio.onrender.com) out of the box. Easily change the default Security Headers to suit your needs.
2. **Fast by default**. Leverages the fastest static site generator, delivering optimized and minified static assets on the fastest CDNs on Render and Netlify.
3. **SEO-ready**. Uses sensible defaults for structured data, open graph, and Twitter cards. Or easily change the SEO settings to your liking.
4. **Tina Integrated**.A feature-rich headless CMS.
5. **Development tools**. Custom Development tools
6. **Responsive**.  Robust, flexible, and intuitive website that is responsibe to any device.
7. **Integrated Blog**. Modern and well-designed author landing page, as well as built-in and full-featured blog ready for publishing.
8. **Individual Titles Page(s) & Spotlight featured/newly released title(s)**. Ability to introduce books, spotlight featured titles, reader testimonials/reviews, showcase all content easily with a modern & sleek user interface
9. **Deploy-ready**. Deploy to Netlify or Render with sensible defaults. Easily use Netlify Functions, Render Redirects, and Headers.

## Documentation

_TODO_

## Contributing

You can contribute to this project by using it to create your own website, sharing it with your friends, sharing your ideas or reporting a bug through opening an issue and informing us if you have crafted your website using Corporio.

Contribution to the source code and documentation are highly welcome, there are many comments in the source code containing the keyword `TODO:` which could be a good staring point for you, feel free to ask a question by opening an issue.

## Communities

_TODO_

## License

[The MIT License](https://github.com/AminZibayi/Corporio/blob/master/LICENSE)

## If you clone this repo and want to view the site through the builtin Hugo/NodeJS HTTP Server you can follow the following steps:
### Install Dependencies through your preferred package manager first:
#### Arch
```bash
sudo pacman -Sy git npm pnpm
git clone https://github.com/drpdead/krob.git /srv/http/krob && sudo chown -R $USER:$USER /srv && cd /srv/http/krob
pnpm install # if any error occur install the necessary dependencies or follow instructions to enable error free installation
pnpm start # starts webserver at 127.0.0.1:1313 open browser and go to https://localhost:1313 to see the website
```
#### Ubuntu
```bash
sudo apt update && sudo apt upgrade
sudo apt install -y git npm pnpm
git clone https://github.com/drpdead/krob.git /srv/http/krob && sudo chown -R $USER:$USER /srv && cd /srv/http/krob
pnpm install # if any error occur install the necessary dependencies or follow instructions to enable error free installation
pnpm start # starts webserver at 127.0.0.1:1313 open browser and go to https://localhost:1313 to see the website
```
#### Windows
run cmd.exe or windows terminal with Admin priviledges
```pwsh
winget install -e github.github- #or winget install -e --id GitHub.cli # First one has a gui
winget install -e --id pnpm.pnpm
gh clone https://github.com/drpdead/krob C:\Users\$USER\srv\krob\
cd C:\Users\$USER\srv\krob\
pnpm install
pnpm start # starts webserver at 127.0.0.1:1313 open browser and go to https://localhost:1313 to see the website


