## Welcome to my page

### First, we need to tell Markdown where the two column layout begins.
Anything before this element will be rendered normally.

```
<div class="begin-examples"></div>
```

And we should also tell it where the two column layout ends.

```
<div class="end-examples"></div>
```

### `h2` will be an example section header.

```
## Section title
```

And any text directly after the section title will not be split into two columns.

```
## Section title
This text, along with the title, remains in a single column
```

### Each point in a section starts with an `h3`.

```
### Main you want to make point here
```

### Normal text elements (`p`) are used for more detailed explanations. 
You can put them after the main point.

``` 
### Main point
Some explanatory text.
```

### Code is interleaved with explanatory text.

The main point or explanation for a piece of code should come directly before it.

    ### Main point about code block 1

    ```
    code block 1
    ```

    More text explaining code block 2

    ```
    code block 2
    ```

## Styling
We can use CSS to style the Markdown output to create a two column layout when readers view our page on a larger screen.

## Scientific output

## Resources



You can use the [editor on GitHub](https://github.com/afinnemann/afinnemanngithub.io/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Scientific output

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/afinnemann/afinnemanngithub.io/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Resources

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
