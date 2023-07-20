# About Website Template

Each system will have a `system-about` website built with [Markdown](https://daringfireball.net/projects/markdown/)/. This website will be used to track contributions, phases, and documentation. This repo is a template for the `system-about` websites. These repos are named `system-about`.

This template is built using [Markdown](https://daringfireball.net/projects/markdown/). Creating and editing these websites will only require a basic understanding of [Markdown](https://daringfireball.net/projects/markdown/)

## Website Structure

About websites will have the following structure: 

```
project
│   README.md
│   index.markdown
│   phase-1.markdown
│   phase-2.markdown
│
└── phase-1
│   │   phase-1-pitch.markdown
│   │   phase-1-pitch.pdf
│   │   phase-1-requirements.markdown
│   │   phase-1-requirements.pdf
│
└── images
```

## Contributors

At the bottom of a `phase-<#>.markdown` document the contributors are placed in a table including avatar, name, and GitHub link. The avatar images are copied to the `images` folder in the repo and resized to 30 x 30 pixels. Image are named `<FIRST>-<LAST>.<ext>`.

## Guidlines

The following rules should be followed with each `system-about` website:

- Home page includes a brief system descrition followed by a blog list
- Each phase will have a page named `phase-<#>.markdown` in the `root` folder
- Each phase will have a folder with the original PDF pitch, PDF requirements document, and matching markdown files
- Phase files are named `<SYSTEM>-phase-<#>-pitch.markdown`, `<SYSTEM>-phase-<#>-pitch.pdf`, `<SYSTEM>-phase-<#>-requirements.markdown`, and `<SYSTEM>-phase-<#>-requirements.pdf`
- Images for the `inex.markdown`, `phase-<#>.markdown`, and phase documents are placed in the `root/images` folder
- Images related to a phase are named `phase-<#>-<TITLE>.<EXT>`
- All Markdown follows [Tidy](https://tidy.codeadam.ca/) guidelines

> This repo is available to view at  
> https://brickmmo.github.io/template-about-markdown/

***

## Repository Resources

* [Markdown](https://daringfireball.net/projects/markdown/)

<a href="https://brickmmo.com">
<img src="https://brickmmo.com/images/brickmmo-logo-horizontal.jpg" width="300">
</a>
