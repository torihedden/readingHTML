### What is a Tag?

A tag's name is the text in between the two angle brackets < >. The opening tag is inside angle brackets, and closing tags contain the tag name preceded by a backslash \. Tags create elements. The content found within the angle brackets will be "contained" within the tag. Tags are instructions to the browser about what kind of content to generate. [5]

## `<!DOCTYPE>`

A document type declaration [7]. Begins a document, AKA is a document type definition [6]. This indicates that the code following this notation will be HTML, if <!DOCTYPE> is followed by <html>.

## `<!-- -->`

Creates a comment. Text within this "tag" will not display on a webpage. Used for leaving notes and reminders in the code, useful for the original author and for any other humans reading the code. Computers don't care about comments.

* _parents_: none, this is not an element or a tag
* _content_: none
* _display_: none

## `<html>`

The whole `document`, which wraps all elements in an HTML document, except for [`<!DOCTYPE>`](#doctype).

* _parents_: none, it's the top of the HTML document
* _content_: _only_ [`<head>`](#head) and [`<body>`](#body)
* _display_: `block`, maybe? I mean, I can see it... RESEARCH!

## `<head>`

* _parents_: `html`
* _content_: `title` of your page (this shows up in the tab in your browser!), a `link` to a stylesheet, a `link` to javascript files too. Provides metadata about the page. [2]
* _display_: not applicable, because it doesn't display elements on the page. I'm going with none.

## `<body>`

* _parents_: `html`. [`<body>`] is the second child of an [`<html>`] tag.
* _content_: allows for [Flow Content] [3].
* _display_: `block`

### Attributes

* `class` -- a space-separated list of category names
* `dir`	-- a global attribute that defines the text direction. Value is either ltr (Left-To-Right) or rtl (Right-To-Left) [8]
* `hidden` -- global attribute that indicates the visibility of some elements. A Boolean attribute. Elements with this attribute won't be rendered by the browser. [9]

* `Global attributes` -- attributes that can be applied to all HTML elements. However, using these attributes on some elements will have no effect. [9]

## `<div>`

A generic page division that should only be used if no other, more semantic choice is appropriate.

* _parents_: anything that accepts [Flow Content][1].
* _content_: any [Flow Content][1], palpable content
* _display_: `block`

## `<h1>`

A header tag. The number after h denotes a relative size this tag will display as, with 1 being the largest, all the way to 6, the smallest.

* _parents_: phrasing content, any element that can contain flow elements, hgroup (a group of headings)[10]
* _content_: Flow content, heading content, palpable content [4]
* _display_: `block`
. . .

## `<span>`

* _parents_: Any element that can contain phrasing elements
* _content_: phrasing content (e.g. `<em>`, `<strong>`, and `<label>`)[11]
* _display_: `block`

## `<li>`

an element in a list. each item in the list must be surrounded by these tags.

* _parents_: `<ul>` or `<ol>`, unordered list and ordered list, respectively.
* _content_: Flow Content [12]
* _display_:`block`

## `<dl>`

a description list [13]

* _parents_: any elements that can contain flow elements
* _content_: `<dt>` elements, followed by `<dd>`
* _display_: `block`

## `<dt>`

a term or name in a description-list. Always requires a start tag but does not require an end tag if the element is followed immediately by another `<dt>` or `<dd>` [14]

* _parents_: `<dl>`
* _content_: Flow content
* _display_: `block`

## `<form>`

a submittable form, filled out by a user. requires a start and end tag. [15]

* _parents_: any element that can contain flow content
* _content_: flow content
* _display_: `block`

## `<table>`

used for storing and organizing data, using columns and rows.

* _parents_: any element that can contain flow elements [16]
* _content_: an optional caption (aka title), `<colgroup>` elements (columns), `<tr>` (rows), `<tbody>`, `<tfoot>`
* _display_: `table`

## `<img>`

an image

* _parents_: Any element that can contain phrasing elements. [18]
* _content_: empty. this is a void element (an element that is never allowed to have contents under any circumstances. Can have attributes.) [17]
* _display_: `inline-block`

###### Footnotes

[1](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/Content_categories#Flow_content)
[2](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/head)
[3](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/body)
[4](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/Heading_Elements)
[5](https://developer.mozilla.org/en-US/docs/Glossary/Tag)
[6](https://en.wikipedia.org/wiki/Document_type_declaration)
[7](https://en.wikipedia.org/wiki/Document_type_definition)
[8](https://developer.mozilla.org/en-US/docs/Web/HTML/Attributes)
[9](https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes)
[10](https://www.w3.org/TR/html-markup/h1.html)
[11](https://www.w3.org/TR/html-markup/span.html#span)
[12](https://www.w3.org/TR/html-markup/li.html#li)
[13](https://www.w3.org/TR/html-markup/dl.html#description-list)
[14](https://www.w3.org/TR/html-markup/dt.html#dt-term)
[15](https://www.w3.org/TR/html-markup/form.html#form)
[16](https://www.w3.org/TR/html-markup/table.html#table)
[17](https://www.w3.org/TR/html-markup/syntax.html#void-element)
[18](https://www.w3.org/TR/html-markup/img.html#img)
