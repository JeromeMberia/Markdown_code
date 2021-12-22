# Markdown

## Heading

```text
## 1
```

### Output for heading

> ## 1

## Bold

```text
**bold text**
```

### Output for bold

> **bold text**.

## Italic

```text
*bold text*
```

### Output for italic

> *bold text*

## Blockquote

```text
> Dorothy followed her through many of the beautiful rooms in her castle.
```

### Output for blockquote

> Dorothy followed her through many of the beautiful rooms in her castle.

## Ordered List

```text
1. First item
2. Second item
3. Third item
4. Fourth item
```

### Output for ordered list

> 1. First item
> 2. Second item
> 3. Third item
> 4. Fourth item

## Unordered List

```text
* First item
* Second item
* Third item
* Fourth item
```

### Output for unordered list

> * First item
> * Second item
> * Third item
> * Fourth item

## Code

```text
    ``` 
    ```
```

### Output for code

```text

```

## Horizontal Rule

```text
***
```

### Output for horizontal rule

***

## Link

### Without a title for the link

```text
My favorite search engine is [Duck Duck Go](https://duckduckgo.com).
```

#### Output for link without a title

> My favorite search engine is [Duck Duck Go](https://duckduckgo.com).

### With a title for the link

```text
My favorite search engine is [Duck Duck Go](https://duckduckgo.com "The best search engine for privacy").
```

#### Output for link with a title

> My favorite search engine is [Duck Duck Go](https://duckduckgo.com "The best search engine for privacy").

## Image

```text
![tokyo street](/images/image_1.jpg "tokyo street")
```

### Output for images

![tokyo street](/images/image_1.jpg "tokyo street")

## Table

```text
| Syntax    | Description | Test Text   |
| :---      | :----:      | ---:        |
| Header    | Title       | Here's this |
| Paragraph | Text        | And more    |
```

### Output for table

|Syntax|Description|Test Text|
|:---|:----:|---:|
|Header|Title|Here's this|
|Paragraph|Text|And more|

## Fenced Code Block

```text
    (```json)
    {
    "firstName": "John",
    "lastName": "Smith",
    "age": 25
    }
    (```)
```

### Output for fenced code block

```json
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

## Footnote

```text
    Here's a simple footnote,[^1] and here's a longer one.[^bignote]

    [^1]: This is the first footnote.

    [^bignote]: Here's one with multiple paragraphs and code.

        Indent paragraphs to include them in the footnote.

        `{ my code }`

        Add as many paragraphs as you like.
```

## Output

Here's a simple footnote,[^1] and here's a longer one.[^bignote]

[^1]: This is the first footnote.

[^bignote]: Here's one with multiple paragraphs and code.

    Indent paragraphs to include them in the footnote.

    `{ my code }`

    Add as many paragraphs as you like.

## Heading ID

```text
### My Great Heading {#custom-id}
```

### Output for heading ID

#### My Great Heading {#custom-id}

## Definition List

```text

```

## Output for definition list

>

## Strikethrough

```text
~~The world is flat.~~ We now know that the world is round.
```

## Output for strikethrough

> ~~The world is flat.~~ We now know that the world is round.

## Task List

```text
- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media
```

### Output for task list

* [x] Write the press release
* [ ] Update the website
* [ ] Contact the media

## Emoji

```text
Gone camping! :tent: Be back soon.

That is so funny! :joy:
```

### Output for emoji

Gone camping! :tent: Be back soon.

That is so funny! :blush:

## Highlight

```markdown
I need to highlight these ==very important words==.
```

### Output for highlight

> I need to highlight these ==very important words==.

## Subscript

```text
H~2~O
```

### Output for subscript

H~2~O

## Superscript

```text
X^2^
```

### Output for superscript

X^2^
