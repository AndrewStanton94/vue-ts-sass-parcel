# Vue, Typescript, SASS and Parcel template

An opinionated template based on the files I've set up previously.

It uses

- [Parcel](https://parceljs.org/): Asset bundler
- [Vue](https://vuejs.org): front end framework
- [TypeScript](https://www.typescriptlang.org): development language
- [SASS](https://sass-lang.com/): CSS preprocessor

## How to use

1. [Install parcel](https://parceljs.org/getting_started.html) with `npm install -g parcel-bundler`
1. Go to [github.com/andrewstanton94/vue-ts-sass-parcel](https://github.com/AndrewStanton94/vue-ts-sass-parcel)
1. Create repo from template
1. Clone it
1. Run `npm init` to generate the package.json file
	- Use [this page](https://spdx.org/licenses/) to get the SPDX licence code. E.g. `GPL-3.0-or-later`
1. Add these sections to the `package.json` file
	```javascript
	"scripts": {
		"start": "parcel src/index.html"
	},
	"dependencies": {
		"bulma": "^0.8.0",
		"vue": "^2.6.10",
		"vue-hot-reload-api": "^2.3.4"
	},
	"devDependencies": {
		"@vue/component-compiler-utils": "^3.0.2",
		"eslint": "^6.7.2",
		"eslint-plugin-vue": "^6.0.1",
		"parcel-bundler": "^1.12.4",
		"sass": "^1.23.7",
		"typescript": "^3.7.3",
		"vue-template-compiler": "^2.6.10"
	}
	```
1. Run `npm install` to get dependencies
	- Parcel can detect and install missing dependencies but I had issues when I skipped this step initially.
1. Run `npm start` to begin developing
1. Replace this file with a relevant README
