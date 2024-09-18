# Extend Syntax Markdown

## Table

```md
| Syntax | Description|
|------- |----------- |
| Header | Title      |
| Paragraph | Text    |
```

| Syntax | Description|
|------- |----------- |
| Header | Title      |
| Paragraph | Text    |

:star: [Markdown Tables Generator](https://www.tablesgenerator.com/markdown_tables)

### Alignment

```md
| Syntax | Description | Test Text |
| :--- | :----: | ---: |
| Header | Title | Here's this |
| Paragraph | Text | And more |
```

| Syntax | Description | Test Text |
| :--- | :----: | ---: |
| Header | Title | Here's this |
| Paragraph | Text | And more |

:star: Use a colon (`:`) to the left, right, or on both side of the hyphens within the header row

- `:---` : to align left
- `---:` : to align right
- `:----:` : to align center

### Formatting Text in Tables

- :yum: Can add links, code (in tick mark only), emphasis.
- :imp: Can't add heading, blockquote, list, horizontal rules, images, or HTML tags.

### Escaping Pile Character in Tables

:star: use HTML character code `&#124;` to replace `|`.

## Fenced Code Blocks

```json
{
    "firstName": "John",
    "lastName": "Smith",
    "age": 25
}
```

## Footnotes

> Footnotes allow tou to add and references without cluttering the body of the document

```md
Here's a simple footnote, [^1] and here's a longer one. [^bignote]

[^1]: This is the first footnote

[^bignote]: Here's one with multiple paragraphs and code.  
    Indent paragraphs to include them in the footnote.  
    `{ my code }`  
    Add as many paragraphs as you like.
```

Here's a simple footnote, [^1] and here's a longer one. [^bignote]

<!-- Description -->
[^1]: This is the first footnote

[^bignote]: Here's one with multiple paragraphs and code.  
    Indent paragraphs to include them in the footnote.  
    `{ my code }`  
    Add as many paragraphs as you like.

## Linking to Heading IDs

### InPage

:dart: Table of Content:

```md
1. [Tables](#table)
2. [Fenced Code Block](#fenced-code-blocks)
3. [Footnote](#footnotes)
4. [Heading IDs](#linking-to-heading-ids)
```

1. [Tables](#table)
2. [Fenced Code Block](#fenced-code-blocks)
3. [Footnote](#footnotes)
4. [Heading IDs](#linking-to-heading-ids)


### URL Page

```md
[Heading IDs](https:/www.eff.org/page#heading-ids)
```

[Heading IDs](https:/www.eff.org/page#heading-ids)

### In Another Page

```md
How to use [Basic Syntax Markdown](./Basic%20Syntax%20Markdown.md) .
```

How to use [Basic Syntax Markdown](./Basic%20Syntax%20Markdown.md) .

## Definition Lists

💔 This syntax feature is **not** part of the original Markdown syntax.

```md
Love  
: to like another adult very much and be romantically and sexually attracted to them, or to have strong feelings of liking a friend or person in your family
```

Love  
: to like another adult very much and be romantically and sexually attracted to them, or to have strong feelings of liking a friend or person in your family


## Strikethrough

```md
The word is ~~flat~~ round.
```

The word is ~~flat~~ round.

## Task List

:memo: **Daily :**

- [x] : Wake up at 6 AM.
- [x] : Exercise
- [ ] : HomeWork

## Automatic URL Linking

:star: Markdown processor will automatically turn it into a link even though you haven't used brackets.

```md
<https://google.com.vn>
```

<https://google.com.vn>

### Disabling Automatic URL Linking

:star: Meaning turn into code

```md
`http://www.example.com`
```

`http://www.example.com`
