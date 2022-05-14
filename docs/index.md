## Welcome to GitHub Pages

### Quick Links

* [Getting Started](getting_started.md)
* [Installing Metabuild](install_metabuild.md)

### Goals

1.  Written in portable Python 3.8+ code.

2.  Python based syntax for the MetaBuild files. The builder commands are as close as possible to [Buck](http://buck.build/) from Facebook.

3.  Compile all of the C++ code from source and allow sharing external C++ dependencies without duplication.

4.  Unlike [Buck](http://buck.build/), `MetaBuild` doesn't actually drive the compilation of the C++ code:
    - Generates native Xcode and Visual Studio projects.
    - Generates CMake files for Android and Linux.

5.  Supported external dependencies:
    - download via HTTP/S
    - download from Artifactory
    - download code straight out of GIT

6.  `MetaBuild` is fast:
    - cache downloads from remote
    - cache extracted dependencies
    - allow shallow git clones of external repos with lots of history
    - allow local linking of external dependencies for local development

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/BadBob2021/ZX/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
