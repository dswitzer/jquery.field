jQuery Field Plug-in
============

This plugin greatly expands the ability to retrieve and set values in forms beyond
jQuery's standard <code>val()</code> method (and Mike Alsup's Form Plug-in's
<code>fieldArray()</code> method) by allowing you to interact with all types of
form field elements (except <code>input[type="file"]</code>, which is a
read-only element.) It works the same way for text elements as it does for
radio, checkbox and select elements.

The plug-in was built on the concept that you want to manipulate the fields
like their traditional variables. Selectors should be written to query a specific
field object (i.e. elements that would be linked together via a common name
attribute, for example <code>$("input[name='myRadioButton']")</code>.)

Elements that return multiple values are either separated by a comma or
returned as an array based on which methods you invoke.

For elements that allow more than one option to be select (select and
checkbox elements) you can specify a comma delimited list or an array of
values to mark multiple options as being selected.
