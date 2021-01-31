# Introducing CSS

CSS allows you to create rules that specify how the content of an element should appear.

CSS Properties Affect How Elements Are Displayed CSS declarations sit inside curly brackets and each is made up of two parts: a property and a value, separated by a colon. You can specify several properties in one declaration, each separated by a semi-colon.

h1, h2, h3 {
font-family: Arial;
color: yellow;}

| Selector | Meaning |  |
| ---  | --- | ----------- |
| Universal Selector | Applies to all elements in the
document | * {}
Targets all elements on the page |
| Type Selector | Matches element names | h1, h2, h3 {}
Targets the <h1>, <h2> and <h3>
elements | Class Selector | Matches an element whose
class attribute has a value that
matches the one specified after
the period (or full stop) symbol |.note {}
Targets any element whose class
attribute has a value of note
p.note {}
Targets only <p> elements
whose class attribute has a
value of note|
|ID Selector|Matches an element whose
id attribute has a value that
matches the one specified after
the pound or hash symbol|#introduction {}
Targets the element whose
id attribute has a value of
introduction|
