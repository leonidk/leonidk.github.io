# updated website

This mostly comes from [Jon Barron's website](https://jonbarron.info/) and is converted for my own use, re-purposing my old markdown posts. Feel free to use this for your own purposes. 

**Jekyll** is a static site generator that's perfect for GitHub hosted blogs ([Jekyll Repository](https://github.com/jekyll/jekyll)) **Jekyll Now** makes it easier to create your Jekyll blog, by eliminating a lot of the up front setup and is from [this repository](https://github.com/barryclark/jekyll-now).

## issues
* In general, jekyll will try to build a full page for every post. I skip that by forcing `permalink: /`. This creates multiple entries in sitemap.xml for index.html but is otherwise fine. 
* If you want multiple paragraphs, consider using `excerpt_separator: <!--more-->` in `_config.yml`, for my own use I didn't need this. 
