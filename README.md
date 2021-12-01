# generator-html-scss-js

- This is for anyone who wanna use this for web development
- This package includes languages such as `scss`, `js` and `html`

## Info
Generator-html-scss-js is being depreceated. Thiss is the **SUCCESSOR** of that generator. Please install this.

## Installation

First, install [Yeoman](http://yeoman.io) and generator-html-scss-js using [npm](https://www.npmjs.com/) (I assume you have pre-installed [node.js](https://nodejs.org/)).

``` bash
npm install -g yo
npm install -g generator-html-scss-js-2
```

> Install `yo` one time only

Then generate a new project in your respective directory:

```bash
yo html-scss-js
```

## Folder structure

``` bash
bash
generator-html-scss-js
├─ .editorconfig
├─ .eslintignore
├─ .git
├─ .gitattributes
├─ .gitignore
├─ .travis.yml
├─ generators
│ └─ app
│ ├─ index.js Main process happend
│ └─ templates
│ ├─ .gitignore
│ ├─ app
│ │ ├─ js
│ │ │ └─ script.js
│ │ └─ scss
│ │ ├─ style.scss
│ │ └─ \_variables.scss
│ ├─ gulpfile.js Compile scss-css, copy files to their own dir
│ ├─ index.html
│ ├─ package-lock.json
│ ├─ package.json
│ └─ \_gitignore
├─ LICENSE
├─ package-lock.json
├─ package.json
├─ README.md
└─ **tests**
└─ app.js

## Friendly Reminder

- If you want to update to a newer version, please check the github repo to check whether are there any problems.
- Please update the package every month. Run `npm update generator-html-scss-js-2 -g`
- If you encounter any issue, please file an issue at the repo :)
- Pull request is always welcome :D
