# Caerunox fonts

Webfont files and a shared stylesheet for the Caerunox Carrd sites.

- Repository: https://github.com/caerunox/caerunox-fonts
- GitHub Pages specimen: https://caerunox.github.io/caerunox-fonts/
- Stylesheet: https://caerunox.github.io/caerunox-fonts/fonts.css

GitHub Pages configuration: `main` branch, repository root. Open `index.html` to see specimens and a loading check for all three font faces.

## Usage

Add the stylesheet to a Carrd **Code → Hidden → Head** embed:

```html
<link rel="stylesheet" href="https://caerunox.github.io/caerunox-fonts/fonts.css">
```

Use `font-family: 'Caerunox Giove', serif` for headings and `font-family: 'IM Fell English', serif` for body text. Both use weight `400`; the body family includes normal and italic faces. `carrd-fonts.html` contains the stylesheet link and selectors prepared for the existing Carrd draft.

## Files and provenance

| Hosted file | Source supplied by the site owner | CSS family/style |
| --- | --- | --- |
| `fonts/Giove-Regular.woff` | Giove by Typefactory, converted from the owner's Giove font | `Caerunox Giove`, normal |
| `fonts/IMFellEnglish-Regular.ttf` | Original `IMFeENrm28P.ttf` by Igino Marini | `IM Fell English`, normal |
| `fonts/IMFellEnglish-Italic.ttf` | Original `IMFeENit28P.ttf` by Igino Marini | `IM Fell English`, italic |

The IM Fell English TTF contents are preserved byte for byte. Only their filesystem names differ from the supplied originals; their embedded font names and notices are unchanged.

## Font licenses

**Giove is proprietary.** The owner supplied the font and confirmed a webfont license for this hosting. Giove remains subject to its rights holder's license; publication here does not place it under the OFL or grant a general license to reuse it. Its embedded metadata identifies Typefactory: http://typefactory.co/.

**IM Fell English is licensed under the SIL Open Font License 1.1.** The original files identify © 2007 Igino Marini, with Reserved Font Names **IM FELL English Roman** and **IM FELL English Italic**. The exact embedded notices and the complete OFL are in [licenses/IM-Fell-English-OFL.txt](licenses/IM-Fell-English-OFL.txt). These notices were read from the supplied fonts, rather than substituted from a different distribution.

There is no blanket license covering all fonts in this repository.
