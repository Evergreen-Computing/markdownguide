This is a guide to making compact and sleek documents in Markdown. Markdown was created by **John Gruber** and **Aaron Swartz**.

![Markdown](https://softwareicons.kps10.repl.co/icons/program/si_markdown.png)

Markdown is very different from other **word processors**. Word processors usually have *GUI* to modify text and lock up documents in a proprietary file format. Markdown, however, is universal and can be **rendered on *any* device**. It needs no GUI; all it needs is a Markdown editor, which can be found in a lot of places. There are many online ones available, like [Replit](https://replit.com) and [Github](https://github.com). Many offline Markdown editing applications are also available.

Markdown is designed so that even without a renderer, it is readable. That's why it is such a good markup language to know if you are into writing.

Markdown is also used widely in web development. Markdown was used to create the very page you are on right now. Many libraries for languages like **JavaScript** can help Markdown be displayed on a page instead of **HTML**, or with a service like [Github Pages](https://pages.github.com), which this site is hosted on.

Let's get started. Create a file called **`README.md`** and upload it to a Markdown editor.

Now, let's start coding. To create large headlines, you use the **#** tag.

```markdown
# Headline 1
## Headline 2
### Headline 3
#### Headline 4
##### Headline 5
###### Headline 6
```
There are **6** different sizes of headline. The headline size depends on the amount of #s you put before the title. In this case, Headline 1 would be the biggest, and Headline 6 the smallest.

You can type plain text to generate plain text.

```markdown
Here's Some Text
```
There are many things you can use to **modify** text in Markdown. For example, if you wanted to make something **bold**, then use double-asteriks:

```markdown
This is **bold**
```
And likewise, to make something *italic*, use single-asteriks:
```markdown
This is *italic*
```
There is no harm in combining both to make something both ***bold and italic***.

To add a snippet of a `command` or `function` in your Markdown file, use the backtick.
```markdown
`echo Hello World` is the command in Bash used to print a string to screen.
```

[Links](https://evergreen-computing.github.io/markdownguide/) can be added by using a specific notation - in this, you list the link following it's alias.
```markdown
[The Comprehensive Markdown Guide](https://evergreen-computing.github.io/markdownguide/)
```
> To create a **block quote**, use the ">" symbol:
```markdown
> "This is a quote" - *Evergreen-Computing*, 2022
```  
  
 To create an **unordered bullet list**, use the hyphen:
 
 - One
 - Two
 - Three

```markdown
- One
- Two
- Three
```

For an ordered list, use numbers:

1. One
2. Two
3. Three

Adding an **image** has similar notation to adding a link.
![Evergreen Computing](evergreencomputing.png)
```markdown
![Evergreen Computing](evergreencomputing.png)
```
To create a **horizontal rule**, just type 3 hyphens.
```markdown
---
```
---
