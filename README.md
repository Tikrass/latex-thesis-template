# latex-thesis-template
My template for my master thesis.

# Build
This should probably work:
```
cd thesis
mkdir build
xelatex -synctex=1 -interaction=nonstopmode -output-directory=build thesis.tex
makeglossaries -d build "thesis"
xelatex -synctex=1 -interaction=nonstopmode -output-directory=build thesis.tex
biber --output_directory build "thesis"
xelatex -synctex=1 -interaction=nonstopmode -output-directory=build thesis.tex
xelatex -synctex=1 -interaction=nonstopmode -output-directory=build thesis.tex
```
# Example
If you are interested, on how to use the packages, you can find the sources of my master thesis in `example.zip`. 

# Fonts
Adobe Open Source Font Family:
- Source Serif Pro
- Source Code Pro
- Source Sans Pro

# License
Feel free to use my template, but please put some attribution somewhere in your thesis. 

Creative Commons Attribution 4.0
https://creativecommons.org/licenses/by/4.0/legalcode
