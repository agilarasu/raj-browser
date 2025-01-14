<div align=center>

 ![icon-small](https://user-images.githubusercontent.com/72294760/131682171-2300d5e0-f42c-490e-86bd-6eba492abad9.png)

# Raj Browser

 [![License](https://badgen.net/github/license/Rajaniraiyn/raj-browser)](LICENSE) [![Release](https://badgen.net/github/release/Rajaniraiyn/raj-browser)](../../releases/latest) ![Checks](https://badgen.net/github/checks/Rajaniraiyn/raj-browser) [![Stars](https://badgen.net/github/stars/Rajaniraiyn/raj-browser)](../../stargazers) [![Forks](https://badgen.net/github/forks/Rajaniraiyn/raj-browser)](../../network/members) [![Opened Issues](https://badgen.net/github/open-issues/Rajaniraiyn/raj-browser)](../../issues?q=is%3Aopen) [![CodeQL](https://github.com/Rajaniraiyn/raj-browser/actions/workflows/codeql-analysis.yml/badge.svg)](https://github.com/Rajaniraiyn/raj-browser/actions/workflows/codeql-analysis.yml)

 A UI and privacy focussed browser for the web from the web.
</div>

<!-- ## Screenshots

### New tab

![New Tab](https://user-images.githubusercontent.com/72294760/131171971-10b9c9f0-f03f-4e4b-bb5d-78721f72cbae.png)

### New tab (after animation)

![New Tab (after animation)](https://user-images.githubusercontent.com/72294760/131172020-e41a5e37-822d-4927-898b-2ba439bef3f0.png)

### Google home page

![Google home page](https://user-images.githubusercontent.com/72294760/131172169-082379af-6bc4-41d3-b528-db31dab6b9fb.png)

## Adaptable top bar (according to the active tab)

![top bar (active - google.com)](https://user-images.githubusercontent.com/72294760/131172271-4ada4b0c-784b-4394-9ca7-bf483ae5d82e.png)
![top bar (active - New tab)](https://user-images.githubusercontent.com/72294760/131172300-cb02c651-00a1-45e5-9818-6aefda042b82.png)

## Demo
<https://user-images.githubusercontent.com/72294760/131172992-8613a52a-ace2-48c0-a528-f7e87e16ded8.mp4> -->

## Reason

I noticed all the browser even from the past uses same kind of tabs and address bar with slight variations.
To bring new evolution to browser design, I have created this with more space for the webpages and adaptable browser colour according to the website.

- Microsoft Edge (Chromium) ![image](https://user-images.githubusercontent.com/72294760/131173277-3278767e-1d20-4621-bcd5-ae58bd0a73b4.png)
- Microsoft Edge (Legacy) ![image](https://user-images.githubusercontent.com/72294760/131176216-d753f761-0e5b-4160-80ac-b74c42c90ceb.png)
- Google Chrome ![image](https://user-images.githubusercontent.com/72294760/131173422-3f10d0df-4df6-40a1-8234-9b3299022926.png)
- Mozilla Firefox (new proton design) ![image](https://user-images.githubusercontent.com/72294760/131173690-d336fc07-eca9-4c38-bff2-ca63d721e82a.png)
- Mozilla Firefox (old) ![image](https://user-images.githubusercontent.com/72294760/131173829-f382f4f6-0dc4-4772-b4e8-69172fbfead9.png)
- Vivaldi ![image](https://user-images.githubusercontent.com/72294760/131174404-2dc56f12-bf64-469e-a6b5-2c718df7beab.png)
- Brave ![image](https://user-images.githubusercontent.com/72294760/131174497-ef2663c8-25bf-4fbb-8eb4-80d29d02162d.png)
- Internet Explorer ![image](https://user-images.githubusercontent.com/72294760/131176270-c43c0632-bd26-4001-b1e1-656b062f5caf.png)

and most of all other browsers

## Features

**🚀 Current:**

- Chromium based so more compatibility over websites
- Uses only necessary chromium binaries so more privacy
- Modern, Unique and Simple Design
<!-- - Adaptive top-bar for website like feel -->
- Smooth animations
- Powerful Ads Blocking using [adblocker-electron](https://github.com/cliqz-oss/adblocker/tree/master/packages/adblocker-electron)
- Awesome downloader which can pause and resume download even after any time using [electron-download-manager](https://github.com/danielnieto/electron-download-manager)
<!-- - Custom scrollbar for all websites -->
- Completely powered by opensource
- Address bar
<!-- - Process manager -->
<!-- - Settings configuration -->
- Context menu using [electron-context-menu](https://github.com/sindresorhus/electron-context-menu)
<!-- - Code caching for faster subsequent loads -->
<!-- - Splash screen -->

**🤞 Eventually:** (can be used manually)

- Chrome extensions
- Website screenshots
- Dev tools (use context menu to use it)
- Dark mode
- Dropping links to open a page

**🤔 Considering:** (planned to be implement)

- Performance optimizations
- UI for Adblocker
- UI for download manager
- Settings UI
- More featured new tab
- Sleeping tabs for reduce resources
- Customisable UI
- Custom themes
- Improved UI and UX
- More animations
- On the fly image compression to reduce data usage
- Installation setup
- Porting from `<webview>` to `BrowserView` for additional performance and security

**❌ Limitations**

- no `prompt` support as electron by default doesn't support it (but working on it. devs! take a look at `customDialogues.js` for more info)

## Stack

 1. [Svelte](https://Svelte.dev)
 2. [TypeScript](https://)
 3. [Node.js](https://nodejs.org/)
 4. [Electron.js](https://www.electronjs.org/)

### To run the browser locally

To clone and run this repository you'll need [Git](https://git-scm.com) and [Node.js](https://nodejs.org/en/download/) (which comes with [npm](http://npmjs.com)) installed on your computer. From your command line:

 1. `git clone https://github.com/Rajaniraiyn/raj-browser`
 2. `cd raj-browser`
 3. `npm install`
 4. `npm start`

That's it you are running Raj browser

### To build locally

To clone and build packages of this repository you'll need [Git](https://git-scm.com) and [Node.js](https://nodejs.org/en/download/) (which comes with [npm](http://npmjs.com)) installed on your computer. From your command line:

 1. `git clone https://github.com/Rajaniraiyn/raj-browser`
 2. `cd raj-browser`
 3. `npm install`
 4. `npm run make`

Then check the out folder you will see both portable and installable files according to your OS.

## Downloads

[**Latest Release**](https://github.com/Rajaniraiyn/raj-browser/releases/latest)

**For Windows** download [Raj.Browser-win32-x64-portable.7z](https://github.com/Rajaniraiyn/raj-browser/releases/latest/download/Raj.Browser-win32-x64-portable.7z)

**For Others** Please build it yourself as I am using Windows
