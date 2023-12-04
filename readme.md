# Motivation

This repo is a perfect solution when you need to develop a new website/templates based on [Tailwindcss](https://tailwindcss.com/) without any extra configuration or just for learning purposes.

## Requirements

- [Node](https://nodejs.org/en/) `^16.15.0`
- [NPM](https://www.npmjs.com/) `^8.5.5`
- [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) `latest`

## Installation

After confirming that your environment meets the above [requirements](#requirements),
it is time to clone the project locally by doing the following:

```bash
$ git clone https://github.com/DeanHristov/simple-tailwind-starter-kit.git <project-name>
$ cd <project-name>
```

When you're done with the steps above, run the following command:

```bash
$ npm install # or yarn install
```

```
├── dist                # Contains **production-ready** code.
│   └── index.html      # The entry page of the site
│   └── *.html          # Sub-pages
│   └── css             # Contains all compiled styles
│       └── style.css   # the Main style. It is used from the index.html
├── package.json        # It holds important metadata about the project
├── input.css           # The entry point of tailwindcss
├── package-lock.json   # Place where we controls the dependencies
├── README.md           # A documentation file
```

## Main tasks

All tasks automation are based on [NPM scripts](https://docs.npmjs.com/misc/scripts).

| Tasks           | Description                                      |
| --------------- | ------------------------------------------------ |
| `npm run watch` | Watching the styles for changes                  |
| `npm run build` | Building the styles in **production-ready** mode |

## Running the styles in development mode.

```bash
$ npm run watch
```

In order to open the page you can use any live server. For example, this could be a
[Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)

## Build the styles in production mode.

Compiling the styles in production-ready mode in **~/dist** directory.

```bash
$ npm run build
```

## Used technologies

- [NodeJS](https://nodejs.org/en/)
- [Git](https://git-scm.com/)
- [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)

## NPM Packages

- [tailwindcss](https://www.npmjs.com/package/tailwindcss)

## Made by

Author: [D. Hristov](https://dhristov.eu/)
