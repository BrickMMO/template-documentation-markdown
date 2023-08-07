# About Website Template

Each system will have a `system-about` website built with [Markdown](https://daringfireball.net/projects/markdown/). This website will be used to track contributions, versions, and documentation. This repo is a template for the `system-about` websites. These repos are named `system-about`.

This template is built using [Markdown](https://daringfireball.net/projects/markdown/). Creating and editing these websites will only require a basic understanding of [Markdown](https://daringfireball.net/projects/markdown/)

## Website Structure

About websites will have the following structure:

```
project
│   README.md
│   index.markdown
│   v1.markdown
│   v2.markdown
│
└── v1
│   │   system-v1-pitch.markdown
│   │   system-v1-pitch.pdf
│   │   system-v1-requirements.markdown
│   │   system-v1-requirements.pdf
│
└── images
    |   codeadamca.jog
```

## Contributors

At the bottom of a `v<#>.markdown` document the contributors are placed in a table including avatar, name, and GitHub link. The avatar images are copied to the `images` folder in the repo and resized to 40 x 40 pixels. Image are named `<FIRST>-<LAST>.<ext>`.

## Guidlines

The following rules should be followed with each `system-about` website:

- Home page includes a brief system descrition followed by a list of versions
- Each version will have a page named `v<#>.markdown` in the `root` folder
- Each version will have a folder with the original PDF pitch, PDF requirements document, and matching markdown files
- Version files are named `<SYSTEM>-v<#>-pitch.markdown`, `<SYSTEM>-v<#>-pitch.pdf`, `<SYSTEM>-v<#>-requirements.markdown`, and `<SYSTEM>-v<#>-requirements.pdf`
- Images for the `index.markdown`, `v<#>.markdown`, and version documents are placed in the `root/images` folder
- Images related to a version are named `v<#>-<TITLE>.<EXT>`
- Profile images are named `<GITHUB_USERNAME>.png`, images are 80 x 80 pixels and can be png, jpg, or gif, and placed in the `students` or `faculty` folder

> **Note**  
> All Markdown should follow the [_readme](https://readme.codeadam.ca/) guidelines.

> This repo is available to view at  
> https://brickmmo.github.io/template-about-markdown/

---

## Repository Resources

- [Markdown](https://daringfireball.net/projects/markdown/)

<a href="https://brickmmo.com">
<img src="https://brickmmo.com/images/brickmmo-logo-horizontal.jpg" width="300">
</a>
