# css notes

## things to remember
- inline elements flow within the text w/o starting a new line
- block elements start a new line with each element
- rules are structured with a selector folowed by a declaration `<tag {thing your making the tag do!;other thing you want it to do;}>`
- css changes how things are displayed
- you can put css in the html file via `<style>` or its own via 
`<link>` but external files are preferd for most css
- linking in looks like `<link href="css file link" type="text/css" rel="stylesheet" />`
- style use goes in head


## cheet sheet

Console code | What it does
--------------|-------------
`* {}` | universal selector apply changes to all elements in the document
`tag {}` | type selector targets elements with this tag type
`.'class' {}` | matches to 'class' attribute defined behind the dot
`#'id' {}` | matches to 'id' attribute defined behind the hash ids hold highest priority for an element
`tag>tag2 {}` | child selector selects a child of a tag to be modified
`tag tag {}` | descendant selector targets an element within an eliment
`tag+tag {}` | adjacent sibling selector targes elements that follow a nother type of element but no others
`!important` | at the end of a css rule makes it override any other conflicting rules
`font-size {}` | changes the size of the font with in associated element useing a variaty of measurments including pixels(px) or point(pt)

