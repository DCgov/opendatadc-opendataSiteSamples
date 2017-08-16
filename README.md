# opendatadc-starterkit
This repository is a collection of samples designed for use with ESRI's opendata site builder. To use simply drop into a text box and replace images, text, and link urls as needed.

This repository is under construction, thank you for your patience.

Introduction
----------
<b>Coming soon...</b>

How to use
----------
<b>Coming soon...</b>

 File | Description | Link
---|---|----
3-cards.html| | [image](img/3-cards.PNG)
4-cards.html| |
5-medallions.html| |
6-medallions.html| |
footer-sample.html| |
left_image-right_text-with-buttons.html| |
three-horizontal_w-one-top_two-bottom.html| |
top_w_bottom-left-right.html| |

Glossary
----------
*Under Construction - thank you for your understanding*

 Term | Use
---|---
div| Defines elements; does not have any defined style of its own
br| Inserts a break between elements
a| Used to define text that links to a url or resource; text between the open and closing tag will be linked; see href
p| A standard tag used for text, not always necessary but can help with code readability
ul| An unordered list; the opening tag that contains li elements
li| List items contained within ul or ol elements
img| Used to place an image; must be paired with a 'scr' tag to link file
span| allows for the insertion of style elements within another element
h#| This tag applies a header style to the text within; 1 being the largest and 6 being the smallest
href=""| Used in conjunction with 'a' tag; place url or source link in opening tag to make related text linked
src=""| Used in conjunction with 'img' tag; place url for img link in opening tag to add linked image
alt=""| Allows for 'alt' text to be included; important to readability of pages for page readers
col-'size'-'value'|The way Bootstrap defines the page behavior; 'size' defines the screen size where the behavior occurs; 'value' defines how much of the page the object fills

Advanced Usage
----------
While these samples should allow for a number of the elements seen on DC's Open Data pages to be recreated there are certain aspects that may require some additional modifications to properly scale based on your desired elements.
The ESRI open data sites are based on bootstrap and use it for much of their reactivity. To allow for maximum configurability we recommend using just code within a single text box. While ESRI's tools can be very helpful, those experienced with HTML may find it easier to work almost exclusively with the HTML.

A few specific recommendations for those working with the html:
-when placing an image alongside text the use of either sm, md, or lg as break points may be best based on your image size, we recommend trying each to see what works best for your specific layout
-while many of the samples assume equal sections for each element, if a single element is intended to stand out or take more space, we recommend playing with the way the bootstrap columns are split among the elements to achieve your desired layout

Contributing
------------
See [CONTRIBUTING.md](../master/CONTRIBUTING.md)

License
----------
See [LICENSE.md](../master/LICENSE.md)"# opendatadc-opendataSiteSamples" 
