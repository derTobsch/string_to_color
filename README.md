String to Color
===============

Tiny library to generate the same nice hex color for a string in Javascript. 

###Features 

- Sexy colors, not muddy browns and boring grays
- Binary safe


### Why it needed to exist 

I needed a way to generate a consistent NICE color for any given word 
to assign a tag it's own independent color  (without knowing what all tags are).


### How to use it

####Bower

Add it to your bower.json

    "dependencies": {
        "stringToColor": "https://github.com/derTobsch/stringToColor.git#1.0.1"
    }


###EcmaScript 6 (ES6)

StringToColor Is realized as an EcmaScript 6 Module.
You can find the ES6 Module in

    dist/string-to-color.js

###Universal Module Definition (UMD)

The pattern is admittedly ugly, but is both AMD and CommonJS compatible,
as well as supporting the old-style “global” variable definition.

If your engines do not support EC6 you can use the UMD Module

    dist/string-to-color.umd.js


###Demo 

http://dertobsch.github.io/stringToColor/


###License
 
String to color is licensed under the Apache License 2.0