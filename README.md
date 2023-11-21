<!-- THIS IS A COMMENT, WON'T BE SHOWN -->

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://user-images.githubusercontent.com/25423296/163456776-7f95b81a-f1ed-45f7-b7ab-8fa810d529fa.png">
  <source media="(prefers-color-scheme: light)" srcset="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png">
  <img alt="Shows an illustrated sun in light mode and a moon with stars in dark mode." src="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png">
</picture>

## About me

Hi, I'm Mona. You might recognize me as GitHub's mascot.

<details open>
<summary>My top THINGS-TO-RANK</summary>

| Rank | Languages  |
|-----:|------------|
|     1| C#         |
|     2| SQL        |
|     3| Javascript |

</details>


--- <!-- Horizontal line -->
<!-- The next goes a quote -->
> If we pull together and commit ourselves, then we can push through anything.
> 
— Mona the Octocat

# First-level heading
## Second-level heading
... Can be up to 6th level
###### Sixth-level heading

When we have 2 or more headings, GitHub automatically generates table of contents

**This is bold text**

* *This is italic text* *
* 
  ~~This is strikethrough text~~
  
  **This is bold and _nested italic_**
  
  ***This is all bold and italic***
  
  This is a <sub>subscript</sub> text
  
  This is a <sup>superscript</sup> text

  Text that is not a quote
  
> Text that is a quote

We can use backticks to quote code without formatting (for inline code quotes)

Use `git status` to list all new or modified files that haven't yet been committed.

To format code or text into a quote block, use triple backticks

Some basic Git commands are:
```
git status
git add
git commit
```
We can also use backticks to visualize colors like `#ffffff` for white or `#000000` for black
Supported formats are: 
hex (#RRGGBB, for example `#0969DA`)
rgb (rgb(R,G,B), for example `rgb(9, 105, 218)`)
hsl (hsl(H,S,L), for example `hsl(212, 92%, 45%)`)
(this only works in issues, pull requests and discussions, but not in readme)

This is a [link to the GitHub main page](https://github.com/)

This is a relative link to the [contributing.md file in the docs folder](docs/CONTRIBUTING.md) Github correctly handles branches. Preferred as it is more reliable when cloning a repository.
/ means repository root, also supports ./ and ../ syntax

To show image with an alternative text:
![Here be alternative text](https://myoctocat.com/assets/images/base-octocat.svg)

We can define which image to show depending on the browser color scheme (theme):
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://user-images.githubusercontent.com/25423296/163456776-7f95b81a-f1ed-45f7-b7ab-8fa810d529fa.png">
  <source media="(prefers-color-scheme: light)" srcset="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png">
  <img alt="Shows an illustrated sun in light mode and a moon with stars in dark mode." src="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png">
</picture>

To make an unordered list, precede each item with -, + or *
- George Washington
* John Adams
+ Thomas Jefferson

To make an ordered list, precede each item with any number:
1. James Madison
1. James Monroe
1. John Quincy Adams

To create nested list, use indentation so that the inner list marker lays directly below the first letter of the outer level
1. First list item
   - First nested list item
     - Second nested list item
     - Second nested list item 2

Here be a task list. Here we can refer other GitHub issues. To mark a task as closed, put x into square brackets. If a task description starts with ( - espace it like \(.
- [x] #739
- [ ] https://github.com/octo-org/octo-repo/issues/740
- [ ] Add delight to the experience when all tasks are complete :tada:

Can reference teams and people using @ prefix, and issues or pull request with # prefix.

Can use emojis liek this:
@octocat :+1: This PR looks great - it's ready to merge! :shipit:

To create a new paragraph, leave an empty line.

Can use footnotes using the following syntax:
Here is a simple footnote[^1].

A footnote can also have multiple lines[^2].

[^1]: My reference.
[^2]: To add line breaks within a footnote, prefix new lines with 2 spaces.
  This is a second line.

We can use alerts to emphasize important information

> [!NOTE]
> Highlights information that users should take into account, even when skimming.

> [!TIP]
> Optional information to help a user be more successful.

> [!IMPORTANT]
> Crucial information necessary for users to succeed.

> [!WARNING]
> Critical content demanding immediate user attention due to potential risks.

> [!CAUTION]
> Negative potential consequences of an action.

Use backslash to escape Markdown formatting
Let's rename \*our-new-project\* to \*our-old-project\*.

Use hyphen (-) and pipe (|) to create tables. Leave blank line before the table for correct rendering.

| First Header  | Second Header |
| ------------- | ------------- |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |

No need for perfect alignment in the code, just leave at least 3 hyphens in each column in the header row

| Command | Description |
| --- | --- |
| git status | List all new or modified files |
| git diff | Show file differences that haven't been staged |

In the table, you can use formatting like links, inline code blocks and text styling

| Command | Description |
| --- | --- |
| `git status` | List all *new or modified* files |
| `git diff` | Show file differences that **haven't been** staged |

Use colon to align content within the column

| Left-aligned | Center-aligned | Right-aligned |
| :---         |     :---:      |          ---: |
| git status   | git status     | git status    |
| git diff     | git diff       | git diff      |

To use pipe within a column content, use escaping

| Name     | Character |
| ---      | ---       |
| Backtick | `         |
| Pipe     | \|        |


We can use collapsed sections using 'details' tag. Use 'open' attribute to have the section expanded at start.

<details>

<summary>Tips for collapsed sections</summary>

### You can add a header

You can add text within a collapsed section. 

You can add an image or a code block, too.

```ruby
   puts "Hello World"
```

</details>
