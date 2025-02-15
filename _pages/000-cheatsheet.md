<p>
Books - Coming Soon
</p>
<md-block>
# MD-Block Plugin Test

*This is a test of the MD-block plugin implementation.*

Cheatsheet sourced from [Markdownguide.org](https://www.markdownguide.org/basic-syntax/)

* The code was implemented in the /_includes/tracking-header.html file.

# This is a size 1 header.

## This is a size 2 header.

### This is a size 3 header.

#### This is a size 4 header.

##### This is a size 5 header.

###### This is a size 6 header.

*This text is in italics.*

**This text is in bold.**

***This text is in bold and italics***

> This is a block quote.
> You can tell by the way it is blocky.

> This is also a block quote.
>
	>> But it is a nested block quote.
	>> You can tell by the way in which it is nested.
> 
> Normal formatting, such as *italics*, **bold** and so on also work inside block quotes.
	>> ## Headings also work in block quotes.
	
## Ordered Lists

1. These are made by adding line items with numbers, followed by a period.
2. As an example: 3. would be next in line in this list.

## Unordered Lists

* Unordered lists can be made simply by placing an asterisk ( * ) followed by a space at the beginning of the line item.
* Dashes ( - ) and plus signs ( + ) can also be used, but asterisks ( * ) should be used by default.
	* Nested lists can also be created, by indenting the line before placing the initial asterisk.
* And subseqently de-nested again later.

## Adding an image

![Test adding an image, by using the UM logo](/assets/images/demo1.jpg)
	
## Horizontal rules
* To add a horizontal rule, use three or more asterisks, dashess or underscores on a line.
* Use dashes to maximize legibility in coding

---

## Adding links

* To add a link, use [link display name](https://ulfhednar-asn.github.io).
* To add a hover-over description to the link, use [link display name](https://ulfhednar-asn.github.io "this is the hover-over description").
* Links can also be added without naming it, simply by enclosing it in chevrons:
	* <https://ulfhednar-asn.github.io>

## Reference links

This type of links can be used to reference other links internally on the same page.

### First part of the reference link:
* The first set of brackets denotes the *display name* of the link.
* The second set of brackets are the *label* used as a reference for the other link.

[reference link display name][reference label]


### Second part of the reference link:
* The first part is the *label* in brackets is followed by a colon, and at least one space.
* The second part is the *URL* for the link, enclosed in chevrons.
* The third part is the *title* for the link, enclosed in parentheses.

[reference label]: <https://ulfhednar-asn.github.io/> (Ulfhednar Miniatures)

This concludes the test.
</md-block>
