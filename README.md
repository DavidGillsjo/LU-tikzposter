# LU-tikzposter
LaTeX Tikzposter Template for Lund University, Sweden. See [here](example.pdf) for example. The color is off in the preview, so download to see it properly.
This LaTeX template follows the [LU graphical manual](https://www.medarbetarwebben.lu.se/sites/medarbetarwebben.lu.se/files/grafiskmanual-2.0-2018.pdf).
The fonts need to be downloaded separately due to licensing.

## Tikzposter version
The package on CTAN is older and than the master branch source code,
so the included `tikzposter.cls` is built from source https://bitbucket.org/surmann/tikzposter/src.

## Changes
All changes to the theme should go into `lutheme.sty` to make it easy to incorporate updates from tikzposter's master branch.
Here you can change between the different LU-colors and layout styles from the Tikzposter package. See their [styleguide](https://bitbucket.org/surmann/tikzposter/downloads/styleguide.pdf) for details on themes.

## Usage
To use, download the LU specific fonts from https://lu-mediaportal.qbank.se
and unzip to the directory named `fonts`.
Then build `luposter.tex` using `xelatex` with your favourite environment.
