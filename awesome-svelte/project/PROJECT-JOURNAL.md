#Project Journal


# Steps 1
## Day 1: 5/1
- ` npm create svelte@latest ( project name ) `
- Install app dependencies : See List from reources/section 2.

# Step 2
## Day 2: 5/2
### One time steps.
- Created Netlify team : ntl.idevforweb
- installed globaly netlify with : ` sudo npm install netlify-cli --location=global `

### Project Steps ( needed in every project )
- Update import statement to ` import adapter from '@sveltejs/adapter-netlify' ` in svelte.config.js
- In app root dir: ` npm i netlify-cli --save-dev ` 
- Added netlify.toml with commands:
    [build]
    command = "vite build"
    publish = "build"
- Install Netlify adapter : ` npm i -D @sveltejs/adapter-netlify@next `
- open netlify account in browser 
- In command prompt run:
netlify sites:create
npm run build
ntl deploy
- At this point use ntl dev 


# Next Steps 
Resolve errors
Start here:https://stackoverflow.com/questions/75817687/svelte-not-generating-public-or-dist-folder-with-vite
Learn How to 
