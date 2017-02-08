# EqnEditor Fix

There is a bug at the original [EqnEditor Code](http://ckeditor.com/addon/eqneditor), when you use more than one editor at the same page.

Due it's dependency on jQuery and DOM browsing selector, the math overlay only opens at the very first editor used by the user at the page, as informed at some forums at the web:

* [multiple eqneditor of ckeditor not showing math overlay](https://stackoverflow.com/questions/38055970/multiple-eqneditor-of-ckeditor-not-showing-math-overlay)
* [CKEDITOR EqnEditor(Math plugin) not working on multiple instances on same page](https://stackoverflow.com/questions/40484643/ckeditor-eqneditormath-plugin-not-working-on-multiple-instances-on-same-page)

# What I did?

I've added a little correction at this code, created by Kevin Willians, due this age. Now it's working at the current versions of CKEditor and EqnEditor.

I hope somewhen in the future this code be merged with the original trunk. As I am not de maintainer of the EqnEditor, I cannot do that much.

# How to use

Pretty simple: add a reference to fixEquation.js at your page. That's it.

# Dependency

Off course, [EqnEditor Code](ht1tp://ckeditor.com/addon/eqneditor) and [jQuery](http://www.jquery.com).

# Thanks

* [Kevin Willians](https://twitter.com/kmwill23)