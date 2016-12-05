# Branch Structure

### DEV
This is branch where the version for distribution is going to be kept. Please target all your commits here.

### MASTER
This is the branch that will be compiled into the shipping version. DO NOT MAKE MODIFICATIONS TO THIS BRANCH unless you're one of the admins on the project.

# Guidelines

### Templates + Guides 
We're following the MS Docs guidelines with a few adjustments to meet our needs. Thanks to the MS Docs team for making such a great guideline.
- **voice-tone.md**: This is the general tone we want to achieve in the docs.
- **template.md**: General guidelines for markdown formatting for the docs.
- **template-device.md**: The structure template for Devices and Macros.
- **template-todo.md**: Use this code for either the entire file (if completely unfinished), or at the top if partially unfinished.

### Folder Structure + Naming Convention

The `docs` folder is the root of all documentation, with `TOC.json` acting as the TOC that will be consumed by both the software and online documentation.

Slug or URL moniker for each topic will be in this format:
> Folder Name with -- separator followed by the topic name, with dashes replacing all whitespace and/or special characters.
> `folder-name--topic-name`

Avoid using any numerals or special characters and use only A-Z for file names. Actual topic titles can contain limited ASCII special characters in the TOC. 
