## Build PDF when run `.tex` file on TeXShop
- Install MacTeX with builtin editor (TexLive) - (3.2GB)
- Open the Terminal

- If `brew` not installed in your machine then
```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

- Install mactex
```
brew install --cask mactex
```

- After conmplete installation 
```bash
open /Applications/TeX
```

- Click on TexShop and write your Latex code
- When TeXShop is active, there is a `Typeset` menu, in which you should mark the `pdftex` option (see also the `Typesetting` panel of TeXShop's Preferences to make this choice permanent).

- Once this is done, TeXShop will typeset your documents with PDFLaTeX whenever you select `LaTeX` in the same Typeset menu. (Shortcut: `command-shift-L`, or simply `command-t` if the default format chosen in the `Typesetting` Preferences panel is indeed LaTeX.)

- Then output `.pdf` will same name as `.tex`
