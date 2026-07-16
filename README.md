# Bootstrap Training

Personal exercises and mini-projects from a Udemy "Bootstrap 4" course. Contains a series of standalone HTML/CSS pages practicing individual Bootstrap 4 features (grid, flex, navbars, jumbotron, images, text utilities) plus a few small practice projects built on top of them.

## Tech Stack

- Bootstrap 4.4.1 (vendored locally under `bootstrap/`)
- jQuery 3.4.1 and Popper.js 1.12.9 (vendored per-lesson)
- Plain HTML/CSS — no build tools or package manager

## Running

Every lesson/project is a self-contained set of static HTML files with local CSS/JS — no install step needed. Either open a file directly in the browser:

```bash
open 05/flex.html
```

or serve the whole folder and navigate in-browser:

```bash
npx http-server .
```

## Project Structure

```
01/ .. 07/     Numbered lesson exercises (grid, text, images, flex/nesting, navbar/buttons/jumbotron/slider, etc.)
bootstrap/     Vendored copies of Bootstrap 4.4.1, jQuery, and Popper.js
projects/      Practice mini-projects:
  01WatchLangingPage/       Watch product landing page
  02CodeIsAwesome/          "Code is Awesome" landing page
  02CodeIsAwesomeAssignment/  Assignment variant of the above
  03LoginScreen/            Login screen UI
```
