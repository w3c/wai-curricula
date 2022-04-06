---
title: "[Draft] Module 2: Structure"
nav_title: "Structure"
permalink: /curricula/content-author-modules/structure/
ref: /curricula/content-author-modules/structure/
lang: en
github:
  repository: w3c/wai-curricula
  path: content/content-author-modules/structure.md
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

* demonstrate how people with disabilities rely on headings, paragraphs, lists, and other structures to orient themselves, as well as to understand, navigate, and process content
* explain accessibility requirements related to content structure

## Learning Outcomes for Module

Students should be able to:

* explain how people with disabilities rely on headings, paragraphs, lists, and other structures to orient themselves, as well as to understand, navigate and process content
* provide headings to help users identify and navigate the different content sections
* group content using paragraphs, lists, and other structures
* provide tables of contents to give an overall summary of the content structure
* collaborate with designers and developers to include methods to move back and forth through long pieces of content, including "back to top" links
* employ accessible authoring tools that:
  * support the inclusion of headings, lists, paragraphs, and other content structures
  * produce appropriate markup for headings, lists, paragraphs, and other content structures
* identify related requirements for developers and designers to ensure visual and non-visual perception of content structures , including headings, paragraphs, lists, quotes, and others

{% include excol.html type="all" %}

## Competencies

Skills required for this module:

{% include excol.html type="start" %}

### Students

{% include excol.html type="middle" %}

