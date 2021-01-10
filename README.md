# Economic datasets: a dashboard

<img class="avatar" align="left" alt="epogrebnyak" src="https://github.com/epogrebnyak.png?v=3&s=96" width="48" height="48" />

Hi, I'm Evgeniy Pogrebnyak, an economist who maintains to several economic datasets and codebooks. 
This data is open access - you can download the dataset or build it yourself locally. 
<a href="mailto:e.pogrebnyak@gmail.com">Drop me a line</a> if you find this work useful or it is similar to what you are with other data.

[tg]: https://t.me/epoepo
[tw]: https://twitter.com/PogrebnyakE

## Releases

- [boo](#boo)
- [weo](#weo)
- [ssg](#ssg)

<a name="boo">
  
### boo: Russian corporate financial reports for 2012-2018

[![](https://badgen.net/badge/icon/github?icon=github&label)][boo]

[boo]: https://github.com/ru-corporate/boo

**Motivation:** Rosstat published Russian corporate reports as open-source datasets 
in 2012-2018, but without metadata. The `boo` package knows where to 
download dataset from, assign variable names to columns and clean some  
erroneous rows. There you get access to financial statements of 2.5 million Russian 
firms.

<a name="weo">
  
### weo: World Economic Outlook releases since 2007 as pandas dataframes

[![](https://badgen.net/badge/icon/github?icon=github&label)][weo]

[weo]: https://github.com/ru-corporate/boo

**Motivation:** World Economic Ooutlook is an established publication with country macroeconomic forecasts
and historic statistics, but no interface for immediate use in python pandas. `weo`
package allows to download WEO releases by year and month and transform the data.

<a name="ssg">
  
### ssg-dataset: Static site generators popularity on Github

[![](https://badgen.net/badge/icon/github?icon=github&label)][ssg]
[![Download CSV](https://img.shields.io/badge/download-CSV-brightgreen)][url]
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.4429834.svg)](https://doi.org/10.5281/zenodo.4429834)

[url]: https://raw.githubusercontent.com/epogrebnyak/ssg-dataset/main/data/ssg.csv
[ssg]: https://github.com/epogrebnyak/ssg-dataset

**Motivation:** after experimenting with Hugo, Jekyll, MkDocs and several other SSG I needed
a better picture what drives the open source tool popularity.



<!--
## Scripts and demos
## Archive
-->
