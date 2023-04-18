# Alfred workflow to replace semicolons/ commas from the clipboard

## The problem
Keywords in academic articles are usually separated by semicolons/dots or commas but if you try to copy and paste these keywords into Zotero (and possibly other reference managers), the whole list will be converted into a single tag. 

## The solution
In order for Zotero to create a separate tag for each keyword, each keyword has to be in a line of its own. In other words: semicolons/dots/commas need to be replaced by linebreaks. And that's exactly what this workflow does.

The workflow provides two ways of achieving the same thing:

You can copy the keywords the normal way (⌘+C) and then use the assigned hotkey to paste them, or
You can copy the keywords using universal actions (Select "Replace semicolons/dots and copy") and then paste them the normal way (⌘+V).


Either way, semicolons/dots will be replaced by linebreaks.

So replacing semicolons/dots is the default behaviour but in both cases, you can use the option key to replace commas instead of semicolons/dots.

Commas are not replaced by default, because they are sometimes used *within* keywords. So, when commas are used to spearate the keywords, you need to explicitly tell it so. 

A note on the dots: different journals use different dot-characters to separate their keywords. I included multiple versions, but you will probably come across some dot-characters that I missed. You can just add them into the [ ] inside the workflow.
