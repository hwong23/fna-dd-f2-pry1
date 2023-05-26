# PRY01. Gobierno SOA del FNA      

<!-- usage note: edit the H1 title above to personalize the manuscript -->

[![HTML Manuscript](https://img.shields.io/badge/manuscript-HTML-blue.svg)](https://hwong23.github.io/fna-dd-f2-pry1/)
[![PDF Manuscript](https://img.shields.io/badge/manuscript-PDF-blue.svg)](https://hwong23.github.io/fna-dd-f2-pry1/manuscript.pdf)
[![GitHub Actions Status](https://github.com/hwong23/fna-dd-f2-pry1/workflows/Manubot/badge.svg)](https://github.com/hwong23/fna-dd-f2-pry1/actions)

## Manuscript description

<!-- usage note: edit this section. -->

This repository is a template manuscript (a.k.a. rootstock).
Actual manuscript instances will clone this repository (see [`SETUP.md`](SETUP.md)) and replace this paragraph with a description of their manuscript.


### Continuous Integration

Whenever a pull request is opened, CI (continuous integration) will test whether the changes break the build process to generate a formatted manuscript.
The build process aims to detect common errors, such as invalid citations.
If your pull request build fails, see the CI logs for the cause of failure and revise your pull request accordingly.

When a commit to the `main` branch occurs (for example, when a pull request is merged), CI builds the manuscript and writes the results to the [`gh-pages`](https://github.com/hwong23/fna-dd-f2-pry1/tree/gh-pages) and [`output`](https://github.com/hwong23/fna-dd-f2-pry1/tree/output) branches.
The `gh-pages` branch uses [GitHub Pages](https://pages.github.com/) to host the following URLs:

+ **HTML manuscript** at https://hwong23.github.io/fna-dd-f2-pry1/
+ **PDF manuscript** at https://hwong23.github.io/fna-dd-f2-pry1/manuscript.pdf

For continuous integration configuration details, see [`.github/workflows/manubot.yaml`](.github/workflows/manubot.yaml).

## License

<!--
usage note: edit this section to change the license of your manuscript or source code changes to this repository.
We encourage users to openly license their manuscripts, which is the default as specified below.
-->

[![License: CC BY 4.0](https://img.shields.io/badge/License%20All-CC%20BY%204.0-lightgrey.svg)](http://creativecommons.org/licenses/by/4.0/)
[![License: CC0 1.0](https://img.shields.io/badge/License%20Parts-CC0%201.0-lightgrey.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

Except when noted otherwise, the entirety of this repository is licensed under a CC BY 4.0 License ([`LICENSE.md`](LICENSE.md)), which allows reuse with attribution.
Please attribute by linking to https://github.com/hwong23/fna-dd-f2-pry1.

Since CC BY is not ideal for code and data, certain repository components are also released under the CC0 1.0 public domain dedication ([`LICENSE-CC0.md`](LICENSE-CC0.md)).
All files matched by the following glob patterns are dual licensed under CC BY 4.0 and CC0 1.0:

+ `*.sh`
+ `*.py`
+ `*.yml` / `*.yaml`
+ `*.json`
+ `*.bib`
+ `*.tsv`
+ `.gitignore`

All other files are only available under CC BY 4.0, including:

+ `*.md`
+ `*.html`
+ `*.pdf`
+ `*.docx`

Please open [an issue](https://github.com/hwong23/fna-dd-f2-pry1/issues) for any question related to licensing.
