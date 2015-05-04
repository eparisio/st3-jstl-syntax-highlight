# sublime text 3 JSTL and JSP syntax highlight
Basic support for sublime text 3 jstl and jsp syntax highlight.

Based on original Java Server Page(JSP) syntax highlight.

#### File support
* jsp
* tag

#### develop note:
* highlight __all__ jstl base tags(```<xxx:xxx>```), parameter in the tag(```xxx="```) and server variable(```${}```)
* ~~add support for all jstl tag~~ - added general regex for __jstl tags and custom tags__
* ~~review regex for highlight end-closing tag with parameter~~ - added support and internal text highlight
* ~~add highlight for jstl operation inside tags (and,or,<,>,eq,ne,=,etc..)~~ add highlight for operator, add highlight for jstl functions
* add hilight support for all base color scheme

### TO DO:
* ~~add support for all jstl tag~~
* ~~review regex for highlight end-closing tag with parameter~~
* ~~add highlight for jstl operation inside tags (and,or,<,>,eq,ne,=,etc)~~
* ovverride html syntax color in normal html tag for nested tags/server var