* [Foundation Prerequisites](/curricula/developer-modules/#foundation-prerequisites)
* Basic knowledge of:
  * Content creation
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
  * [Module 1: Clear Content](/curricula/content-author-modules/clear-content/)
  * Authoring tools accessibility

{% include excol.html type="end" %}

## Topics to Teach

Topics to achieve the learning outcomes:

{% include excol.html type="start" %}

### Topic: Headings

{% include excol.html type="middle" %}

[Intro paragraph TBD].

#### Learning Outcomes for Topic

Students should be able to:

* provide headings and their corresponding rank levels to help users identify and navigate the different content sections
* write descriptive and meaningful heading text depending on the heading purpose
* employ accessible authoring tools that produce appropriate markup for headings and their corresponding rank levels
* identify related requirements for designers and developers to ensure visual and non-visual perception of headings

#### Teaching Ideas for Topic

Optional ideas to teach the learning outcomes:

* Discuss different ways of structuring pages and documents. Explain how these structures relate to headings in the content. Discuss headings and their corresponding rank levels. Explain that it is good practice to use heading level one for including the information of the page title. Some tools automate this process, some require the author to do it manually. 
* Explain some uses of heading text. These include entitling a given section, providing a headline for a piece of news, and summarizing the content the heading precedes.
* Show examples of how headings may appear visually. Explain that predefining the styles is a designer's and author tool vendor's responsibility. If the author changes these styles, they must ensure they are accessible.
* Introduce accessible authoring tools that produce appropriate markup for headings. Explain that changing the font size alone does not produce an accessible heading. It is more efficient to rely on the tool's built-in functionality and then change the style later. Explain that some tools may produce accessible content but may not be accessible themselves and vice versa.

#### Ideas to Assess Knowledge for Topic

Optional ideas to assess knowledge:

* Short Answer Questions &mdash; Ask students about situations where they would use headings. Assess how students identify situations where headings can be used.
* Practical &mdash; Have students include headings using a given authoring tool. Assess how students rely on the tool's built-in functionality to include headings.

{% include excol.html type="end" %}

{% include excol.html type="start" %}

### Topic: Paragraphs and Lists

{% include excol.html type="middle" %}

[Intro paragraph TBD.]

#### Learning Outcomes for Topic

Students should be able to:

* explain how people with disabilities rely on paragraphs and lists to understand and process content grouping
* group related content using:
  * paragraph structures to group thematic units
  * unordered lists when the item numbering is not relevant
  * ordered lists when the item numbering is relevant

#### Teaching Ideas for Topic

Optional ideas to teach the learning outcomes:

* Explain different uses of paragraphs to group thematic units. Explain that providing the paragraphs is an authors responsibility, defining how these paragraphs look like is a designers responsibility, and implementing markup for these paragraphs is a developers responsibility.
* Explain uses of ordered lists (where numbering does not matter) and unordered lists (where numbering matters). Explain that providing these lists is an authors responsibility, defining how these lists look like is a designers responsibility, and implementing markup for these lists is a developers responsibility.
* Demonstrate approaches to group related content for easier processing. For example, appropriate spacing between different content sections and use of paragraphs and lists to group related content.

#### Ideas to Assess Knowledge for Topic

Optional ideas to assess knowledge:

* Short Answer Questions &mdash; Ask students about different uses of paragraphs and lists. Assess how students recall different uses of paragraphs and lists.
* Practical &mdash; Give students a set of related items where numbering matters and a set of related items where numbering does not matter. Ask them to provide the correct type of list for each.. Assess how students use ordered and unordered lists.

{% include excol.html type="end" %}

{% include excol.html type="start" %}

### Topic: Orientation and Navigation

{% include excol.html type="middle" %}

[Intro paragraph TBD]

#### Learning Outcomes for Topic

Students should be able to:

* explain how people with disabilities rely on meaningful content sequence, tables of contents, and orientation methods to navigate content
* provide tables of contents to:
  * give a summary of the overall content structure
  * help users navigate to parts of the content
* ensure availability of methods for users to move back and forth through long passages of content, for example using:
  * tables of contents
  * links to get back to the top of the content and to the top of specific sections
  * methods to move from a footnote to its content and from its content back to the footnote
* identify related requirements for designers and developers to support visual and non-visual perception and operation of orientation and navigation methods

#### Teaching Ideas for Topic

Optional ideas to teach the learning outcomes:

* Demonstrate use of assistive technologies to navigate through long passages of text. Explain that several groups of users rely on orientation and navigation methods to understand where they are in the content and to move back and forth through different content sections.
* Show examples of tables of contents. Explain that they provide a summary of the overall structure of the whole piece of content. They also enable users to get to the specific sections they are interested in.
* Discuss the use of methods to get back to the table of contents, for example “Back to top” links at the end of each section. Explain that these help keyboard users get back to the table of contents when they are finished reading a specific section. Otherwise they would have to tab back through the whole document, which creates a poorer user experience.
* Show examples of document footnotes. Explain that keyboard users need methods to move from the footnote to its contents and to move back from the footnote contents to the text. Explain that providing the footnote and its contents is an author’s responsibility, defining the appearance and operation of the footnote is a designer’s responsibility, and implementing the footnote is a developer’s responsibility.

#### Ideas to Assess Knowledge for Topic

Optional ideas to assess knowledge:

* Short Answer Questions &mdash; Ask students about different methods to help users orient and navigate long passages of text. Assess how students recall methods to help users orient and navigate long passages of text, including tables of contents and “Back to top” links.
* Practical &mdash; Ask students to provide the table of contents for a document. Assess how students provide the table of contents for a document.
* Practical &mdash; Ask students to collaborate with other team members to provide accessible footnotes. Assess how students collaborate with other team members to include methods for users to move back and forth through the footnotes and its contents.

{% include excol.html type="end" %}

{% include excol.html type="all" %}

## Ideas to Assess Knowledge for Module

Optional ideas to assess knowledge:

* Short Answer Questions &mdash; Ask students about the structural units that exist and their purpose. Assess how students recall the structural units that exist and how they explain their purpose.
* Portfolio &mdash; Have students create a page with accessible content structures, including headings, paragraphs, and lists. Assess how students include accessible headings, paragraphs, and lists in their pages.

## Teaching Resources

Suggested resources to support your teaching:

* [Writing for Web Accessibility](https://www.w3.org/WAI/tips/writing/) -- Introduces some basic considerations to help you get started writing web content that is more accessible to people with disabilities.
* [[How People with Disabilities Use the Web]](/people-use-web/) &mdash; Describes some of the barriers that people encounter using the Web; and introduces types of assistive technologies and adaptive strategies that some people use.
* [Clear Layout and Design (Web Accessibility Perspectives)](https://www.w3.org/WAI/perspective-videos/layout/) &mdash; Is one of the Web accessibility perspectives videos that show accessibility features and how they impact people with disabilities.
* [Understandable Content (Web Accessibility Perspective)](/perspective-videos/understandable/) &mdash; Is one of the Web accessibility perspectives videos that show accessibility features and how they impact people with disabilities.
* [WCAG](https://www.w3.org/WAI/standards-guidelines/wcag/) &mdash; Address accessibility of web content on desktops, laptops, tablets, and mobile devices.
