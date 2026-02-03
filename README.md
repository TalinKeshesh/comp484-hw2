# comp484-hw2
https://talinkeshesh.github.io/comp484-hw2/



1.	Determine a structuring strategy.
             a.	Applies to: structure.htm
             b.	Open the structure.htm file and explore the page structure and ARIA roles. Write out the document outline, and how structural tags like aside, article, nav, and section are being used.
             c.	Examine how semantic tags like the header, footer, and main elements are used.
             d. review slide #7 of the lecture slides.Create a diagram of how the tags would look like in the HW website.Take a screenshot of the diagram and add it to the images folder.
             e. review slide #10 of the lecture slides. Use the website provided or other alternative options to produce a document outline. Take a screenshot of the outline and add it to the images folder.



1.
    b.
<header role="banner">
Holds the site heading (“Comp 484”), the page title (“Structuring Pages”), and the primary navigation.

<nav role="navigation" aria-label="Primary">
Contains the site-wide menu (a list of links) used to move between the six pages of the site.

<main role="main">
Wraps the main content of the page (everything unique to this page).

<article>
Wraps the full instructional content as one main “article” inside the main area.

<footer role="contentinfo">
Contains footer information (the CSUN address/link) at the bottom of the page.

<aside role="complementary"> (appears inside one section)
Used as a callout box (“W3C Warning”) that supports the surrounding content, but is not required for the main flow of reading.

Document outline:

The page’s headings create this outline:
H1: Comp 484
H2: Structuring Pages
H3: Conveying meaning through structure
H3: Sectioning elements
H3: Document outlines
H4: W3C Warning (inside the aside callout)
H3: WAI-ARIA Roles

How structural tags are being used:
nav: used for the primary site navigation menu.
article: used to group the page’s main instructional content as a single, self-contained unit.
section: used to break the article into major topic areas. Each section is introduced by an h3 heading, so each section becomes a major part of the page outline.
aside: used for related content (the “W3C Warning” callout), which belongs with the “Document outlines” section but is not part of the main description.




    c.
<header role="banner">: Top of the page; contains the site title (H1), page title (H2), and the main navigation (<nav>).
<main role="main">: Holds the page’s primary content.
<footer role="contentinfo">: Bottom of the page; contains footer/site info (CSUN link/address).
