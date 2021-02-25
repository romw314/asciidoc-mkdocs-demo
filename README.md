# asciidoc-mkdocs-demo

Sample content to test an asciidoc > pandoc > markdown > MKDocs workflow

Basic set up: 

    pip install mkdocs

    pip install mkdocs-material

    pip install mkdocs-git-revision-date-localized-plugin

    mkdir docs

    cp -r images docs/images

    asciidoctor -b docbook -a leveloffset=+1 -o - master.adoc | pandoc  --atx-headers --wrap=preserve -t markdown_strict -f docbook - > docs/index.md

    mkdocs serve

## TODO

* Generate page navigation from master.adoc into mkdocs.yml

for example: 

```
# Page tree
nav:
  - Home: index.md
  - Getting started:
    - Installation: getting-started.md
    - Creating your site: creating-your-site.md
    - Publishing your site: publishing-your-site.md
    - Customization: customization.md
    - Troubleshooting: troubleshooting.md
    - Data privacy: data-privacy.md
    - Insiders: insiders.md
    - License: license.md
```

* Set up the github action to run asciidoctor command
* Set up the github action to serve via mkdocs to github pages
* Ensure in doc xref linking works


