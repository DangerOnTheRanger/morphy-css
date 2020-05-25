Morphy.css - neumorphic CSS widget library
==========================================

**Morphy.css** is a neumorphic widget library - you bring any fonts/layout you like, and Morphy.css styles your widgets!

What's neumorphism? In a nutshell, it's the skeumorphism (mimicking real-life stuff) of old with a shiny new softly gradiented look.
A picture's worth a thousand words - take a look at the screenshot section.


Screenshots
-----------

![Music player](https://raw.githubusercontent.com/DangerOnTheRanger/morphy-css/master/musicplayer.jpg)

Demo
----


Usage
-----

Morphy.css is classless - drop a `<link rel="stylesheet" href="morphy.css">` in your HTML, and you're good to go!

Widgets implemented
-------------------

Hopefully at some point, I'll cover all interactable HTML widgets, and maybe provide a few pure
custom CSS widgets.

* Buttons
* Checkboxes
* Radio buttons
* Dropdowns
* Progress bars (indeterminate bars are currently unsupported)
* Tables

Morphy.css also provides a few mixin classes that allow you to make your own neumorphic components:

* `mc-raised[-small|-large]` - Provides a medium/small/large raised border that can be used for sections/cards. This
  class doesn't round the border, however; round the border according to your own tastes.
* `mc-lowered[-small|-large]` - Provides a medium/small/large lowered border. This class doesn't round borders, either.


Customization
-------------

Morphy.css makes use of many CSS custom properties - look at the top of the source code for documentation on them.


License
-------

Morphy.css is licensed under the MIT License.
