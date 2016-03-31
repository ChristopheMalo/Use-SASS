# How to use SASS

This project shows different tests with SASS.

The exemples follow the step by step 'learn sass' [official web site](http://sass-lang.com/)

I use version 3.4.22 (Selective Steve)

I use Sass syntaxe, not SCSS syntaxe

[command-or-whatever]: optionnal

## Install (On mac os x)
- Needs ruby (OS X Lion comes with ruby 1.8.7)
- Needs x code tool if you want upgrade to ruby 2.0 (for SASS 3.5)
- Command line to install SASS: [sudo] gem install sass
- Check the version: sass -v

## Use SASS
- Create a CSS folder
- Create a scss file, ex: input.scss [your-name-file.scss]
- Go to folder CSS
- To start watch the file, in folder CSS, run: sass input.scss output.css [your-ouput-file.css]
- To watch folder or directories: sass --watch app/sass:public/stylesheets
- Use variables