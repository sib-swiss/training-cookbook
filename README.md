# SIB training cookbook

Hosted at [https://sib-swiss.github.io/training-cookbook](https://sib-swiss.github.io/training-cookbook). 

## How to develop locally

This website is generated with [MkDocs](https://www.mkdocs.org/), with the theme [Material](https://squidfunk.github.io/mkdocs-material/).

To host it locally, clone this repository including the flowchart submodule:

```bash
git clone --recurse-submodules
```

Then, install `mkdocs-material`:
```bash
pip install mkdocs-material
```

To run the website locally, you can use:

```bash
mkdocs serve
```

Check it out with your browser at [http://localhost:8000/](http://localhost:8000/).

For an automatically generated github page, you can run:

```sh
mkdocs gh-deploy
```

This will generate a webpage at:

https://yourname.github.io/reponame

