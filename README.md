# LaTeX Beamer: Minima Slides

This projects provides modern LaTeX beamer slides for professional and private use. 
The slides are designed to be easily adaptable and extensible. 
For example, you can:
- Change colors in the section 'COLOR THE TEMPLATE' in `assets/minima.sty`
- Add a logo to the right corner of the frames (edit `\defbeamertemplate*{frametitle}{minima}` in `assets/minima.sty`, see corresponding comment)
- Change the fonts (edit `\setsansfont` and `\newfontfamily\TitleFont` in `main.tex`; see below)
- Use custom backgrounds (see the corresponding slide in the template)

## Quick Start

1. Copy the folder `minima-slides`
2. Edit `main.tex`
3. Compile with `lualatex`


## Fonts

- The template uses a combination of [Roboto](https://fonts.google.com/specimen/Roboto) and [Roboto Serif](https://fonts.google.com/specimen/Roboto+Serif)

- To reproduce the example slides
	1. Download both fonts
	2. Either install them in the 'Font Book' (on macOS) or place them in the `assets` folder
	3. Depending on your choice in (2.), set `Path=assets/,` in `\setsansfont{Roboto}` and in `\newfontfamily\TitleFont{Roboto Serif}` in `main.tex`

- When using custom fonts, you need to compile the slides with `lualatex`


---

This is the second version of this template (see [releases](https://github.com/jzenn/beamer-minima-slides/releases) for the first version).
The original design was inspired by slides from [Philipp Hennig](https://uni-tuebingen.de/en/fakultaeten/mathematisch-naturwissenschaftliche-fakultaet/fachbereiche/informatik/lehrstuehle/methoden-des-maschinellen-lernens/personen/philipp-hennig/) but has evolved substantially since then.
