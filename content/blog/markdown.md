+++
title = "Markdown example"
description = "This page demonstrates how Markdown looks in the Hook theme for Zola"
date = 2021-07-30
taxonomies.tags = [
    "markdown",
    "syntax",
]
taxonomies.categories = [
    "intro"
]
+++

This post is a markdown example.

Here is [a link](http://example.com).

Some *italic text* and **bold text** and ~~strikethrough text~~ and `inline code`. [^1]

```rust
// Here is a code block

fn main() {
    println!("Hello world!");
}
```

Unordered list: [^2]
- An unordered,
- bulleted list
- of items

Ordered list:
1. An ordered,
2. numbered list
3. of items

> A quote.
>
> It contains multiple paragraphs.

# Heading 1

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6

![An example image](https://plchldr.co/i/480x360?bg=EB6361)

![A large image](https://plchldr.co/i/1280x720?bg=3D8EB9)

| Hello world! | This is a table. | Tables are also supported. |
|--------------|------------------|----------------------------|
| They even    | have alternating | row colors!                |
| Let me add   | another row so   | it's easier to see.        |

[^1]: A footnote. Footnotes can be used for things that could have explanation or extra context, but
for which the explanation is not relevant or otherwise desirable to have inline.

[^2]: Another footnote.
