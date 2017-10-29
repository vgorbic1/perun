# Perun
A Foundation front-end website theme.

![http://perun.gorbich.com](http://perun.gorbich.com/img/demo.jpg)

## Demo
[perun.gorbich.com](http://hyperbola.gorbich.com)

## Description
Perun is a front-end theme created from a mock-up. The theme is created with Foundation CSS framework and Sass.

The theme is inspired by [Brad Traversy](http://www.traversymedia.com/)'s BThosting theme.

## Setup
To use this template, your need:

- [NodeJS](https://nodejs.org/en/) (0.12 or greater)
- [Git](https://git-scm.com/)

This template can be installed with the Foundation CLI, or downloaded and set up manually.

### Using the CLI

Install the Foundation CLI with this command:

```bash
npm install foundation-cli --global
```

Use this command to set up a blank Foundation for Sites project with this template:

```bash
foundation new --framework sites --template basic
```

The CLI will prompt you to give your project a name. The template will be downloaded into a folder with this name.

### Manual Setup

To manually set up the template, first download it with Git:

```bash
git clone https://github.com/zurb/foundation-sites-template projectname
```

Then open the folder in your command line, and install the needed dependencies:

```bash
cd projectname
npm install
bower install
```

Finally, run `npm start` to run the Sass compiler. It will re-run every time you save a Sass file.
