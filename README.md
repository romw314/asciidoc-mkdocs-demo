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

* CAVEAT: modules must use second level headings below document title
* CAVEAT: master.adoc must be named master.adoc
* CAVEAT: images folder must be named images
* Set up the github action to run asciidoctor command
* Set up the github action to serve via mkdocs to github pages
* Ensure in doc xref linking works


