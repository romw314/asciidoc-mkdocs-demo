# Asciidocs MKDocs Static Site Demo

## Getting Started

This document is sample asciidoc content used to test a github pages based asciidoc static site generated with pandoc and MKDocs.

![Image](images/image.png)

## Asciidoc syntax sample

-   level 1

    -   level 2

        -   level 3

            -   level 4

                -   level 5

-   level 1

<https://asciidoctor.org> - automatic!

[Asciidoctor](#:https://asciidoctor.org)

[Asciidoctor @ **GitHub**](#:https://github.com/asciidoctor)

    require 'sinatra' 

    get '/hi' do 
    "Hello World!" 
    end

-   Library import

-   URL mapping

-   HTTP response body

Tables
Table with a title, three columns, a header, and two rows of content:

<table>
<caption>Table Title</caption>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th>Name of Column 1</th>
<th>Name of Column 2</th>
<th>Name of Column 3</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Cell in column 1, row 1</p></td>
<td><p>Cell in column 2, row 1</p></td>
<td><p>Cell in column 3, row 1</p></td>
</tr>
<tr class="even">
<td><p>Cell in column 1, row 2</p></td>
<td><p>Cell in column 2, row 2</p></td>
<td><p>Cell in column 3, row 2</p></td>
</tr>
</tbody>
</table>

Admonitions
AsciiDoc provides five admonition style labels out-of-the-box:

Please note that…​

Pro tip…​

Don’t forget…​

Watch out for…​

Ensure that…​
Admonitions can also encapsulate any block content:

While werewolves are hardy community members, keep in mind the following dietary concerns:

bold **constrained** & **un**constrained

monospace bold `*constrained*` & \`\`**un**\`\`constrained

monospace italic `_constrained_` & \`\`*un*\`\`constrained

monospace bold italic `*_constrained_*` & \`\`***un***\`\`constrained

## Level 1 Section Title

italic *constrained* & *un*constrained

bold italic ***constrained*** & ***un***constrained

monospace `constrained` & \`\`un\`\`constrained

### Level 2 Section Title

italic *constrained* & *un*constrained

#### Level 3 Section Title

italic *constrained* & *un*constrained

bold italic ***constrained*** & ***un***constrained

monospace `constrained` & \`\`un\`\`constrained

##### Level 4 Section Title

More text

###### Level 5 Section Title

Text

## Another Level 1 Section Title

And text.
