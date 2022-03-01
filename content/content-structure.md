---
title: "[Draft] Module 2: Content Structure"
nav_title: "Content Structure"
permalink: /curricula/content-author-modules/content-structure/
ref: /curricula/content-author-modules/content-structure/
lang: en
github:
  repository: w3c/wai-curricula
  path: content/content-author-modules/content-structure.md
license: creative-commons
acknowledgements: /curricula/acknowledgements/
changelog: /curricula/changelog/
footer: >
  <p><strong>Date:</strong> Updated 9 February 2022. First published December 2019.</p>
  <p><strong>Editors:</strong> Daniel Montalvo and <a href="http://www.w3.org/People/shadi/">Shadi Abou-Zahra</a>. Contributors: <a href="https://www.w3.org/WAI/EO/EOWG-members">EOWG Participants</a>. ACKNOWLEDGEMENTS lists contributors and credits.</p>
  <p>Developed by the Education and Outreach Working Group (<a href="http://www.w3.org/WAI/EO/">EOWG</a>). Developed with support from the <a href="https://www.w3.org/WAI/about/projects/wai-guide/">WAI-Guide Project</a> funded by the European Commission (EC) under the Horizon 2020 program (Grant Agreement 822245).</p>
parent_in_h1:
  - ref: /curricula/content-author-modules/
    name: nav_title
  - ref: /curricula/
    name: "Curricula on Web Accessibility"
navigation:
  previous: /curricula/content-author-modules/clear-writing/
  next: /curricula/content-author-modules/images/
---

## Introduction
{:.no-display}

Courses based on this module should:

* demonstrate how people with disabilities rely on titles, headings, paragraphs, lists, and other structures to understand and process content
* explain accessibility requirements related to content structure

## Learning Outcomes for Module

Students should be able to:

* explain how people with disabilities rely on titles, headings, paragraphs, lists, and other structures to understand and process content
* write titles that describe the purpose of the page
* provide headings to help users identify the different content sections
* write clear and meaningful link text to communicate the link purpose
* ensure content structures are perceived visually and non-visually, including titles, headings, paragraphs, lists, quotes, and others
* employ tools that:
  * support the inclusion of titles, headings, lists, paragraphs, and other content structures
  * produce accessible markup for content structures
* identify related requirements for designers and developers to make content structures perceivable visually and non-visually

{% include excol.html type="all" %}

## Competencies

Skills required for this module:

{% include excol.html type="start" %}

### Students

{% include excol.html type="middle" %}

