# Project Title

Welcome to the **sample README**. This file demonstrates common GitHub Markdown features.

---

## Headings

# Heading level 1  
## Heading level 2  
### Heading level 3  
#### Heading level 4  

---

## Styling Text

You can style text in several ways:

- **Bold text**
- *Italic text*
- ***Bold and italic***
- ~~Strikethrough~~
- `Inline code`

---

## Quoting Text

> This is a blockquote.  
> It’s commonly used for notes, tips, or quoting documentation.
>
> — Someone Important

---

## Supported Color Models

GitHub supports the following color formats in Markdown (often used in issues, PRs, and documentation):

- HEX: `#0969DA`
- RGB: `rgb(9, 105, 218)`
- HSL: `hsl(212, 92%, 45%)`

Example usage:

```css
color: #0969DA;
background-color: rgb(9, 105, 218);
border-color: hsl(212, 92%, 45%);

## Colors

GitHub Markdown supports the following color models:
- HEX
- RGB
- HSL

These are commonly used in documentation, issues, pull requests, and code blocks.

---

### HEX Colors

HEX colors use the format `#RRGGBB`.

Examples:

- Red: `#FF0000`
- Green: `#00FF00`
- Blue: `#0000FF`
- Black: `#000000`
- White: `#FFFFFF`
- GitHub Blue: `#0969DA`

```css
color: #FF5733;
background-color: #0969DA;
border-color: #000000;

# A first-level heading
## A second-level heading
### A third-level heading

Quoting text
Text that is not a quote

> Text that is a quote

Quoting code
Some basic Git commands are:
```
git status
git add
git commit
```
Supported color models
The background color is `#ffffff` for light mode and `#000000` for dark mode.

Links
This site was built using [GitHub Pages](https://pages.github.com/).

Section links
# Example headings

## Sample Section

## This'll be a _Helpful_ Section About the Greek Letter Θ!
A heading containing characters not allowed in fragments, UTF-8 characters, two consecutive spaces between the first and second words, and formatting.

## This heading is not unique in the file

TEXT 1

## This heading is not unique in the file

TEXT 2

# Links to the example headings above

Link to the sample section: [Link Text](#sample-section).

Link to the helpful section: [Link Text](#thisll-be-a-helpful-section-about-the-greek-letter-Θ).

Link to the first non-unique section: [Link Text](#this-heading-is-not-unique-in-the-file).

Link to the second non-unique section: [Link Text](#this-heading-is-not-unique-in-the-file-1).

Relative links
[Contribution guidelines for this project](docs/CONTRIBUTING.md)
[Contribution
guidelines for this project](docs/CONTRIBUTING.md)

Custom anchors
# Section Heading

Some body text of this section.

<a name="my-custom-anchor-point"></a>
Some text I want to provide a direct link to, but which doesn't have its own heading.

(… more content…)

[A link to that custom anchor](#my-custom-anchor-point)

Line breaks

This example
Will span two lines
Include two spaces at the end of the first line.

This example  
Will span two lines
Include a backslash at the end of the first line.

This example\
Will span two lines
Include an HTML single line break tag at the end of the first line.

This example<br/>
Will span two lines
If you leave a blank line between two lines, both .md files and Markdown in issues, pull requests, and discussions will render the two lines separated by the blank line:

This example

Will have a blank line separating both lines

Images
![Screenshot of a comment on a GitHub issue showing an image, added in the Markdown, of an Octocat smiling and raising a tentacle.](https://myoctocat.com/assets/images/base-octocat.svg)

The Picture element

The <picture> HTML element is supported.

Lists
- George Washington
* John Adams
+ Thomas Jefferson

1. James Madison
2. James Monroe
3. John Quincy Adams

Nested Lists
1. First list item
   - First nested list item
     - Second nested list item

Task lists
- [x] #739
- [ ] https://github.com/octo-org/octo-repo/issues/740
- [ ] Add delight to the experience when all tasks are complete :tada:
- [ ] \(Optional) Open a followup issue

Mentioning people and teams
@github/support What do you think about these updates?

Using emojis
@octocat :+1: This PR looks great - it's ready to merge! :shipit:

Footnotes

Here is a simple footnote[^1].

A footnote can also have multiple lines[^2].

[^1]: My reference.
[^2]: To add line breaks within a footnote, add 2 spaces to the end of a line.  
This is a second line.

Alerts
> [!NOTE]
> Useful information that users should know, even when skimming content.

> [!TIP]
> Helpful advice for doing things better or more easily.

Hiding content with comments
You can tell GitHub to hide content from the rendered Markdown by placing the content in an HTML comment.

<!-- This content will not appear in the rendered Markdown -->
Ignoring Markdown formatting
Let's rename \*our-new-project\* to \*our-old-project\*.

> [!IMPORTANT]
> Key information users need to know to achieve their goal.

> [!WARNING]
> Urgent info that needs immediate user attention to avoid problems.

> [!CAUTION]
> Advises about risks or negative outcomes of certain actions.


    

