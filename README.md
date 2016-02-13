# Jekyll Starter Theme - Minimial


A minimalistic Jekyll starter theme for "classic" web sites (e.g. just some web pages)


```
├── _config.yml                  # site configuration
├── _layouts
|   └── default.html             # master layout template
├── css
|   └── style.css                # styles
├── three.html                   # another sample page (in hypertext markup e.g. html)
├── two.md                       # another sample page (in markdown e.g. md)
└── index.md                     # index (start) sample page (in markdown e.g. md)
```

Becomes

```
└── _site                        # output build folder; site gets generated here
    ├── css
    |   └── style.css            # styles for pages (copied 1:1 as is)
    ├── three.html               # another sample page
    ├── two.html                 # another sample page 
    └── index.html               # index (start) sample page
```

### Live Demo

See a live demo @ [`henrythemes.github.io/jekyll-starter-theme` »](http://henrythemes.github.io/jekyll-starter-theme)


### Version 2.0

Note: For a more "advanced" starter theme, see the
[Jekyll Starter Theme V2](https://github.com/henrythemes/jekyll-starter-theme-v2).
The V2 includes:

- Shared (common) template/page building blocks using `_includes` e.g. `head.html`, `header.html`, `footer.html` etc.
- CSS preprocessing using Sass/SCSS e.g. `_settings.scss` with `$link-color` etc.
- Nav(igation) menu (auto-)built using a configuration / data block
- And more

### More Themes

See the [Dr. Jekyll's Themes](https://drjekyllthemes.github.io) directory.


### More Quick Starter Wizard Scripts

See the [Mr. Hyde's Scripts](https://github.com/mrhydescripts/scripts) library.



## Meta

#### License

The starter theme is dedicated to the public domain.
Use it as you please with no restrictions whatsoever.

#### Questions? Comments?

Post them to the [wwwmake forum](http://groups.google.com/group/wwwmake). Thanks!

