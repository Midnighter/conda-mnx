# Conda-MNX

[![master Build Status](https://travis-ci.org/Midnighter/conda-mnx.svg?branch=master)](https://travis-ci.org/Midnighter/conda-mnx)
[![Docker image pulls](https://img.shields.io/docker/pulls/midnighter/conda-mnx)](https://cloud.docker.com/repository/docker/midnighter/conda-mnx/)
[![License](https://img.shields.io/badge/license-Apache--2.0-blueviolet)](https://opensource.org/licenses/Apache-2.0)

The `midnighter/conda-mnx` Docker image exposes a collection of Python conda
packages centered around working with [MetaNetX](https://metanetx.org/) that is
[metanetx-sdk](https://pypi.org/project/metanetx-sdk/),
[metanetx-assets](https://pypi.org/project/metanetx-assets/), and
[metanetx-post](https://pypi.org/project/metanetx-post/).

## Usage

Run the image and take a look at the commands described in the help text.

```
docker run --rm midnighter/conda-mnx:latest mnx-sdk --help
docker run --rm midnighter/conda-mnx:latest mnx-assets --help
docker run --rm midnighter/conda-mnx:latest mnx-post --help
```

## Copyright

* Copyright © 2020, Moritz E. Beber.
* Free software licensed under the [Apache License, Version 2.0](LICENSE).
