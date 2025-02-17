# FitGirl Repacks Game Browser
### [FGRG Browser](https://fgrg-browser.github.io/)

### Used plugins:

- [PapaParse](https://github.com/mholt/PapaParse) for parsing CSV
- [handsontable](https://github.com/handsontable/handsontable) for showing the parsed data as a spreadsheet

### Description

this is browser for the fitgirl repack site the original website lacks many filtering options and you cant even select the games categories so i made my own solution all 4910 games from the original fitgirl site are here where sort them by release date size of the repack and also you can filter by category 
and search by keyword 


all games are from fitgirl repack site we just share refrence links 



### run localy with docker 
- docker build -t web-image:v2 .
- docker run -d -p 8080:80 web-image:v2
