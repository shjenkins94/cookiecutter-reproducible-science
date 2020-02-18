Reproducible Science
====================

A boilerplate for reproducible and transparent science with close resemblances to the philosophy of [Cookiecutter Data Science](https://github.com/drivendata/cookiecutter-data-science): *A logical, reasonably standardized, but flexible project structure for doing and sharing data science work.*

Requirements
------------
Install `cookiecutter` command line: `pip install cookiecutter`    

Usage
-----
To start a new science project:

`cookiecutter gh:shjenkins94/cookiecutter-reproducible-science`

Project Structure
-----------------

```
.
├── bin                   <- Most code goes here.
│   ├── external          <- Any external source code, like git repos or
|   |                        libraries (ignored)
|   |   └── README.md     <- Source of any external source code.
│   ├── src               <- Anything that needs to be compiled
│   ├── tools             <- Any helper scripts go here.
│   └── visualization     <- Scripts for visualisation of results.
├── config                <- Configuration files.
|   └── environment.yaml  <- conda env export
├── data
|   ├── Makefile          <- File that does simple data processing.
│   ├── external          <- Data from third party sources.
│   |   └── README.md     <- Source of any external data.
│   ├── intermediate      <- Intermediate data that has been transformed.
│   ├── practice          <- Data used to try things out and test code.
│   ├── raw               <- Original proprietary data.
│   └── target            <- The final product.
├── docs                  <- Text things go here
│   ├── notebooks         <- Ipython or R notebooks.
│   └── reports           <- For a manuscript source.
│       └── figures       <- Figures for the manuscript or reports
├── AUTHORS.md
├── LICENSE
└── README.md
```

Check out my latest research project, which successfully applied the `cookiecutter` philosophy: [SEMIC: an efficient surface energy and mass balance model applied to the Greenland ice sheet](https://gitlab.pik-potsdam.de/krapp/semic-project).

License
-------
This project is licensed under the terms of the [BSD License](/LICENSE)
