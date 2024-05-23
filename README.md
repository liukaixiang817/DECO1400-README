<p align="center">
  <a href="https://game.lkx666.cn">
    <img src="logo.jpg" height="256">
  </a>
  <a href="https://game.lkx666.cn">
    <h1 align="center">Games in Old Memories</h1>
  </a>
</p>
<p align="center">
  <a aria-label="Sponsors" href="#sponsors">
    <img
      src="https://img.shields.io/badge/SPONSORS-brightgreen.svg?style=for-the-badge&logo=github-sponsors&logoColor=white&labelColor=000000&logoWidth=20">
  </a>
</p>

> This project is developed with vite and vue3. Those are frameworks which provide better behavior and performance under the support of node.js.
## How to run this locally
### Preparation for node.js:
- Windows: install node.js from https://nodejs.org/ recommend version is `18.20`.
- Other:Open a terminal and run the following commands:
    ```bash
    curl -fsSL https://deb.nodesource.com/setup_lts.x | sudo -E bash -
    sudo apt-get install -y nodejs
    ```
### Installation:
- Step 1: run `npm install` to install packages from package.json
- Step 2: run `npm run dev` to start the server at port 80. It is recommended to use sudo or with administrator permission.
- Step 3: The website should now start at port:80. You can your browser can visit: http://localhost:80
## Root Folder Structure
- `/api`: The website is deployed on vercel and this is the place for vercel to reply the request from cloudflare captcha(turnstile) via `validate-captcha.js`.
- `/dist`: This folder will appear after you build the website. It has no relationship with raw code.
- `/node_modules`: This folder is home of modules and it will also appear after `npm install`.
- `/public`: This is used by vite and if there is an error, it will show a page to report with this vite logo.
- `/src`: This is the core of website. I will introduce it later.
- `/index.html`: It is ⚠️ not ⚠️ the real main webpage. The real one is at the src folder.
- `/packages.json` & `/package` : This is the configuration of node.js framework.
- `/vite.config.js` : This is the configuration of vite.
- ## `/src` Folder Structure (Main Code Structure)
- `/src/assets`: This is the resource folder for the whole and contain sources like images and main css: `styles.css`. It offers such as fonts and other customise configuration.
- `/src/components`: This is 
- `/src/router`: This is the router of the whole website. This website has a routing structure and the `index.js` in it tells the main program where to find each page.
- `/src/views`: This is the folder of each pages. ⚠️ Mention that all the pages with vue framework are not html documents but vue documents. ⚠️ 
- `/src/App.vue`: This is the main template of other pages.
- `/src/global.css`: This is global setting css.
- `/src/main.js`: This is the router.
- `/src/style.css`: This is an additional setting for some thorny elements.
## For Criteria
### 1. Responsive website
- You can use different device to test this via your local IP address on port : 80 or visit https://game.lkx666.cn .
- Alternatively you can just adjust the size of your browser, but mention that minor changes may not be noticeable. It is better to make sure that the width of the page is under 1280px.
### 2. CSS usage
- If you put you cursor hover on the card elements, it'll float.
- The position of elements are also controlled by css style
- There are huge amount of selector in these vue documents and you can easily find a lot of them.
- Responsive design are located at the bottom of the vue document which uses `@media`.
### 3. JavaScript usage
- A lot of interactions and comments are used. For example at `Contact.vue` part, I marked this part and tell myself to add more countries here.
- A great number of functions are use in the website.<br>1. Time function for clock at `Home.vue`.<br>2&3. Several functions for the pop-up at `Home.vue`.<br>4. Warning of external link at `News.vue`.<br>5+. And more...
### 4. HTML usage
- A lot of labels such as dir, section or a and more are used.
- Some pictures are added in the website even in this `README.md`.
### 5. Overall website
- The website is tested by a lot of volunteers and get great reflection.
- You can easily jump to anywhere and easy to get a quick feedback.
## Thanks
- Thank you to read here. I wish you will have a good day.
