# BGGN239Spring2023

## Build page: first time users
Assuming you have already installed all dependencies (see below), clone this repository, then
```bash
cd BGGN239Spring2023
bundle init
bundle add jekyll  jekyll-default-layout jekyll-feed jekyll-optional-front-matter jekyll-paginate jekyll-redirect-from jekyll-relative-links jekyll-sitemap  classifier-reborn
jekyll build
```
## Update page
Only necessary if the changes alter the path to a file or link. If not, it updates automatically.
```bash
cd BGGN239Spring2023
git pull
jekyll build
git add .
git commit -m 'update'
git push
```
Keep in mind that it might take a few minutes for the changes to be reflected in the page.


## Installation (recommend using mamba)
```bash
mamba create --name jekyll
```
