# insertAtCaret
A JavaScript package to insert a text at caret position.

* This package is inspired by [this tip](http://stackoverflow.com/questions/1064089/inserting-a-text-where-cursor-is-using-javascript-jquery).

# Installation
Using bower is the simplest way.

    bower install insert-at-caret --save-dev

# Preparation

Load insertAtCaret.js

    <script src="js/insertAtCaret/insertAtCaret.js"></script>

# Usage

***Basic Way***

    insertAtCaret('id', 'TEXT');
    
***Using Jquery***

    $('#id').insertAtCaret('TEXT');
    
# License
    
This package is licensed under the MIT License.  
Copyright 2016 Sukohi Kuhoh