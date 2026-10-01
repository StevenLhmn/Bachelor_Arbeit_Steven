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

## Add to dictionary
Petrit
Vuthi
Ähnlichkeitsanalyse
Ähnlichkeitsanalysen
Algorithmenauswahl
Autarkiegrad
Autarkiegrade
Autarkiegrades
Bottom
bzw
Clusteralgorithmen
Clusteransatz
Clusteransätze
Clusterebene
Clustergrundlage
Clusterung
Communities
CSV
DBSCAN
Distanzbasierte
Dynamic
Energiecommunities
Erzeugungs
Frameworks
Geo
Geodataframe
GeoJSON
Geopandas
Graphenbasierte
HAW
IDs
learn
Learning
Machine
Means
Merkmalsbasierte
Numpy
Numpys
Plugin
Plugins
Prosumer
PV
QGIS
scikit
Steven
up
Warping
Merkmalsbasierte
EPSG
Seed