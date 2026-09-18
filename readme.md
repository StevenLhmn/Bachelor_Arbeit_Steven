### Setup
Install TeX Live full scheme

#### Install in VSC:
install LaTeX Extension
install LaTeX Workshop Extension
install LTeX+ Extension

#### Set settings: 
  "latex-workshop.latex.autoBuild.run": "onFileChange",
  "latex-workshop.latex.outDir": "%DIR%",
  "latex-workshop.view.pdf.viewer": "tab",
  "latex-workshop.latex.tools": [
    {
      "name": "latexmk",
      "command": "latexmk",
      "args": [
        "-synctex=1",
        "-interaction=nonstopmode",
        "-file-line-error",
        "-pdf",
        "-outdir=%DIR%",
        "-auxdir=%DIR%/.latex",
        "%DOC%"
      ]
    }
  ],

  "latex-workshop.latex.recipes": [
    {
      "name": "latexmk",
      "tools": [
        "latexmk"
      ]
    }
  ],

  "files.watcherExclude": {
    "**/.latex/**": true
  },

  "search.exclude": {
    "**/.latex/**": true
  },
  "ltex.language": "auto",
