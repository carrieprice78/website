---
# Course title, summary, and position.
linktitle: LibGuides
summary: Best practices for librarians building LibGuides. 
weight: 37

# Page metadata.
title: LibGuides
draft: false  # Is this a draft? true/false
toc: true  # Show table of contents? true/false
type: docs  # Do not modify.
date: 2021-03-11

# Add menu entry to sidebar.
# - name: Declare this menu item as a parent with ID `name`.
# - weight: Position of link in menu.
menu:
  libguides:
    name: LibGuides
    weight: 1
---


I have built a lot of LibGuides over the years and I'm happy to share what worked best for me.

As the content and number of guides grew, I found it helpful to have at least three internal guides, as defined below. If working at an institution that has a lot of guides, it might be helpful to have these types of internal guides for each group, college, or discipline. 

## Best Practices Guide (Internal)

Use your best practices guide internally. It should provide guidance to other LibGuide content creators. I included sections for:

### Accessibility


#### Links

* Avoid using the words such as "link", "here", and "for more information..." in your linked text.
* Screen readers will recognize the href HTML tag as a link.
* Linked text should make sense out of context. It should describe the link.

#### Copy

Use heading element tags (h3, h4, h5) instead of text decoration (bold, underline, italic) so that screen readers can identify headings and sections. h1 and h2 are already defined in LibGuides.

#### Images

Include short descriptive text as alt text (alternative text) for images so that screen readers can describe the image to the viewer with the use of a screen reader.

#### What is an Accessible PDF?

An accessible PDF:

* has readable text
* is not an image
* has tags to indicate a heading structure
* has alternate text for images
* has a set reading order so that it can be read by a screen reader
* has a set language

Make sure that your uploaded accessible documents have alternative text and a thumbnail image.

##### Using Adobe Acrobat Pro to Ensure Accessibility

Use Adobe Acrobat Pro to create accessible PDFs.

Go to Tools  >  Action Wizard, and follow the steps to prepare your PDF for accessibility.

See more on the [Adobe Acrobat Pro User Guide](https://helpx.adobe.com/acrobat/using/create-verify-pdf-accessibility.html).

#### What is Alternative Text?
Alternative text helps screen readers recognize and describe images used on websites. An image without alternative text cannot be described in context.

* Use alternative text when including an image in your guide.
* Alternative text is read by screen readers in place of images.
* Enter accurate text that avoids terminology such as "image of..." or "link to...".
* See [WebAIM's section on alternative text](https://webaim.org/techniques/alttext/).


### Color

Make a list of colors that are allowed on the guides and note their Hex and RGB values. I used a table for this and noted which elements which colors should correspond to, such as box headers, footer, links, complementary colors.

Link to your institutional brand pages, which should reflect your choices of color.

### Editorial Guidelines

Here is where you can standardize terminology, grammar, and punctuation, fonts, and other materials such as PowerPoints and presentations for the whole library. I used tables inside a tabbed box for this purpose.

You can also specify how users should create friendly URLs or slugs for their guide pages. See [Compound Domain names](https://www.nngroup.com/articles/compound-domain-names/) from the Nielsen Norman Group.

Link to your institutional brand pages, which should reflect your choices of fonts.
### Responsive Design

LibGuides has Bootstrap built in to the platform. Bootstrap makes it easy to make content appear beautifully across a variety of devices. CSS Grid can also be used within a box.

Do not use tables for formatting. Tables should only be used for tabular content. LibGuides contains Bootstrap pre-formatted tables that you can select for look and feel.

You may wish to create a CSS Grid inside a box for a more customized look than Bootstrap. Two CSS Grids are also available in the Reusable Content tab. Make a copy and edit the text if you'd like to use them.

Embed responsive images by setting width to 100% with the height left blank.

Also note how you should embed resopnsive media, usually with a div class. See [Bootstrap's Documentation on Responsive Embeds](https://getbootstrap.com/docs/4.4/utilities/embed/). 


### Site Documentation
Upload your current documents to a site documentation page on the best practices guide, and keep it updated.

* customized JS/CSS
* header code
* footer code
* subjects and tags metadata
* logos
* embedded icon collections
* favicon

### Guide Maintenance

#### Making a New Guide

Ensure the need for a new guide by first checking manager/LibGuides administrators. To create a new guide, choose Create Guide in the LibGuides system. The default navigation is Side Nav.

##### Adding Assets, Links, and Databases

Before you add a new asset (link) or database to the system, check to make sure that one doesn't already exist. You can do this from Content > Assets or Content > A-Z Database List on the LibGuides toolbar.

* Links should be added to Assets
* Only databases should be added to Databases


#### Retiring Your Guide

If a guide is no longer relevant, consider setting its status to Private or Unpublished.

You are free to delete your own content and your own guides when appropriate if it is not being mapped to other guides.

#### Maintaining Your Guide

Ensure that your guide's links are still active. Find the Link Checker under Tools in the LibGuides toolbar. The schedule for link checking is January and July of every year.

#### Keep Your Profile Up to Date

Keep your profile up to date. You can do this by navigating to LibApps > Profile in the toolbar.

Profiles should include at a minimum:

* Photo
* Email Address


### Include a Help Area

Make sure that LibGuide builders know who to contact for help, and where they can find additional training.

* [LibGuides Community Sites](https://community.libguides.com/)
* [Springshare Help Center](http://support.springshare.com/libguides)
* [Springshare Training](http://support.springshare.com/libguides/training)

It may also be helpful to link to tools that will help budding web developers try out some new techniques, like: 

* [Bootstrap](https://getbootstrap.com/)
* [Bootstrap Documentation](https://getbootstrap.com/docs/4.3/getting-started/introduction/)
* [CSS Grid on w3 Schools](https://www.w3schools.com/css/css_grid.asp)
* [CSS Zen Garden](http://www.csszengarden.com/)
* [Font Awesome Integration](https://fontawesome.com/v3.2.1/examples/)
* [JS Fiddle](https://jsfiddle.net/)
* [TryIt Editor from w3 Schools](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_basic)







## Storage and Reusable Elements Guide (Internal)

I used the storage guide to keep reusable boxes that appeared frequently on many guides. I also used a storage guide to display resuable elements like headers, boxes, and other customized CSS or HTML elements. A user could see what it looked like before using the code in their own site. Content creators could also simply reuse a box that had the correct information, and the boxes could be updated from one place.

You might also consider adding a sandbox page here, so that content creators can try out different designs before going live.

## Reusable Pages Guide (Internal)

As the content grew, I realized that it was better to have a reusable pages guide as well. Reusable pages are for things that require more than just a few boxes, like a process, a course, a lesson plan, or a database tipsheet. Users could map to the page, and the pages could be updated from one place.