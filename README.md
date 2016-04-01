# How to use Sass

This project shows different tests with Sass.

The exemples follow the step by step 'learn Sass' [official web site](http://sass-lang.com/)

I use version 3.4.22 (Selective Steve)

I use SCSS syntax, not SASS syntax

[command-or-whatever]: optionnal

## Install (On MAC OS X)
- Needs ruby (OS X Lion comes with ruby 1.8.7)
- Needs x code tool if you want upgrade to ruby 2.0 (for SASS 3.5)
- Command line to install Sass: [sudo] gem install sass
- Check the version: sass -v

## Use Sass
- Create an html file (to link the CSS and test the result)
- Create a CSS folder
- Create a Scss file, ex: input.scss [your-name-file.scss]
- Go to folder CSS
- To generate css file, run: sass [path-to]input.scss [path-to]output.css [your-ouput-file.css]
- To watch folder or directories: sass --watch app/sass:public/stylesheets
- To watch one file (generate output on save): sass --watch input-file.scss:output-file.css
- Use variables
- Use nesting
- Use referencing parent selectors: &
- Code partial Sass files, name the file with underscore: _name-of-partial-file.scss and use with @import directive
- Use @import
- Create mixins with @mixin
- Use @extend (Inheritance
- Use operators, doing math and create a simple fluid grid based on 960px

## Memento
- Install sass: gem install sass
- Convert Sass to Scss: sass-convert style.sass style.scss
- Concert Scss to Sass: sass-convert style.scss style.sass
- Generate ouptput css: sass input.scss output.css
- Update CSS file every time Sass file changes (saved): sass --watch input.scss:output.css
- Diretory with many files: sass --watch app/sass:public/stylesheets (aka source_folder:destination_folder)
- Help: sass --help