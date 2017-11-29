# opendatadc-starterkit

What is Here
----------
The District of Columbia government has created its open data site using the <a href="http://doc.arcgis.com/en/hub/sites/design-the-layout-of-your-open-data-site.htm">Esri ArcGIS open data</a> platform. This provides several widget and card elements for easy drag, drop and configuration provided users have a mature ArcGIS Online organization containing data and web apps. In addition to these, DC government has created a collection of its own custom elements. Here you will find code samples for DC open data elements along with helpful steps to begin.


Get Organized
----------
We are excited that you have chosen to lead and build a DC open data site. Just remember, your site's primary purpose is to be an <b>open data site</b> - explore, engage, educate and enrichment via data. Begin by working with a smaller focus. You can always grow the site and its pages.

    Identify an Open Data Team
        Administrator - one admin who will build and manage the site
        Content Editors - group who will author written narratives, create web apps, quality check
        Data Curators - group who will act as data owners, quality check and work with OCTO to publish
        IT Leads - some agencies have developers or IT leads who may want to participate

    Inventory Agency Content
        Data on http://opendata.dc.gov
        Apps by agency employees
        New data to curate


Gather Your Toolbox
----------
Open data sites use Bootstrap to create custom elements. We recommend familiarizing yourself with <a href="https://www.w3schools.com/bootstrap/default.asp">Bootstrap</a> concepts. Edits to these code samples can be done in a standard text document editor such as Notepad in Windows, or in Microsoft Word. We however recommend using an html editor. Here are some easy to use, 

   <a href="https://www.jetbrains.com/pycharm/">Pycharm</a> <br>
   <a href="https://www.jetbrains.com/pycharm/">Another</a> <br>
   <a href="https://www.jetbrains.com/pycharm/">Another</a>

We use PNG files for images. Use these sizes for images,

    480 x 270 for Card Thumbnails
    102 x 102 for Medallions
    800 x 500 for Featured Image
    
    Row banner images are subjective, but larger is better. Sites are responsive so we've used 5300 x 1800 and 2100 x 400.
    
Esri shares content to help you get moving so take a look at these. Find more at http://resources.esri.com or http://www.esri.com/videos.

<a href="http://doc.arcgis.com/en/hub/sites/design-the-layout-of-your-open-data-site.htm">Designing Your Site</a><br>
<a href="http://www.esri.com/videos/watch?videoid=EBwNntOx0n0&channelid=UC_yE3TatdZKAXvt_TzGJ6mw&title=customizing-open-data">Customizing Open Data</a><br>
<a href="https://www.arcgis.com/home/item.html?id=f99fb5f7c91f4424b6ae1ca90678f58a">Create a Cascade Story Map</a><br>
<a href="https://www.arcgis.com/home/item.html?id=da029c7670514be1b5a10b60825cd8da">Create a Story Map Journal</a>


How to Use
----------
This collection of elements is designed for use with Esri's opendata site <a href="http://doc.arcgis.com/en/hub/sites/design-the-layout-of-your-open-data-site.htm">Layout Builder</a>. Elements are created within <a href="http://doc.arcgis.com/en/hub/sites/design-the-layout-of-your-open-data-site.htm#ESRI_SECTION1_943AEBF0EEA74B60BEE4AEF1EF8FFC58">Text Cards</A> and organized into <a href="http://doc.arcgis.com/en/hub/sites/design-the-layout-of-your-open-data-site.htm#ESRI_SECTION1_11FF2ACF716C4DB4BC9D9C7CEF7A5DC0">Rows.</a>

<li> Start by copying the code samples into a text, hmtl text editor or prefered staging area</li>

<li> Follow the stepped comments identified by the exclamation marks</li>

<li> Replace dummy image links with your image links
    
<li> Look for text that are in ALL CAPS and replace those with your text - including titles, paragraphs, web links, emails, etc.</li>
    
<li> Paste your final edited code sample into a <a href="http://doc.arcgis.com/en/hub/sites/design-the-layout-of-your-open-data-site.htm#ESRI_SECTION1_943AEBF0EEA74B60BEE4AEF1EF8FFC58">Text Card</a> in the open data <a href="http://doc.arcgis.com/en/hub/sites/design-the-layout-of-your-open-data-site.htm#ESRI_SECTION1_11FF2ACF716C4DB4BC9D9C7CEF7A5DC0">Row.</a></li>


Shared Values
----------

<li> Data visualized is data downloadable. If the data isn't available, let's not have our users "window shop" here.</li>
<li> Increase the use of existing content with links, narratives, agency sites, other open data sites, colleague web apps.</li>
<li> Create opportunities for engagement. Create citizen buy-in to your story – “how is, has been or will… my say be used?”</li>
<li> Author impactful narratives to story tell the data and illuminate the problem follow by resolution. It's okay to use pronouns.</li>
<li> No kitchen sink apps or pages with overloaded content. Rather, focused stories and supporting app.
<li> There are 900+ data layers in <a href="http://opendata.dc.gov">opendata.dc.gov</a>. Consider it as a source.</li>


Must Haves
----------
We are one DC government. Let's do our best to provide cohesive open data sites. Please make sure these are included in your site,

<li> All app cards need a data download link</li>
<li> The third column in footer element needs to remain, linking to important dc.gov resources</li>
<li> On homepage, the Tools for Building & Development row needs to remain however we can work with placement and coloring</li>



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

Tips for Usage
----------

Tip | and Why
---|---
Create a staging page| the layout builder does not have an undo feature, nor does it create back ups.
Think small| careful of overcrowding the home page, use pages for initiatives
Saving images| store images on a dc.gov content manager or other approved source.
Keep the comments| these will help future admins to reference.
Multi-testing| preview the site on multiple devices.
Ask for peer review| we are a team, and no one is as smart as all of us.

Contributing
------------
See [CONTRIBUTING.md](../master/CONTRIBUTING.md)

License
----------
See [LICENSE.md](../master/LICENSE.md)"# opendatadc-opendataSiteSamples" 
