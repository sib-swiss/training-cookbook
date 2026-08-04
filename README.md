# SIB training cookbook

Hosted at [https://sib-swiss.github.io/training-cookbook](https://sib-swiss.github.io/training-cookbook). 

## How to develop locally

This website is generated with [Zensical](https://zensical.org/), the successor to MkDocs built by the Material for MkDocs team, reading the existing `mkdocs.yml` configuration.

To host it locally, clone this repository including the flowchart submodule:

```bash
git clone --recurse-submodules https://github.com/sib-swiss/training-cookbook.git
```

Then, install `zensical` (ideally in a virtual environment):
```bash
pip install zensical
```

To run the website locally, you can use:

```bash
zensical serve
```

Check it out with your browser at [http://localhost:8000/](http://localhost:8000/).

To build a static version of the site (e.g. to check the output before pushing):

```sh
zensical build --clean
```

This generates the site in the `site/` directory. On push to `main`, the [build-site workflow](.github/workflows/build_site.yml) builds the site with Zensical and publishes it to GitHub Pages automatically at:

https://sib-swiss.github.io/training-cookbook

