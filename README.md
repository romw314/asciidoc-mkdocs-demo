# asciidoc-mkdocs-demo

Sample content to test an asciidoc > pandoc > markdown > MKDocs workflow

Basic set up: 

    pip install mkdocs

    pip install mkdocs-material

    pip install mkdocs-git-revision-date-localized-plugin

    mkdir docs

    asciidoctor -b docbook -a leveloffset=+1 -o - master.adoc | pandoc  --atx-headers --wrap=preserve -t markdown_strict -f docbook - > docs/index.md

## TODO

* Generate page navigation from master.adoc
* Set up the github action to run asciidoctor command
* Set up the github action to serve via mkdocs to github pages


