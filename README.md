# blogstrapper
Modern, responsive theme for Blogger

## Overview
This project aims to provide a modern and responsive bootstrap theme for a Blogger blog. Multiple screen resolutions and sizes are supported with the same layout (for phones, tablets, desktops, etc). Demo:  [http://blogstrapper.blogspot.com](http://blogstrapper.blogspot.com)

## Key Features
- Blog Search and Feeds (RSS/Atom)
- Frameworks: Bootstrap, FontAwesome, jQuery
- SEO: Canonical URL, Meta Description, Optimized Page Title support
- Out of the box integration with Facebook, Twitter, Disqus and Google Analytics
- Cookie consent request for compliance with [EU Cookie Law](http://www.cookielaw.org/the-cookie-law/)

## Widgets
- Link List and About Section
- Labels with List and Cloud views
- Responsive Navigation Menu with Static Pages and custom links
- Archive with Hierarchical, Flat and Menu views
- Popular Posts with titles, descriptions and thumbnails

## How to use
1. [Download](https://github.com/marcosbozzani/blogstrapper/archive/master.zip) the project and extract it
1. Open in a browser the file **maps/_map.html** 
1. Select the **template.xml** file, choose a map file (e.g. **maps/en-us.map**) and click on the **Go!** button
1. Copy the generated template code
1. Open **Blogger** and select the desired blog
1. On the blog's dashboard, open the **Template** section and click **Edit HTML** button
1. Paste the generated template code and click on the **Save Template** button
1. Visualize your blog with the new theme. **Done!**

## Customization
### Basic customization
Simple customization can be done by editing a map file:

- To enable Google Analytics set: analytics_config.id
- To enable Disqus Comments set: disqus_config.shortname
- To change Disqus interface language set: disqus_config.language
- To provide a like to the blog privacy terms set: cookieconsent_options.link

### Advanced customization
For further customization, it is advisable to edit the template file directly.

### Translations
For translations choose an appropriated map file (e.g. *pt-br.map* for Brazilian Portuguese) or create a new one with your own translated values. Note that some translations are provided by the Blogger engine. In those cases, you can either change the blog's language in the Blogger's Dashboard or create customs keys in the map file and change the template file accordingly.

## License
This project is released under the terms of the MIT license. [View](https://github.com/marcosbozzani/blogstrapper/blob/master/LICENSE)

The MIT License is simple and easy to understand and it places almost no restrictions on what you can do with this project.

You are free to use this project in any other project (even commercial projects) as long as the copyright header is left intact.