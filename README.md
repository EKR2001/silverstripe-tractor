# silverstripe-tractor

Tractor is a set of CMS enhancements for the Silverstripe platform.  Currently it is an internal Kindleman tool, soon to be released as open source.

docs for the flexible content component


Shortcodes
----------------
Tractor includes Social Embeds.  You can use them to place social feeds in your WYSIWYG content areas.

https://github.com/asecondwill/silverstripe-social-embed-shortcodes

![alt text](shortcodes.png)

Blocks
---------------
Pages have a tab "Blocks".  Click into that and view the dropdown of block types.  Select one and click add to start creating. Click the preview button to see where the blocks will go.

![blocks](blocks.png)]

Blocks can be ordered using the drag handle on the left.

## Block Types


### Content Block

Straightforward WYSIWYG / TINYMCE field.   




Classes
----------------
You can add some special classes to elements to add styling.  

Push-down - adds margin top
Button - turns a link into a button

Sass Framework
----------------
Tractors Css is based on the Sass framework Foundation.  The docs for foundation are useful when using Tractor's blocks components or developting new themes.   Tractors blocks aims to provide various foundation elements as flexible content.   

http://foundation.zurb.com/sites/docs/



Forms
-----------------
Tractor includes Silverstripe's userforms module.  To add a form,  create a page of type UserDefinedForms.  Click the FormFields tab and add fields. There is [Further UserForms documentation](https://github.com/silverstripe/silverstripe-userforms/blob/master/docs/en/userguide/index.md) available.


