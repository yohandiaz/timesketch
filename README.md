# Timesketch
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/google/timesketch/blob/master/notebooks/colab-timesketch-demo.ipynb)
[![Open In Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/google/timesketch/master?urlpath=%2Flab)


[![Version](https://img.shields.io/pypi/v/timesketch.svg)](https://pypi.python.org/pypi/timesketch)
[![Version API](https://img.shields.io/pypi/v/timesketch_api_client.svg)](https://pypi.python.org/pypi/timesketch_api_client)
[![Version Import](https://img.shields.io/pypi/v/timesketch_import_client.svg)](https://pypi.python.org/pypi/timesketch_import_client)

[![Tweet](https://img.shields.io/twitter/url/http/shields.io.svg?style=social)](https://twitter.com/intent/tweet?text=Digital%20Forensic%20Timeline%20Analysis&url=https://github.com/google/timesketch/&via=jberggren&hashtags=dfir)

![](https://github.com/google/timesketch/workflows/timesketch-end-to-end/badge.svg)
![](https://github.com/google/timesketch/workflows/pipenv%20unittests/badge.svg)
![](https://github.com/google/timesketch/workflows/ppa%20unittests/badge.svg)


## Table of Contents
1. [About Timesketch](#about-timesketch)
2. [Getting started](#getting-started)
3. [Community](#community)
4. [Contributing](#contributing)

## About Timesketch
Timesketch is an open source tool for collaborative forensic timeline analysis. Using sketches you and your collaborators can easily organize your timelines and analyze them all at the same time.  Add meaning to your raw data with rich annotations, comments, tags and stars.

<img src="https://01dd8b4c-a-62cb3a1a-s-sites.googlegroups.com/site/timesketchforensics/about/timesketch-201708.png" alt="Timesketch" width="1000"/>

## Getting started

#### Installation
* [Install Timesketch manually](docs/Installation.md)
* [Use Docker](docker/)
* [Upgrade from existing installation](docs/Upgrading.md)

#### Adding timelines
* [Create timeline from JSON/JSONL/CSV file](docs/CreateTimelineFromJSONorCSV.md)
* [Create timeline from Plaso file](docs/CreateTimelineFromPlaso.md)
* [Enable Plaso upload via HTTP](docs/EnablePlasoUpload.md)
* [Use the API client to upload data](docs/UploadDataViaAPI.md)
* [Import other data](docs/CreateTimeLineFromOtherData.md)

#### Using Timesketch
* [Users guide](docs/Users-Guide.md)
* [Using Sigma Analyzer](docs/UseSigmaAnalyzer.md)

## Community
* [Community guide](docs/Community-Guide.md)

## Contributing
* [Prerequisites](CONTRIBUTING.md)
* [Developers guide](docs/Developers-Guide.md)

---

##### Obligatory Fine Print
This is not an official Google product (experimental or otherwise), it is just code that happens to be owned by Google.
