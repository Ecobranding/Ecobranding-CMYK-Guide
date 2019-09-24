# Ecobranding CMYK Guide

An eco-designed color guide and open-source to use less ink, less paper, less energy.

## What

The Ecobranding CMYK Guide is an open-source color tool that features 167 CMYK four-color process (Cyan, Magenta, Yellow, Yellow, Key (Black)) eco-designed and their corresponding values.
The colours defined in this guide limit the ink consumption used for four-colour printing.

## Why
### In printing, not all colours use the same amount of ink. 
When you print a red (0% Cyan + 100% Magenta + 100% Yellow + 100% Yellow + 0% Key = 200%) you use twice as much ink as if you print black (0% Cyan + 0% Magenta + 0% Yellow + 100% Key = 100%). 

### In printing not all colours use the same type of paper. 
In printing, the maximum ink rate is 300%, for recycled paper it can be 270%. If you print a strong green like Forest Green (100% Cyan + 50% Magenta + 100% Yellow + 50% Key = 300%) you must use a thick paper under penalty of drying and staining problems, conversely if you print with a lighter green like Light Green (40% Cyan + 0% Magenta + 40% Yellow + 7% Key = 87%) you can reduce your paper consumption by using a less thick paper.

### In printing, not all colours use the same amount of energy. 
Inkjet printers go back and forth with a print head that will project the ink onto the paper. All these trips consume energy. We have found (disclaimer: without official studies) that for a color with a high anchoring rate the print head will make more trips than with a color with a low inking rate, the color with a high inking rate will therefore consume more energy.

## How
We have created Ecobranding CMYK Guide, a new color language tool to define only colours that do not exceed an inking rate of 100%. Our first version has 167 "standards" colors, but we can define many more and the Ecobranding CMYK Guide has been designed to evolve. 

Each color has been standardized according to the same process: 

```ECOBRANDING
ECOBRANDING 50-4
```
```ECOBRANDING
ECOBRANDING(name of the colour chart) 50(ink rate) -4(number of the colour in its ink rate range)
```

This allows the user to easily see the ink rate used by each colour he has chosen.


## Available Colors


![available colors](https://github.com/Ecobranding/Ecobranding-CMYK-Guide-/blob/master/EcobrandingCMYKguide.svg)

The Ecobranding CMYK Guide is free and open source and must not be commercialized.
It comes in the form of an Ecobranding.ase color chart file that you can easily install on your computer (e.g. Adobe Illustrator/Presets/Color Swatches) and find it in the color library.

It is also accompanied by a CMYK PDF poster ready to be printed in Certified proof.

## Contribution

Check out the list below.

### Color Value

- `open-color.json`
   - Change and `$ npm run compile-templates`
- `docs/asset/download/open-color_*.*.*.aco`
- `docs/asset/download/open-color_*.*.*.clr`
- Adobe library (admin rights)

### Version Number

- `package.json`
- `docs/asset/download/open-color_*.*.*.aco`
- Adobe library (admin rights)

### Document

- `README.md`
- `docs/documents.html`

### Introduction

- `README.md`
