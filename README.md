Headers:

# H1

    # H1

## H2

    ## H2

### H3

    ### H3

#### H4

    #### H4

##### H5

    ##### H5

###### H6

    ###### H6

# Emphasis

## Italics

_asterisks_ or _underscores_.

    _asterisks_ or _underscores_.

### Strong Emphasis, AKA Bold

**asterisks** or **underscores**.

    **asterisks** or **underscores**.

### Combined emphasis

**asterisks and _underscores_**.

    **asterisks and _underscores_**.

### Strikethrough

two tildes. ~~Scratch this.~~

    two tildes. ~~Scratch this.~~

### Lists

    Ordered List

1.  Renders as
1.  an ascending
1.  list from 1
1.  to 4

    1.  sub list
    1.  Second sub-item

    <br>
        1.  Renders as
        1.  an ascending
        1.  list from 1
        1.  to 4

<br/ comment:"This tag ended the list.">

      Unordered List

- Unordered List
- Second item in an unordered list  
  Two trailing spaces indicates the line is part of the list

  is still part of the list despite a blank line in between

### Links

[I am a normal link](http://www.google.com)

    [text](url)

[References look like this][https://github.com/adam-p/markdown-here/wiki/markdown-cheatsheet]

    [text][reference]

### Images - Broken in vscode

![I'd sure like to bomb some dodongos](https://gamecrawl.com/wp-content/uploads/2018/04/the-legend-of-zelda-ocarina-of-t.jpg "Alt-text")
<br/?>

    ![text](image url)

![Reference (variable) style][refname]

    ![Reference (variable) style][refname]

[refname]: https://gamecrawl.com/wp-content/uploads/2018/04/the-legend-of-zelda-ocarina-of-t.jpg

    [refname]: https://gamecrawl.com/wp-content/uploads/2018/04/the-legend-of-zelda-ocarina-of-t.jpg

### Footnotes

[^label]

    [^label]

[label]: "I am the very model of a modern major general"

    [label]: "I am the very model of a modern major general"

#### Inline footnotes

How do you feel about your career as a military leader? ^[I am the very model of a modern major general]

### Tables

| Columns   | Column 2 |  Column 3 |
| :-------- | :------: | --------: |
| Left      |  Center  |     Right |
| _italics_ | **Bold** | `escaped` |

### Quotes

> This is a quoted line.

    > This is a quoted line.

> > Deeper quote

    >> Deeper quote

I am a little disappointed.

1. Many of these features are behaving differently in VScode and wikijs
1. https://docs-legacy.requarks.io/wiki/user-guide/markdown-syntax
   - wikijs doesnt support Tables
   -
1. https://github.com/adam-p/markdown-here/wiki/markdown-cheatsheet
   - Vscode isnt showing images
     - Are markdowns just as different as I recall from the last time I tried to learn it?
     - There is a slight standardization, but I wouldnt call this a standard.

### Horizontal line:

---

    ----

### Foldable Text (It is just an html(`<details> tag`))

<details>
<summary>Would you like to know more?</summary>
<p>paragraph?</p>
</details>

    <details>
    <summary>Would you like to know more?</summary>
    <p>paragraph?</p>
    </details>
