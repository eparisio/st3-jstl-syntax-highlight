# sublime text JSTL and JSP syntax highlight
Better support for sublime text jstl and jsp syntax highlight.

Based on original Java Server Page(JSP) syntax highlight.

#### File support
* jsp
* tag

#### Installation
##### Using Package Manager

The easiest way to install is to use the Package Control extension. Once this is installed, simply select 'Package Control: Install Package' from the command pallette and search for 'JSTL syntax'.

##### Manually

Within Sublime Text, click Preferences > Browse Packages... and create a folder named JSTL. Clone this repo or add 'jstl.tmLanguage' file into the folder.

#### develop note:
* highlight __all__ jstl base tags(```<xxx:xxx>```), parameter in the tag(```xxx="```) and server variable(```${}```)
* add highlight support for all base color scheme
* added general regex for __jstl tags and custom tags__
* added support and internal text highlight
* add highlight for operator, add highlight for jstl functions
* add highlight for nested tags and vars!
* fix some compatibility with cross-language nesting
* add new jstl support with snippets and autocomplete at: https://github.com/eparisio/st3-jstl-snippet-autocomplete

### TO DO:
 * fix other compatibility/regex with mixed nested language syntax
 * ## Add support for sublime text 4

### Contribute

If you want contribute follow the project at: 

* https://github.com/eparisio/st3-jstl-syntax-highlight
