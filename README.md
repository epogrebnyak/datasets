# EPo: My dataset dashboard

<img class="avatar" align="left" alt="epogrebnyak" src="https://github.com/epogrebnyak.png?v=3&s=96" width="48" height="48" />

Hi, I'm Evgeniy Pogrebnyak, an economist and open data enthusiast, who maintains several economic datasets and codebooks. 
This data is open access - you can download the dataset or build it yourself with code provided. 

<a href="mailto:e.pogrebnyak@gmail.com">Drop me a line</a> if you find this work useful or it is similar to what you are doing with other data.

[tg]: https://t.me/epoepo
[tw]: https://twitter.com/PogrebnyakE

## Releases

[boo](#boo) - [weo](#weo) - [ssg](#ssg)

<a name="boo">
  
### boo: Russian corporate financial reports for 2012-2018

[![](https://badgen.net/badge/icon/github?icon=github&label)][boo]
![](https://badgen.net/pypi/v/boo)
![](https://badgen.net/github/last-commit/ru-corporate/boo)

[boo]: https://github.com/ru-corporate/boo

**Motivation:** Rosstat published Russian corporate reports as open-source datasets 
in 2012-2018, but without metadata. The `boo` package knows where to 
download dataset from, assign variable names to columns and clean some erroneous rows.
There you get access to financial statements of 2.5 million Russian firms.

<a name="weo">
  
### weo: World Economic Outlook releases since 2007 as pandas dataframes

[![](https://badgen.net/badge/icon/github?icon=github&label)][weo]
![](https://badgen.net/pypi/v/weo)
![](https://badgen.net/github/last-commit/epogrebnyak/weo-reader)

[weo]: https://github.com/ru-corporate/boo

**Motivation:** IMF World Economic Ooutlook is an established source for country macroeconomic forecasts
and historic statistics, but has no interface for immediate use in Python pandas. `weo`
package allows to download WEO releases by year and month and transform the dataset by choosing 
a country, variable or a year.

<a name="ssg">
  
### ssg: Static site generators popularity on Github

[![Download CSV](https://img.shields.io/badge/download-CSV-brightgreen)][url]
[![](https://badgen.net/badge/icon/github?icon=github&label)][ssg]
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.4429834.svg)](https://doi.org/10.5281/zenodo.4429834)
[![Open in Streamlit](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)][st]
[![Demo in Google Colab](https://img.shields.io/badge/Colab-Open-orange)][colab]
![GitHub last commit](https://img.shields.io/github/last-commit/epogrebnyak/ssg-dataset)

[url]: https://raw.githubusercontent.com/epogrebnyak/ssg-dataset/main/data/ssg.csv
[ssg]: https://github.com/epogrebnyak/ssg-dataset
[st]: https://share.streamlit.io/epogrebnyak/ssg-dataset/main
[colab]: https://colab.research.google.com/drive/1041e6yOyVRty5lirnbZOAU1zJ3TN77ta

**Motivation:** after experimenting with Hugo, Jekyll, MkDocs and several other SSG I needed
a better picture what drives the open source tool popularity in modern web authoring.

<!--
## Scripts and demos
## Archive
-->
