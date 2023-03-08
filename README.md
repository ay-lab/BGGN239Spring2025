# BGGN239Spring2023

Available in https://ay-lab.github.io/BGGN239Spring2023/

## Installation (recommend using conda/mamba)
Clone this repository, then:
```bash
conda env create --file  jekyll_env.yml
```

## Build page: first time users
Assuming you have already installed all dependencies and cloned the repository.
```bash
cd BGGN239Spring2023
conda activate jekyll
bundle init
bundle add jekyll  jekyll-default-layout jekyll-feed jekyll-optional-front-matter jekyll-paginate jekyll-redirect-from jekyll-relative-links jekyll-sitemap  classifier-reborn
#jekyll build
jekyll build
```
Note: make sure to add the Gemfile to your .gitignore

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

