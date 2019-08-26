
[![Build Status](https://travis-ci.org/cmarquardt/sagittarius.svg?branch=master)](https://travis-ci.org/cmarquardt/sagittarius)

# Sagittarius

Sagittarius is a modern LaTeX [beamerposter] theme based on Anish Athalye's excellent [Gemini] theme.

<!--
<p align="center">
<a href="https://raw.githubusercontent.com/anishathalye/gemini/assets/poster-gemini.pdf">
<img src="https://raw.githubusercontent.com/anishathalye/gemini/assets/poster-gemini-small.png">
</a>
</p>
-->

# Dependencies

* A TeX installation that includes [LuaTeX] or [XeTeX]
* LaTeX package dependencies including beamerposter (these usually come with
  your TeX installation, but if not, you can get them from [CTAN])
* [Raleway] and [Lato] for the base themes; both available under an Open Font License

# Usage

1. Copy the files in this repository (or clone the repository)

1. In `poster.tex`, set up your paper size, column layout, and scale the
   content as necessary

1. Make a copy of `beamercolorthemegemini.sty`, update the `\usecolortheme`
   line in `poster.tex`, and theme the poster to your liking (optional, but
   highly recommended)

1. Run `make` to build your poster

<!--
# FAQ

See the [FAQ] in the Wiki for answers to frequently asked questions such as how
to add an institution logo to the poster.
-->

# Themes

Sagittarius currently includes the three original Gemini color themes:

* `gemini` (default)
* `mit`
* `labsix`


<!--
## MIT theme

<p align="center">
<a href="https://raw.githubusercontent.com/anishathalye/gemini/assets/poster-mit.pdf">
<img src="https://raw.githubusercontent.com/anishathalye/gemini/assets/poster-mit-small.png">
</a>
</p>

## LabSix theme

<p align="center">
<a href="https://raw.githubusercontent.com/anishathalye/gemini/assets/poster-labsix.pdf">
<img src="https://raw.githubusercontent.com/anishathalye/gemini/assets/poster-labsix-small.png">
</a>
</p>
-->

# Design goals

* **Minimal**: clean and easy to read, so that the emphasis is on the content
* **Batteries included**: works and looks good out of the box
* **Easy theming**: easy to create and use a new color theme

# Contributing

As usual - please raise an issue, and feel free to put in pull requests!

# License

Copyright (c) 2018-2019 Anish Athalye for the orignal Gemini. Released under the MIT License. See
[LICENSE.md][license] for details.

[beamerposter]: https://github.com/deselaers/latex-beamerposter
[Gemini]: https://www.anishathalye.com/2018/07/19/gemini-a-modern-beamerposter-theme/
[LuaTeX]: http://www.luatex.org/
[XeTex]: http://xetex.sourceforge.net/
[CTAN]: https://ctan.org/
[Raleway]: https://www.fontsquirrel.com/fonts/raleway
[Lato]: https://www.fontsquirrel.com/fonts/lato
[license]: LICENSE.md
<!--
[FAQ]: https://github.com/anishathalye/gemini/wiki/FAQ
-->
