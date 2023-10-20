# Business and Biodiversity - Ch 4 - Snowball Pilot

[![DOI](https://zenodo.org/badge/DOI/99.9999/zenodo.9999999.svg)](https://doi.org/99.9999/zenodo.9999999)
[![Project Status: Active – The project has reached a stable, usable state and is being actively developed.](https://www.repostatus.org/badges/latest/active.svg)](https://www.repostatus.org/#active)
[![License: CC BY-SA 4.0](https://img.shields.io/badge/License-CC_BY--SA_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by-sa/4.0/)

This repository is part of an ongoing IPBES project.

The authors do not take any responsibility for it's copntent or the correct working of the code. If scripts in here wipe your data, you are on your own.

Nevertheless, please feel free to browse the code and re-use it at your own risk.

Once finalised, the final repo will be published on Zenodo

## Metadata

- **Project name**: Business and Biodiversity - Ch 4 - Snowball Pilot
- **Assessment**: Business and Biodiversity
- **Chapter**: Ch 4
- **Short Name**: `IPBES_BBA_Ch4_Snowball_Pilot_1`
  Please always include `IPBES_BBA_Ch4_Snowball_Pilot_1` in the title of the email to make sure it gets filtered correctly.
- **Status**: waiting for response and way forward

- **Assigned To**:
  - Rainer <Rainer.Krug@Senckenberg.de> <Rainer@krugs.de>

- **email to**:
  - LA <clement.feger@agroparistech.fr>
  - TSU Data <Rainer.Krug@Senckenberg.de>

- **email cc**:
  - LA <francesca.verones@ntnu.no>
  - LA <stephan.pfister@ifu.baug.ethz.ch>
  - TSU BBA <tsu.bizbiodiversity@gmail.com>
  - TSU Data <renske.gudde@senckenberg.de>
  - TSU Data <aidin.niamir@senckenberg.de>
  - ...

- **Github Repo**: [github repository](https://github.com/IPBES-Data/IPBES_BBA_Ch4_Snowball_Pilot_1)
- **Googl Drive Folder**: [Google Drive](<https://drive.google.com/drive/folders/12pNDoJEZFdjXgg6xh6c8INwdLUI-_Okw?usp=share_link>)

## Folders

- **`data`**: data files created during the running of the `snowball.qmd` file and contains cached as well as final data files.
- **`figures`**: figures created during the running of the `snowball.qmd` file in low-res as well as high-res.
- **`Key Papers`**: Key papers for the snowball pilot and a `.csv` and `.bib` file with the references
- **`R`**: R scripts used to create the figures and tables in the `snowball.qmd` file. Files in this folder will be sourced initially. These will later be moved into an R package.

## Status

- [x] Kepypaper were imported into Zotero and the `csv` and `bib` files were exported
- [x] `snowball.qmd` report file was created and the `R` scripts added
- [x] `snowball.html` report created and data files and figures created
- [ ] literature search will be done for two clusters
  - [ ] **authors** will provide key papers fand suggestions for possible additional search strateies to get the literature
  - [ ] citation clusters will be build for each and shown separately and combined
- [ ] Integrate reports into citation network
  - [ ] **Aidin** will investigate identification of link networks on the internet starting from identified reports
  - [ ] **Rainer** will investigate the possibility to use the `R` package `scholar` to identify papers citing the reports
  - [ ] **Rainer** will assess if the references can be extracted from the reports provided

## Reports

- [initial snowballing](snowball.html)
