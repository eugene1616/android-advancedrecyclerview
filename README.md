Documentation source of Advanced RecyclerView library
===

## What's this branch?

This branch contains GitHub Pages source of Advanced RecyclerView.

## Prerequisites

- `pipenv`

## Setup

1. Install prerequisite softwares
2. Clone this repository.

  ```bash
  git clone -b gh-pages-source --recurse-submodules git@github.com:h6ah4i/android-advancedrecyclerview.git android-advancedrecyclerview-gh-page
  ```
3. Install python packages
  ```bash
  ./scripts/setup.sh
  ```

## How to develop the page contents?

1. Run mkdocs in server mode
  ```bash
  ./scripts/dev.sh
  ```

2. Open `http://127.0.0.1:8000/` in your browser

3. Modify files in the `/content` directory.


## How to deploy?

```bash
./scripts/deploy.sh
```
