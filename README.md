# GMIC Email Template

This is the email template for US-based GMIC newsletters. Uses [Foundation for Emails](http://foundation.zurb.com/emails) to rapidly build responsive HTML emails that work in any email client. It has a Gulp-powered build system with these features:

- Handlebars HTML templates with [Panini](http://github.com/zurb/panini)
- Simplified HTML email syntax with [Inky](http://github.com/zurb/inky)
- Sass compilation
- Image compression
- Built-in BrowserSync server
- Full email inlining process

## Installation

To use this template, your computer needs [Node.js](https://nodejs.org/en/) 0.12 or greater.

### Setup

To get started with the template, first download it with Git:

```bash
git clone https://github.com/peterlegwc/gmic-emails-foundation.git projectname
```

Then open the folder in your command line, and install the needed dependencies:

```bash
cd projectname
npm install
```

### Build Commands

Run `npm start` to kick off the build process. A new browser tab will open with a server pointing to your project files.

Run `npm run build` to inline your CSS into your HTML along with the rest of the build process.

## Templating

Templating documentation can be found on the [Foundation for Emails](http://foundation.zurb.com/emails/docs/) docs.

Some templates contain markup for Pardot tags (such as title, view online link, and unsubscribes). Adjust accordingly for other email tools.
