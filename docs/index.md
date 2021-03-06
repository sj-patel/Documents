# Welcome!

This is a basic example of documentation. It is intended as a showcase of some of the
features that TechDocs provides out of the box.

You can see also:

- [A sub page](sub-page.md)
- [Inline code examples](code/code-sample.md)
- [Plugin & Extension examples](extensions.md) - Diagrams, emojis, visual formatting.

## Basic Markdown

Headings (markdown supports four levels of headings):

```# H1 Heading```: results in:
# H1 Heading

```## H2 Heading```: results in:
## H2 Heading

```### H3 Heading```: results in:
### H3 Heading

```#### H4 Heading```: results in:
#### H4 Heading


## Here is a bulleted list:

- Item one
  - sub item
- Item two
- Item Three

Check out the [Markdown Guide](https://www.markdownguide.org/) to learn more about how to
simply create documentation.

You can also learn more about how to configure and setup this documentation in Backstage,
[read up on the TechDocs Overview](https://backstage.io/docs/features/techdocs/techdocs-overview).

## Image Example 

* Referencing a PNG file. *

![Allegiant Logo](images/Allegiant.png){ width=300 }

* Referencing an SVG file *

![Allegiant Logo](images/Allegiant.svg){ width=300 }


!!! note "Note"
    If you want to have a note call-out. There are many other ways [you can use call-outs.](https://squidfunk.github.io/mkdocs-material/reference/admonitions/#supported-types)

!!! danger "No Mermaid"
    Mermaid is not yet supported. It is possible with a bit more work. Will look into it.

``` mermaid
graph LR
  A[Start] --> B{Error?};
  B -->|Yes| C[Hmm...];
  C --> D[Debug];
  D --> B;
  B ---->|No| E[Yay!];
```

## Table Example

While this documentation isn't comprehensive, in the future it should cover the following
topics outlined in this example table:

| Topic   | Description                                                  |
| ------- | ------------------------------------------------------------ |
| Topic 1 | An introductory topic to help you learn about the component. |
| Topic 2 | A more detailed topic that explains more information.        |
| Topic 3 | A final topic that provides conclusions and lessons learned. |


## Button!

[Subscribe to our newsletter](#){ .md-button }

