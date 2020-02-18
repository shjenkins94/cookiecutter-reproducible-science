{{cookiecutter.project_name}}
==============================

{{cookiecutter.project_short_description}}

Project Organization
--------------------
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
