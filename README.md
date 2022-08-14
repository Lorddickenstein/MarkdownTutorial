<a name="readme-top"></a>

# Learning about Markdown

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About the project</a>
    </li>
    <li>
      <a href="#headings">Headings</a>
    </li>
    <li>
      <a href="#line-breaks">Line Breaks</a>
    </li>
    <li>
        <a href="#creating-a-list">Creating a List</a>
      <ul>
        <li><a href="#unordered-list">Unordered List</a></li>
        <li>
            <a href="#ordered-list">Ordered List</a>
            <ul>
                <li><a href="#uppercase-letters">Uppercase Letters</a></li>
                <li><a href="#lowercase-letters">Lower ase Letters</a></li>
                <li><a href="#roman-numerals">Roman Numerals</a></li>
            </ul>
        </li>
      </ul>
    </li>
    <li><a href="#adding-in-line-url">Adding In-Line URL</a></li>
    <li><a href="#adding-in-line-code">Adding In-Line Code</a></li>
    <li><a href="#images">Images</a></li>
    <li><a href="#blockquotes">Blockquotes</a></li>
    <li><a href="#horizontal-rule">Horizontal Rule</a></li>
    <li><a href="#text-formats">Text Formats</a></li>
    <li>
        <a href="#github-markdown">Github Markdown</a>
        <ul>
            <li><a href="#adding-block-code">Adding Block Code</a></li>
            <li><a href="#tables">Tables</a></li>
            <li><a href="#tasks-list">Tasks List</a></li>
        </ul>
    </li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>

## About the project
This is a result of a crash course on how to create a basic markdown file. This follows two short youtube tutorials and an excerpt of a popular readme template.

## Headings
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6
___

## Line Breaks
Create line breaks

by leaving an extra space

in the file.

## Creating a List
### Unordered List
- first item (dash)
* second item (asterisk)
  - indented (nested item)
    - indented again (nested nested item)

### Ordered List
1. numbered
2. list
   1. indented (nested numbered item)
      1. numberlist (nested numbered item)

Markdown does not support letter list so use css. Special thanks to <a href="https://stackoverflow.com/questions/13366820/how-do-you-make-lettered-lists-using-markdown">fuhrmanator</a> for this code.

<style type="text/css">
    .upper-alpha { list-style-type: upper-alpha; }
    .lower-alpha { list-style-type: lower-alpha; }
    .lower-roman { list-style-type: lower-roman; }
</style>

#### Uppercase Letters
<ol class='upper-alpha'>
    <li>Item 1</li>
    <li>Item 2</li>
    <li>Item 3</li>
</ol>

#### Lowercase Letters
<ol class='lower-alpha'>
    <li>Item 1</li>
    <li>Item 2</li>
    <li>Item 3</li>
</ol>

#### Roman Numerals
<ol class='lower-roman'>
    <li>Item 1</li>
    <li>Item 2</li>
    <li>Item 3</li>
</ol>

## Adding In-Line URL
On top of using the a-tag from the html we can use this method. Put the description in a bracket and add a opening and closing parenthesis. Inside the parenthesis is the url that you would like the viewer to go to.

Special thanks to Steve Griffit for teaching about markdown in this [youtube](https://www.youtube.com/watch?v=eJojC3lSkwg&ab_channel=SteveGriffith-Prof3ssorSt3v3) video.

Another Special thanks to Traversy Media for adding more information about markdown file in this [youtube](https://www.youtube.com/watch?v=HUBNt18RFbo&ab_channel=TraversyMedia "Markdown Crash Course") video. (Hover over the link to see title)

## Adding In-Line Code
Put the code inside the *grave accent* (\`) to add in-line code like so `let x = "test"`

## Images
![alt text](https://picsum.photos/200/200)

Some paragraph with text

## Blockquotes
> blockquote text here

> blockquote text there


<!-- Horizontal Rule -->
## Horizontal Rule
Use horizontal rule to separate sections or paragraphs from one another.

- Triple Hyphen

---

- Triple Underscore
___

This is helpful in organizing the content of your project and make it appear very clean and understandable.

## Text Formats
<!-- Strong -->
- This is a **bold** text. (double asterisks)

- This is also a __bold__ text. (double underscores)

<!-- Italics -->
- This is an *italic* text. (single asterisk)

- This is also an _italic_ text. (single asterisk)

<!-- Strikethrough -->
- This is ~~strikethrough~~ text. (double tilde)

# Github Markdown
Github-specific markdowns

## Adding Block Code
Put multiline code inside three *grave accents* (\`\`\`). Declare the programming language after the three *grave accents*.

```java
public class Test {
    public static void main (String[] args) {
        System.out.println("Hello World!");
    }
}
```

```python
import string
import random


def id_generator(size=8, chars=string.ascii_letters + string.digits):
    return ''.join(random.choice(chars) for _ in range(size))


print(id_generator())
```

## Tables
Tables are not officially supported by markdown, but github support this. Observe that the colon specifies the text alignment.

### Table 1
| heading | header | head |
| :--- | :---: | ---: |
| content | more content | text|

### Table 2
| Tables   |      Are      |  Cool |
|----------|:-------------:|------:|
| col 1 is |  left-aligned | $1600 |
| col 2 is |    centered   |   $12 |
| col 3 is | right-aligned |    $1 |

## Tasks List
- [x] Task 1 (Marked - Completed)
- [x] Task 2 (Marked - Completed)
- [ ] Task 3 (Unmarked - Pending)

# Acknowledgments
Special thanks to these people:
- [othneildrew](https://github.com/othneildrew)
- [Traversy Media](https://www.youtube.com/watch?v=HUBNt18RFbo&ab_channel=TraversyMedia)
- [Steve Griffith](https://www.youtube.com/watch?v=eJojC3lSkwg&t=608s&ab_channel=SteveGriffith-Prof3ssorSt3v3)
- [haringpula](https://github.com/haringpula)

<p align="center">(<a href="#readme-top">back to top</a>)</p>