# RCS LaTeX Beamer template
This file provides a beamer-theme for the 
Institute for Real-Time Computer System (RCS), 
TU München, Germany, which is compliant to
current TUM Corporate Identity.

This LaTeX beamer template is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.

(c) 2012-2018 Martin Becker <becker@rcs.ei.tum.de>

## PREREQUISITES:
Optional (if not done, please use 'defaultfont' option):
 Install the TUM LaTeX template for letters, because that delivers the TUM New Helvetica font that you need for that.
 Download at http://portal.mytum.de/corporatedesign/download/LaTeX_Vorlagen/index_html
 Refer to http://people.debian.org/~preining/TeX/TeX-on-Debian/ch4.html#s-sec-user-specific-installation for more information on a non-system-wide setup...

## INSTALLATION:
 Copy these files somewhere in your local texmf path, e.g. to ~/texmf/tex/latex/tum/beamer. Then run texhash in the
 root directory, e.g.:

 cd ~/texmf
 texhash .

## USAGE
See example.tex

### Modes
The template supports two beamer modes (provided by the options with the same names):
 * '''beamer''': colored theme including navigation elements for on-screen presentation.
 * '''handout/article/trans''': Logo and separation lines are black, no navigation elements.
Further, there are various options:
 * `nonci`: better use of space, but not CI compliant 
 * `headfootlines`: separator lines for header and footer
 * `conference`: logos only on title page
 * `rcslogo`: replace TUM logo with RCS logo
 * `titleimage`: the first slide with the title has a blue background with waving TUM flags
 * `color=blue`: not fully supported...inverse color scheme
 * `tumfont`: do use TUM font, instead of LaTeX beamer's standard one

Suggested: nonci