* [Foundation Prerequisites](/curricula/developer-modules/#foundation-prerequisites)
* Basic knowledge of:
  * Content editing

{% include excol.html type="end" %}

{% include excol.html type="start" %}

### Instructors

{% include excol.html type="middle" %}

* Applied expertise in teaching:
  * [WCAG 2 Success Criterion 1.3.1 Info and Relationships](https://www.w3.org/WAI/WCAG21/quickref/#info-and-relationships)
  * [WCAG 2 Success Criterion 2.4.6 Headings and Labels](https://www.w3.org/WAI/WCAG21/quickref/#headings-and-labels)
  * [WCAG 2 Success Criterion 2.4.10 Section Headings](https://www.w3.org/WAI/WCAG21/quickref/#section-headings)
* In-depth knowledge of
  * [Foundation Prerequisites](/curricula/developer-modules/#foundation-prerequisites)
  * Accessibility of authoring tools.

{% include excol.html type="end" %}

## Topics to Teach

Topics to achieve the learning outcomes:

{% include excol.html type="start" %}

### Topic: Titles

{% include excol.html type="middle" %}

[Intro paragraph TBD].

#### Learning Outcomes for Topic

Students should be able to:

* write unique, descriptive, and meaningful page titles
* provide information about the current step in the page title when the page is part of a multi-step process
* provide relevant and unique information first in page titles
* employ tools that produce appropriate markup for accessible page titles

#### Teaching Ideas for Topic

Optional ideas to teach the learning outcomes:

* Present examples of titles that describe the purpose of the page and then show examples of those that do not. Explain that page titles must describe the purpose of the page.
* Show examples of page titles for pages that are part of a multi-step process. Emphasize how information about the current step is presented in the page title, as well as in other parts of the page.
* Discuss different ways to organize information inside page titles. Explain that it is good practice to put information that is specific to the page first in the title. Emphasize that this supports efficiency of some assistive technology users as well as it helps everybody scan the titles.
* Introduce accessible authoring tools that produce accessible markup for page titles. Explain that some mobile user agents and assistive technologies may not display page titles. This is why some tools provide the information in the title also in the first heading of level one on the page. Explain that some tools may produce accessible content but may not be accessible themselves and vice versa.

#### Ideas to Assess Knowledge for Topic

Optional ideas to assess knowledge:

* Short Answer Questions &mdash; Give students non-descriptive titles and ask them to turn these titles into descriptive ones by tweaking their language. Assess how students write unique, meaningful, and descriptive page titles.
* Short Answer Questions &mdash; Ask students about good practices for structuring the information in page titles. Assess how students relate good practices for structuring information in page titles.
* Practical &mdash; Give students several pages that are part of a multi-step process. Ask them to provide information about the current step in each of the page titles. Assess how students provide information about the current step in each of the page titles.
* Practical &mdash; Students select an authoring tool that produces accessible markup for page titles and include page titles using the tool's user interface.

{% include excol.html type="end" %}

{% include excol.html type="start" %}

### Topic: Headings

{% include excol.html type="middle" %}

[Intro paragraph TBD].

#### Learning Outcomes for Topic

Students should be able to:

* provide headings and their corresponding rank levels to help users identify the different content sections and sub sections
* write descriptive and meaningful heading text depending on the heading purpose
* ensure headings are perceived both visually and non-visually
* employ tools that produce appropriate markup for headings and their corresponding rank levels

#### Teaching Ideas for Topic

Optional ideas to teach the learning outcomes:

* Discuss different ways of structuring pages and documents. Explain how these structures relate to headings in the content. Discuss headings and their corresponding rank levels. Explain that it is good practice to use heading level one for including the information of the page title. Some tools automate this process, some require the author to do it manually. 
* Explain some uses of heading text. These include entitling a given section, providing a headline for a piece of news, and summarizing the content the heading precedes.
* Show examples of how headings may appear visually. Explain that predefining the styles is a designer's and author tool vendor's responsibility. If the author changes these styles, they must ensure they are accessible.
* Introduce accessible authoring tools that produce accessible markup for headings. Explain that changing the font size alone does not produce an accessible heading. It is more efficient to rely on the tool's built-in functionality and then change the style later.

#### Ideas to Assess Knowledge for Topic

Optional ideas to assess knowledge:

* Practical &mdash; Give students a page and ask them to provide the headings. Assess how students relate the outline with headings and their corresponding rank levels.
* Short Answer Questions &mdash; Ask students about situations where they would use headings. Assess how students identify situations where headings can be used.
* Practical &mdash; Give students several page headings and ask them to use accessible styles. Assess how students employ accessible styles for headings.
* Practical &mdash; Have students include headings using a given authoring tool. Assess how students rely on the tool's built-in functionality to include headings.

{% include excol.html type="end" %}

{% include excol.html type="start" %}

### Topic: Links

{% include excol.html type="middle" %}

Intro paragraph [TBD].

#### Learning Outcomes for Topic

Students should be able to:

* write unique, descriptive, and meaningful link text
* provide relevant information about the link destination in the link text where possible, including:
  * the target resource title
  * if the link will open a new window
  * the file type and format (when linking to a file)
* ensure links and their different states are perceived both visually and non-visually
* employ tools that:
  * allow the inclusion of link text
  * produce appropriate markup for links

#### Teaching Ideas for Topic

Optional ideas to teach the learning outcomes:

* Discuss different uses of links, such as for linking to other pages, to a document, or to different parts of the content. Explain that these links must have clear and meaningful text so that people can understand their purpose as well as where they go to. For example, providing  information about the link destination, the document type and format and where the link will open.
* Show examples of some predefined styles for links and link states. Explain that redefining the styles is a designer's and author tool vendor's responsibility. If the author changes these styles, they must ensure they are accessible.
* Introduce accessible authoring tools that produce accessible markup for links and that support the inclusion of link text where appropriate. Explain that some tools may name these differently. For example, "link name", "link text", "link description", "screen tip", and others. Explain that it is good practice to always display as much information as possible on the screen's link text to maximize compatibility with user agents and assistive technologies.

#### Ideas to Assess Knowledge for Topic

Optional ideas to assess knowledge:

* Short Answer Questions &mdash; Ask students which types of information the link text could contain. Assess how students relate the information that the link text could contain, including link destination, document type and format, and where the link will open.
* Practical &mdash; Give students a link text that is not meaningful and ask them to make it meaningful by tweaking its language. Assess how students provide meaningful and descriptive link text.

{% include excol.html type="end" %}

{% include excol.html type="all" %}

## Ideas to Assess Knowledge for Module

Optional ideas to assess knowledge:

* Portfolio &mdash; Have students create a page with accessible content structures, including title, headings, links, paragraphs, and lists. Assess how students include accessible titles, headings, links, paragraphs, and lists in their pages.
* @@@

## Teaching Resources

Suggested resources to support your teaching:

* [Writing for Web Accessibility](https://www.w3.org/WAI/tips/writing/#use-headings-to-convey-meaning-and-structure) -- Introduces some basic considerations to help you get started writing web content that is more accessible to people with disabilities.
* [[How People with Disabilities Use the Web]](/people-use-web/) &mdash; Describes some of the barriers that people encounter using the Web; and introduces types of assistive technologies and adaptive strategies that some people use.
* [Understandable Content (Web Accessibility Perspective)](/perspective-videos/understandable/) &mdash; Is one of the Web accessibility perspectives videos that show accessibility features and how they impact people with disabilities.
* [WCAG](https://www.w3.org/WAI/standards-guidelines/wcag/) &mdash; Address accessibility of web content on desktops, laptops, tablets, and mobile devices.
