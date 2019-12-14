UW eScience Reproducible and Open Research Special Interest Group
============

View the page at http://uwescience.github.io/reproducible/

See information about the group at http://escience.washington.edu/about-us/working-groups/reproducibility-and-open-science/
 
Notes on maintaining the website:

- We're using blogdown with the [vex-hugo theme](https://github.com/themefisher/vex-hugo), and editing in RStudio. To see what the site looks like in RStudio: `blogdown::serve_site()`
- We do not edit the HTML files directly, we edit text in the source file data/homepage.yml on the source repo
- Source code for the page is at https://github.com/benmarwick/uwescience-reproducible-webpage-source
- We add images to static/images
- We edit menu anchors in the html files in themes/vex-hugo/layouts/partials
- The .git repo for these materials is in /public, and this is what goes to this GitHub repo to serve the page, cf. [the blogdown book](https://bookdown.org/yihui/blogdown/github-pages.html)

### Contributing

Before you make a substantial pull request, you should always file an issue and
make sure someone from the team agrees that it’s a problem. 

Small typos or grammatical errors in documentation may be edited directly using
the GitHub web interface, so long as the changes are made in the _source_ file.

### Code of Conduct

Please note that this project is released with a
[Contributor Code of Conduct](CODE_OF_CONDUCT.md). By contributing to this
project you agree to abide by its terms.