# latex-thesis-template
My template for my master thesis.

# Build
This should probably work:
```
xelatex -synctex=1 -interaction=nonstopmode -output-directory=build %.tex
makeglossaries -d build %
xelatex -synctex=1 -interaction=nonstopmode -output-directory=build %.tex
biber --output_directory build %
xelatex -synctex=1 -interaction=nonstopmode -output-directory=build %.tex
xelatex -synctex=1 -interaction=nonstopmode -output-directory=build %.tex
```

# Fonts
Adobe Open Source Font Family:
- Source Serif Pro
- Source Code Pro
- Source Sans Pro

# License
Feel free to use my template, but please put some attribution somewhere in your thesis. 

Creative Commons Attribution 4.0
https://creativecommons.org/licenses/by/4.0/legalcode
