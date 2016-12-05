> NOTE: NOT THE FINAL COPY. This is a copy of the template used by MS Docs. Expect modifications to this during the week.

# Metadata and Markdown Template

This core-docs template contains examples of Markdown syntax, as well as guidance on setting the metadata. To get the most of it, you must view both the [raw Markdown](https://raw.githubusercontent.com/dotnet/docs/master/styleguide/template.md) and the [rendered view](https://github.com/dotnet/docs/blob/master/styleguide/template.md) (for instance, the raw Markdown shows the metadata block, while the rendered view does not).

## Basic Markdown, GFM, and special characters

All basic and GitHub Flavored Markdown (GFM) is supported. For more information on these, see:

- [Baseline Markdown syntax](https://daringfireball.net/projects/markdown/syntax)
- [GFM documentation](https://guides.github.com/features/mastering-markdown)

Markdown uses special characters such as \*, \`, and \# for formatting. If you wish to include one of these characters in your content, you must do one of two things:

- Put a backslash before the special character to "escape" it (for example, `\*` for a \*)
- Use the [HTML entity code](http://www.ascii.cl/htmlcodes.htm) for the character (for example, `&#42;` for a &#42;).

## File name

File names use the following rules:
* Contain only lowercase letters, and hyphens.
* No spaces, numbers, or punctuation characters. Use the hyphens to separate words umbers in the file name.
* Use action verbs that are specific, such as develop, buy, build, troubleshoot. No -ing words.
* No small words - don't include a, and, the, in, or, etc.
* Must be in Markdown and use the .md file extension.
* Keep file names reasonably short. They are part of the URL for your articles.  


## Headings

Use sentence-style capitalization. Always capitalize:
- The first word of a heading. 
- The word following a colon in a title or heading (for example, "How to: Sort an array"). 

Headings should be done using atx-style, that is, use 1-6 hash characters (#) at the start of the line to indicate a heading, corresponding to HTML headings levels H1 through H6. Examples of first- and second-level headers are used above. 

There **must** be only one first-level heading (H1) in your topic, which will be displayed as the on-page title.

If your heading finishes with a `#` character, you need to add an extra `#` character in the end in order for the title to render correctly. For example, `# Async Programming in F# #`.     

Second-level headings will generate the on-page TOC that appears in the "In this article" section underneath the on-page title.

### Third-level heading
#### Fourth-level heading
##### Fifth level heading
###### Sixth-level heading
 
## Text styling

*Italics*
 Use for files, folders, paths (for long items, split onto their own line) - new terms - URLs (unless rendered as links, which is the default).

**Bold**
Use for UI elements.

## Links

### Internal Links

To link to a Markdown file in the same repo, use this special format.

Folder Name with -- separator followed by the topic name, with dashes replacing all whitespace and/or special characters.

- Example: `folder-name--topic-name` [Aperture](Devices--Aperture)

### Links to Devices and Macros

You can use the `@device` shorthand to link to devices and macros. GitHub and general Markdown will not recognize it, but our markdown processor will convert it to the appropriate link.

NOTE: **The shorthand must be in lowercase.**

> For example, `@aperture` will be turned into [Aperture](devices--aperture)

### External Links

To link to an external file, use the full URL as the link.

- Example: [GitHub](http://www.github.com)

If a URL appears in a Markdown file, it will be transformed into a clickable link.

- Example: http://www.github.com


## Lists

### Ordered lists

1. This 
1. Is
1. An
1. Ordered
1. List  


#### Ordered list with an embedded list

1. Here
1. comes
1. an
1. embedded
    1. Miss Scarlett
    1. Professor Plum
1. ordered
1. list


### Unordered Lists

- This
- is
- a
- bulleted
- list


##### Unordered list with an embedded list

- This 
- bulleted 
- list
    - Mrs. Peacock
    - Mr. Green
- contains  
- other
    1. Colonel Mustard
    1. Mrs. White
- lists


## Horizontal rule

---

## Code

### Inline code

Use backticks (&#96;) for `inline code`. Use inline code for command-line commands, database table and column names, and language keywords.

## Blockquotes

> The drought had lasted now for ten million years, and the reign of the terrible lizards had long since ended. Here on the Equator, in the continent which would one day be known as Africa, the battle for existence had reached a new climax of ferocity, and the victor was not yet in sight. In this barren and desiccated land, only the small or the swift or the fierce could flourish, or even hope to survive.

## Images

### Static Image or Animated gif

![this is the alt text](../images/Logo_DotNet.png)

### Linked Image

[![alt text for linked image](../images/Logo_DotNet.png)](https://dot.net) 

## Videos

### Channel 9

<iframe src="https://channel9.msdn.com/Shows/On-NET/Shipping-NET-Core-RC2--Tools-Preview-1/player" width="960" height="540" allowFullScreen frameBorder="0"></iframe>

### YouTube

<iframe width="420" height="315" src="https://www.youtube.com/embed/g2a4W6Q7aRw" frameborder="0" allowfullscreen></iframe>

## docs.microsoft extensions

docs.microsoft provides a few additional extensions to GitHub Flavored Markdown. 

### Alerts

It's important to use the following alert styles so they render with the proper style in the documentation site. However, the rendering engine on GitHub doesn't diferentiate them.     

#### Note

> [!NOTE]
> This is a NOTE
> [NOTE!]

#### Warning

> [!WARNING]
> This is a WARNING
> [WARNING!]

#### Tip

> [!TIP]
> This is a TIP
> [TIP!]

#### Important

> [!IMPORTANT]
> This is IMPORTANT
> [IMPORTANT!]

And they'll render like this:
![Alert styles](../images/alerts.png)