# How to use Sass

This project shows different tests with Sass.

The exemples follow the step by step 'learn Sass' [official web site](http://sass-lang.com/)

I use version 3.4.22 (Selective Steve)

I use SCSS syntax, not SASS syntax

[command-or-whatever]: optionnal

## Install (On MAC OS X)
- Needs ruby (OS X Lion comes with ruby 1.8.7)
- Needs x code tool or command line tools from apple developer download site if you want upgrade to ruby 2.0 (for SASS 3.5)
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
- Nested properties with 'namespaces'
- Use interpolation #{}
- Code partial Sass files, name the file with underscore: _name-of-partial-file.scss and use with @import directive
- Use @import rule
- Use nested @import rule
- Use nested @media rule
- Create mixins with @mixin directive
- Use @extend (Inheritance)
- Use @extend with complex selectors
- Use multiple @extend
- Use @at-root directive to be emmitted rules at the root of the doc, can use with @media directive
- Use @debug directive
- Use operators, doing math and create a simple fluid grid based on 960px
- Use comments and # in comments
- Use Control directives & expressions (@if, @for, @each)
- Use function directives (@function)

##Use interactive shell and SassScript
- type text between "": >> "Hello world" returns Hello world
- >> 1px + 1px -> returns the result 2px
- variables $variable-name is SassScript
- variable access as $variable-name or $variable_name is same
- use global in variable to access in all attribute: $heigth: 2em !global;

## Memento
- Install sass: gem install sass
- Convert Sass to Scss: sass-convert style.sass style.scss
- Concert Scss to Sass: sass-convert style.scss style.sass
- Generate ouptput css: sass input.scss output.css
- Update CSS file every time Sass file changes (saved): sass --watch input.scss:output.css
- Diretory with many files: sass --watch app/sass:public/stylesheets (aka source_folder:destination_folder)
- Help: sass --help
- Open interactive shell to use SassScript: sass -i
- Close shell: ctrl c