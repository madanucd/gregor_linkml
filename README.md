# gregor_linkml

This repository includes the LinkML model and tooling for the GREGoR data model.

## Website

[https://madanucd.github.io/gregor_linkml](https://madanucd.github.io/gregor_linkml)

## Repository Structure

* [examples/](examples/) - example data
* [project/](project/) - project files (do not edit these)
* [src/](src/) - source files (edit these)
  * [gregor_linkml](src/gregor_linkml)
    * [schema](src/gregor_linkml/schema) -- LinkML schema
      (edit this)
    * [datamodel](src/gregor_linkml/datamodel) -- generated
      Python datamodel
* [tests/](tests/) - Python tests

## Developer Documentation

<details>
Use the `make` command to generate project artefacts:

* `make all`: make everything
* `make deploy`: deploys site
</details>

## Credits

This project was made with
[linkml-project-cookiecutter](https://github.com/linkml/linkml-project-cookiecutter).
