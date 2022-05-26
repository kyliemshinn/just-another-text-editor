# just-another-text-editor

https://damp-sea-79721.herokuapp.com/

![License](https://img.shields.io/badge/License-MIT-yellow.svg)

![GitHub language count](https://img.shields.io/github/languages/count/kyliemshinn/just-another-text-editor)

## Table of Contents

- [Description](#description)
- [Criteria](#criteria)
- [Installation](#installation)
- [Usage](#usage)
- [Tests](#tests)
- [Technologies Used](#technologies-used)
- [Contributors](#contributors)
- [Questions](#questions)
- [License](#license)

## Description

JATE is a text editor that is meant to be simple to use, and accessible even when offline.


## Criteria

```
GIVEN a text editor web application
WHEN I open my application in my editor
THEN I should see a client server folder structure
WHEN I run `npm run start` from the root directory
THEN I find that my application should start up the backend and serve the client
WHEN I run the text editor application from my terminal
THEN I find that my JavaScript files have been bundled using webpack
WHEN I run my webpack plugins
THEN I find that I have a generated HTML file, service worker, and a manifest file
WHEN I use next-gen JavaScript in my application
THEN I find that the text editor still functions in the browser without errors
WHEN I open the text editor
THEN I find that IndexedDB has immediately created a database storage
WHEN I enter content and subsequently click off of the DOM window
THEN I find that the content in the text editor has been saved with IndexedDB
WHEN I reopen the text editor after closing it
THEN I find that the content in the text editor has been retrieved from our IndexedDB
WHEN I click on the Install button
THEN I download my web application as an icon on my desktop
WHEN I load my web application
THEN I should have a registered service worker using workbox
WHEN I register a service worker
THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets
WHEN I deploy to Heroku
THEN I should have proper build scripts for a webpack application
```


## Installation

The user will need to clone down the repository and then run `npm install` to get all the necessary packages for the app to work on the local machine. Please reference the package.json file outside of all the folders to reference how to run the client, server, and webpack.

If the new user would like to deploy their own link, the original was deployed through Heroku.


## Usage

This is a deployed application, so the user will just need to open the link in browser to utilize the web app. To view the cached data, the user will need to navigate to the console, click on the applications tab, and 

## Technologies Used

- Javascript
- HTML5
- CSS
- Node.js
- Express.js
- Webpack
- Babel
- idb

## Contributors

The server, and styling of the front-end of this web application was created by UC Berkeley Extension School.

The remaining portions to the code was created by Kylie Shinn.

- GitHub: [github](https://github.com/kyliemshinn)
- LinkedIn: [linkedin](https://www.linkedin.com/feed/)

## Questions

For additional information please contact me at:
Email: kyliemshinn@gmail.com

## License

MIT License

Copyright (c) [2022] [Kylie Shinn]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.