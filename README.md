# Minimalistic Reader

![Tesla Model 3 Search Results](https://i.imgur.com/W4DRwiS.png)

>Visual metasearch engine built with React, Redux, Express, and TypeScript.

[Live link to site](http://spresso-search.herokuapp.com/)

## About
Minimalistic Reader scrapes search results from Google using the [node x-ray](https://github.com/matthewmueller/x-ray) library, and uses the same library to scrape obtain meta-information on webpages (preview images, favicons). There is a screenshot feature, which takes screenshots of sites that don't have meta preview images in their HTML. There is also a text-outline feature, powered by [node-unfluff](https://github.com/ageitgey/node-unfluff), which scrapes text content from web pages(ideal for articles & other text-rich pages), allowing the user to read the contents of a web page in clean, formatted text and without leaving the Minimalistic Reader site.

## Running Locally
To run Minimalistic Reader locally, first clone the repo with: `git clone https://github.com/hkharsh/minimalistic-reader.git`


Then `cd` into its directory:  `cd Minimalistic Reader`

Install the dependencies with `npm install`

Then run `npm start` to run the client side code. The app should be visible on port 3000.

Open a new terminal tab/window in the same directory, and run `cd server` to go into the server directory.

Run `node ./build/server.js` to start the server. The app is now ready for use.

If making any modifications to the server's TypeScript code, you should start the TypeScript compiler in watch mode with

 `tsc -w` so your changes can be tracked in the JS build.



