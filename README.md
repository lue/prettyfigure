# prettyfigure
Styles for matplotlib figures. Suitable for single-column astrophysical journals (ApJ, for example).

Uses Latex by default.

## Installation
```
pip install prettyfigure
```

If you use Ubuntu and have problems with tex in matplotlib figures, try this:
```
rm ~/.cache/matplotlib/tex.cache/*.dvi
rm ~/.cache/matplotlib/tex.cache/*.pdf
sudo apt-get install dvipng texlive-latex-extra texlive-fonts-recommended
```


## Usage
```
from prettyfigure.style import *
define_figure_style()

import matplotlib.pyplot as plt
plt.plot([1,2,3])
plt.show()
```
