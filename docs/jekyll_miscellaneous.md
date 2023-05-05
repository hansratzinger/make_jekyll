# Jekyll miscellaneous

### Jekyll in htdocs/subfolder

1. Edit _config.yml

    `````
    baseurl: "/subfolder"
    `````

2. Run

    ````
    bundle exec jekyll serve
    `````

--------------------

### Line breaks in Markdown files  

Jekyll is not rendering line breaks in HTML.  
Solution: Enter **two** spaces after the last word before pressing Return.

[Source](https://stackoverflow.com/a/52796572/11634713)
