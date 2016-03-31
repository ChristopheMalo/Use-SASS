# How to use SASS

This project shows different tests with SASS.

The exemples follow the step by step 'learn sass' [official web site](http://sass-lang.com/)

I use version 3.4.22 (Selective Steve)

I use SCSS syntax, not SASS syntax

[command-or-whatever]: optionnal

## Install (On MAC OS X)
- Needs ruby (OS X Lion comes with ruby 1.8.7)
- Needs x code tool if you want upgrade to ruby 2.0 (for SASS 3.5)
- Command line to install SASS: [sudo] gem install sass
- Check the version: sass -v

## Use SASS
- Create an html file (to link the CSS and test the result)
- Create a CSS folder
- Create a scss file, ex: input.scss [your-name-file.scss]
- Go to folder CSS
- To generate css file, run: sass [path-to]input.scss [path-to]output.css [your-ouput-file.css]
- To watch folder or directories: sass --watch app/sass:public/stylesheets
- To watch one file (generate output on save): sass --watch input-file.scss:output-file.css
- Use variables
- Use nesting
- Code partial Sass files, name the file with underscore: _name-of-partial-file.scss and use with @import directive
- Use @import
- Create mixins with @mixin
