# ACROSS

# ACROSS

This is not an officially supported Google product

This repository contains code and related content for the ACROSS Taxonomy Project, including Workshops and Research, as part of Project OCEAN. 

## [Project OCEAN Overview/Goal](https://vermontcomplexsystems.org/partner/OCEAN/)
Project OCEAN is an open science collaboration focused on understanding the open source ecosystems creating datasets that enable research and forming a clear understanding of the state of open source communities. OCEAN’s goal is to understand the health of the open source communities.


## [ACROSS](https://bit.ly/across-workshop-community-pitch)
The ACROSS workshops allow open source communities to create and publish community-generated contribution documentation for open source ecosystems, clarifying who is present in open source and the impact they have.

For future updates on new work and more ACROSS opportunities, please join our mailing list [across-opensource-workshops@](https://groups.google.com/g/across-opensource-workshops).

## Source Code Headers

Every file containing source code must include copyright and license
information. This includes any JS/CSS files that you might be serving out to
browsers. Please make sure to add the following to any files you submit.

Apache header:

    Copyright 2022 Google LLC

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        https://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

## Local development

This site uses [Jekyll](https://jekyllrb.com/), a Ruby-based static site generator. 

Deployment previews are automated with [netlify](https://www.netlify.com/) (see comments automatically added to new PRs).

It uses GitHub Actions `.github/publish.yaml` to generate static content that is served by the Settings > Pages setting. 

For location development, with a [Ruby installation](https://www.ruby-lang.org/en/documentation/installation/) and [bundler](https://bundler.io/guides/getting_started.html): 

```
bundle install
bundle exec jekyll serve -lo
```