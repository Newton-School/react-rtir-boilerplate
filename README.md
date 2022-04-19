# Telescoping string

We have an input with id="text-input" and div with id="text-span-holder",
what we need to implement is as the user types in the input
for each character typed we create a <code>span</code> inside <code>#text-span-holder</code>div
 with increasing font size starting with 12 and increasing by 1px.

Example:-
User types "Hello" inside input.
Inside <code>#text-span-holder</code
<span>H</span>  // fontSize:12px
<span>e</span>  // fontSize:13px
<span>l</span>  // fontSize:14px
<span>l</span>  // fontSize:15px
<span>o</span>  // fontSize:16px

Use keys for span and id of format <code>char-${index}</code> for span.

