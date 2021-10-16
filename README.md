This is the source for my [website](https://projects.ayanc.org/) as a Jekyll
template (which means it can be served directly by Github Pages). The website
design is partly inspired by Jon Barron's [site](https://jonbarron.info/). 
This template uses Bootstrap and tries to be responsive to adapt to display 
sizes of phones and tablets.

The "content" of the website is in the `info.yml` and `papers.yml` 
files in the `_data/` directory. To make your own site:

1. Fork this repo. You may want to clean out the `faces/` and `teasers/` 
  directories. 
2. Edit the `info.yml` file to put in your own info, bio, etc. Note that
  some content (such as the bio, content of addtional sections) is 
  specified as multi-line strings in YAML. Make sure you know the format
  and indent everything correctly. These strings are also passed through
  a markdown converter, so you can use markdown syntax to specify links,
  etc.
3. Edit the `papers.yml` file to list your publications/research projects.
  The teaser field provides the name of teaser images (to be stored as 
  `teasers/NAME.jpg`), so make sure you create those.
4. To put any analytics code, edit the `index.html` file directly.
5. Make sure you test your site on mobile/tablet displays.

Feel free to use the template. If you like, please leave the line at the end
pointing back to this repo.
