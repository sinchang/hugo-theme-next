<h1 align="center">Hugo Theme Starter</h1>

<p align="center">Develop Hugo themes with Vite, a modern front-end tool.</p>

<p align="center">
  <a href="https://github.com/misitebao/hugo-theme-starter/blob/main/LICENSE">
    <img alt="GitHub" src="https://img.shields.io/github/license/misitebao/hugo-theme-starter"/>
  </a>
  <a href="https://github.com/misitebao/yakia">
    <img alt="GitHub" src="https://cdn.jsdelivr.net/gh/misitebao/yakia/assets/badge_flat.svg"/>
  </a>
  <a href="https://github.com/theNewDynamic/awesome-hugo">
    <img alt="Awesome Hugo" src="https://awesome.re/badge.svg"/>
  </a>
</p>

<div align="center">
<strong>
<samp>

[English](README.md) · [简体中文](README.zh-Hans.md)

</samp>
</strong>
</div>

## Usage

Click the "[**Use this template**](https://github.com/misitebao/hugo-theme-starter/generate)" button at the top of the page, follow the prompts to fill out the form, and create your own theme.

Run `npm install` in the root directory to install dependencies.

```
npm install
```

Running `npm run build` will package the css and js source code written in the `src` directory into the `static` directory.

```
npm run build
```

If you want to get real-time development experience, you can run the `npm run build:watch` command. When you update the js and css source code, the files will be automatically repackaged to the `static` directory. The best way is to cooperate with `hugo serve` command to use.

```
npm run build:watch

cd exampleSite && hugo serve
```
