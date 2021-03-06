nbprocess
================

<!-- WARNING: THIS FILE WAS AUTOGENERATED! DO NOT EDIT! -->

[![CI](https://github.com/fastai/nbprocess/actions/workflows/test.yaml/badge.svg)](https://github.com/fastai/nbprocess/actions/workflows/test.yaml)
[![Deploy to GitHub
Pages](https://github.com/fastai/nbprocess/actions/workflows/deploy.yaml/badge.svg)](https://github.com/fastai/nbprocess/actions/workflows/deploy.yaml)

This will become v2 of nbdev in the near-ish future.

## Install

With pip:

    pip install nbprocess

With conda:

    conda install -c fastai nbprocess

## How to use

By default docs are exported for use with [Quarto](https://quarto.org/).
To install Quarto on Ubuntu, run `nbprocess_install`. See the Quarto
docs for other platforms.

You can run `nbprocess_help` from the terminal to see a list of all CLI
tools:

``` python
!nbprocess_help
```

    nbprocess_bump_version          Increment version in `settings.py` by one
    nbprocess_clean                 Clean all notebooks in `fname` to avoid merge conflicts
    nbprocess_conda                 Create and upload a conda package.
    nbprocess_create_config         Creates a new config file for `lib_name` and `user` and saves it.
    nbprocess_deploy                Deploy docs to GitHub Pages.
    nbprocess_docs                  Generate the docs.
    nbprocess_export                Export notebooks in `path` to python modules
    nbprocess_filter                A notebook filter for quarto
    nbprocess_fix                   Create working notebook from conflicted notebook `nbname`
    nbprocess_ghp_deploy            Deploy docs in doc_path from settings.ini to GitHub Pages
    nbprocess_help                  Show help for all console scripts
    nbprocess_install               Install quarto and the current library.
    nbprocess_install_hooks         Install git hooks to clean/trust notebooks automatically
    nbprocess_install_quarto        Installs latest quarto on mac or linux.  Prints instructions for Windows.
    nbprocess_migrate_directives     Convert all directives in `fname` from v1 to v2.
    nbprocess_new                   Create a new project from the current git repo
    nbprocess_prepare               Export notebooks to python modules, test code and clean notebooks.
    nbprocess_preview               Start a local docs webserver.
    nbprocess_pypi                  Create and upload python package to pypi.
    nbprocess_quarto                Create quarto docs and README.md
    nbprocess_release               Release both conda and pypi packages.
    nbprocess_sidebar               Create sidebar.yml
    nbprocess_test                  Test in parallel the notebooks matching `fname`, passing along `flags`
    nbprocess_trust                 Trust notebooks matching `fname`
    nbprocess_update                Propagates any change in the modules matching `fname` to the notebooks that created them
