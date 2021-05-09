# Personal Blog

This blog was created for me to share my travel and fitness adventures. I have kept some important information below on how to maintain and update the site. 

## Deployment

**Important:**  For security reasons, Github does not allow plugins (under `_plugins/`) when 
deploying with Github Pages. This means that we have to do one of the following:

Generate the site locally (more details below) and push the resulting HTML 
(the contents of `_site/` or `../blog-pages/`) to a Github repository, that GitHub Pages
then host. To do this, simply clone this repository (*master branch*), and then run
`bundle exec jekyll serve` inside the directory. Upload the resulting `_site/` (or `../blog-pages/`)
contents to your repository (*master branch* if uploading as your personal page
(e.g. username.github.io) or *gh-pages branch* if uploading as a project page. 

## Credits

This repository is created using the Jasper2 Jekyll theme as follows: https://github.com/jekyller/jasper2. 
