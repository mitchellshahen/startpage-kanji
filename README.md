<p align="center">
  <img src="favicon.ico">
</p>

<h1 align="center"><strong>startpage</strong>

<p align="center">
  <a href="https://github.com/Alededorigo/startpage/blob/main/LICENSE">
    <img src="https://img.shields.io/github/license/alededorigo/kanji?color=%23cd58f4&style=flat">
  </a>
  <a href="https://github.com/Alededorigo/startpage/releases">
    <img src="https://img.shields.io/github/v/release/alededorigo/kanji?color=ee4f84&include_prereleases&style=flat">
  </a>
  <a href="https://github.com/Alededorigo/startpage/commits/main">
    <img src="https://img.shields.io/github/last-commit/alededorigo/kanji?color=%231ce590&style=flat">
  </a>
</p>
</h1>

<br />

# **A startpage for the browser**

## Release v3.1 <img alt="" align="right" src="https://img.shields.io/github/repo-size/alededorigo/kanji?color=%2358d0f4&style=flat"/>

<a href="https://github.com/Alededorigo/Kanji/releases/tag/3.1">
  <img style="border-radius: 6px" src="https://res.cloudinary.com/adwebsite/image/upload/v1622912733/screenshot.png" alt="preview" align="right" width="400px"/>
</a>

[**Changelog**](https://github.com/Alededorigo/startpage/blob/main/changelog.md) <kbd>v3.1</kbd>:

- [[added](https://github.com/Alededorigo/startpage/commit/23e37f84a1d4cc6f55be543789ffb0801ad145f2)] Chrome theme-color meta tag
- [added] `package.sh` for extensions
- [improved] input box style
- [improved] light instead of dark in CSS
- [fixed] font issues for greetings
- [fixed] removed useless metadata
- [fixed] gap between image and links
- [fixed] font issues
- [[fixed](https://github.com/Alededorigo/startpage/commit/e0c797d3199b7ad878bc7585cc06ada79cb1f8de)] write `/` in input box after focused

<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />

# [🚀️ Demo on Github Pages](https://alededorigo.github.io/startpage/)

<br />
<br />

<img style="border-radius: 6px" src="https://res.cloudinary.com/dn3cdvdix/image/upload/v1615300936/preview_nosmbp.gif" alt="screenshot"/>

## Extensions:

- For Firefox use "Custom New Tab Page"
- For Chrome use "Custom New Tab"
- Or you can load the index.html as an extension <kbd>beta</kbd>

  > see [metadata.json](https://raw.githubusercontent.com/Alededorigo/startpage/main/manifest.json) for details

  - If you are on Firefox:
    > ⇩ Download the zip from [**here**](https://github.com/Alededorigo/startpage/releases)
    - go to `about:debugging`
    - then on `this firefox`
    - `load temporary add-on`
    - locate the `index.html` file and open it
  - If you are on Chrome (or other Chromium browsers):
    - go to `chrome://extensions`
    - enable developer mode
    - drag here the folder
      > if you are on Linux/macOS you can run the `package.sh` file

## Usage:

- On the new tab: use one of the [extensions](#extensions) mentioned

- On the home page:

  - Firefox: Go into
    `Preferences > Home > Homepage and new windows`
    <br/>

    > or editing the `prefs.js` file

    ```js
    67 | user_pref("browser.startup.homepage", "/path/to/index.html")
    ```

    > to open the file, go into `about:profiles`, and open your profile directory

    - Chrome: Go into
      ` Options > Start > Homepage`

## Changing links:

```html
<div class="column">
  <p>SECTION TITLE</p>
  <a class="link" href="WEBSITE LINK">WEBSITE NAME</a>
  <!-- To make a link opening in a new tab, add 'target="_BLANK"' inside the link tag: -->
  <a target="_BLANK"></a>
</div>
```

```html
<div>: column container
├── <p>: section title
│    ├── <a>: bookmark
│    └── <a>: bookmark
└── <p>: section title
     ├── <a>: bookmark
     └── <a>: bookmark
</div>
```

## Keybindings:

| Key        | Function                                  |
| ---------- | ----------------------------------------- |
| `ctrl + m` | Mode - switch between light and dark mode |
| `/`        | Search - focus the search box             |

## Credits:

- [Font for greetings](https://www.1001fonts.com/electroharmonix-font.html)
- [Image on left](https://wallpapercave.com/mt-fuji-wallpaper)
