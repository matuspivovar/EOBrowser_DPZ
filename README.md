# 🌲 Forest Time-Series Analysis from Sentinel Hub EO Browser

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/matuspivovar/EOBrowser_DPZ/master?labpath=Time-series-EO-Browser.ipynb)
<p align="center">
  <img src="https://www.tuzvo.sk/sites/default/files/logo_tuzvo_farebne.png" height="70" alt="Technical University in Zvolen"/>
  &nbsp;&nbsp;&nbsp;&nbsp;
  <img src="https://www.sav.sk/uploads/users/1/Image/sav_logo_sk_farebne.png" height="70" alt="Institute of Forest Ecology SAS"/>
  &nbsp;&nbsp;&nbsp;&nbsp;
  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/b/be/ESA_logo.svg/1200px-ESA_logo.svg.png" height="70" alt="ESA Sentinel-2"/>
</p>
## Overview

Educational Jupyter notebook developed for students of **Geoinformation and
Mapping Technologies in Forestry** as part of a Remote Sensing course at the
[Technical University in Zvolen](https://www.tuzvo.sk) in collaboration with
the [Institute of Forest Ecology, Slovak Academy of Sciences](https://ife.sk).

The notebook guides students through the complete workflow of downloading,
processing, and analysing multi-temporal **Sentinel-2** satellite data from
[Sentinel Hub EO Browser](https://apps.sentinel-hub.com/eo-browser/) to
monitor forest dynamics over time.

## What This Notebook Covers

- Importing and structuring time-series data exported from EO Browser
- Computing and visualising spectral indices (e.g. NDVI) over time
- Detecting seasonal patterns and anomalies in forest cover
- Statistical analysis using regression and trend detection
- Producing publication-ready plots for reporting

## Run in Your Browser

No installation needed — click the **Launch Binder** badge above to open the
notebook interactively in your browser.

> First launch may take a few minutes while the environment is being built.

## Local Installation

```bash
git clone https://github.com/matuspivovar/EOBrowser_DPZ.git
cd EOBrowser_DPZ
pip install -r requirements.txt
jupyter notebook Time-series-EO-Browser.ipynb
```

## Tech Stack

`Python` · `Pandas` · `NumPy` · `Matplotlib` · `Seaborn` · `Scikit-learn` · `SciPy`

## Author

** M.Sc. et M.Sc. Matúš Pivovar, PhD.**
GIS & Remote Sensing | Forestry Applications
[Institute of Forest Ecology SAS](https://ife.sk) · [TUZVO](https://www.tuzvo.sk)

## License

[MIT](LICENSE)

