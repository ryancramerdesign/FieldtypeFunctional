# ProcessWire Functional Fields 

**The “Functional Fields” module lets you make text translatable in your 
template files, much in the same way that you do with multi-language 
support in ProcessWire.**

When editing your site template files, you simply wrap the text you want to output 
in a function call. Hence the name “Functional”. By doing this, you make that 
apparently static text become dynamic text, editable in ProcessWire. Functional 
fields are ideal for text fields that you provide a default value for (in your 
template file) that the user can then change if they want to.

Example function calls used by Functional Fields:

```php
__text('your text');
__textarea('your text');
__richtext('<p>your text</p>');
```
For more details, usage instructions, please see the Functional Fields post at:
<https://processwire.com/blog/posts/functional-fields/>

## How to install

1. Copy all the files in this directory to /site/modules/FieldtypeFunctional/ 
2. In your admin, go to Modules > Refresh.
3. Click the "Install" button next to Fieldtype > Functional.
4. Create a new field (Setup > Fields > Add), choose "Functional Fields" as type. 

## History 

This module was part of the commercial ProFields set of modules between 2017 
and 2024. In that time, this particular module has not required significant 
support resources so no longer needs to be part of ProFields. Plus, we want 
to make room for new ProFields, though this module is very much in keeping 
with the purpose of ProFields. If you find this module useful, please 
consider getting the full ProFields package, as we're sure you'll find it 
very useful as well. Commercial support for this module is also available in 
the ProFields support board for current subscribers. 

More about ProFields: <https://processwire.com/store/pro-fields/>

## License

In June 2024 Functional Fields was released open source under 
the MPL 2.0 license: <https://processwire.com/about/license/mpl/>

Copyright 2017-2024 by Ryan Cramer