---
title: "[Draft] 2: Structure in Content Author Modules | Curricula"
title_html: "Module 2: Structure"
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
  previous: /curricula/content-author-modules/clear-content/
  next: /curricula/content-author-modules/forms/
---

## Introduction
{:.no-display}

Courses based on this module should:

* demonstrate how people with disabilities rely on headings, paragraphs, lists, and other structures to orient themselves, as well as to understand, navigate, and process content
* explain accessibility requirements related to content structure

## Learning Outcomes for Module

Students should be able to:

* explain how people with disabilities rely on headings, paragraphs, lists, and other structures to orient themselves, as well as to understand, navigate, and process content
* provide meaningful and consistent headings to help users identify and navigate content sections
* group content using paragraphs, lists, and other structures
* collaborate with designers and developers to:
  * include methods to move back and forth through long pieces of content, including tables of contents and "back to top" links
  * ensure meaningful content sequences for different screen sizes, user configurations, and assistive technologies in use
* identify requirements for authoring tools to produce appropriate markup for headings, paragraphs, lists, and other content structures
* identify related requirements for developers and designers to ensure:
  * visual and non-visual perception of content structures, including headings, paragraphs, lists, quotes, and others
  * adequate content grouping and spacing to communicate semantic structures visually

{% include excol.html type="all" %}

## Competencies

Skills required for this module:

{% include excol.html type="start" %}

### Students

{% include excol.html type="middle" %}

* [Foundation Prerequisites](/curricula/developer-modules/#foundation-prerequisites)
* Basic knowledge of:
  * Writing
  * Copy-editing
  * Proofreading

{% include excol.html type="end" %}

{% include excol.html type="start" %}

### Instructors

{% include excol.html type="middle" %}

* Applied expertise in teaching:
  * [WCAG 2 Success Criterion 1.3.1 Info and Relationships](https://www.w3.org/WAI/WCAG21/quickref/#info-and-relationships)
  * [WCAG 2 Success Criterion 1.3.2 Meaningful Sequence](https://www.w3.org/WAI/WCAG21/quickref/#meaningful-sequence)
  * [WCAG 2 Success Criterion 2.4.1 Bypass Blocks](https://www.w3.org/WAI/WCAG21/quickref/#bypass-blocks)
  * [WCAG 2 Success Criterion 2.4.6 Headings and Labels](https://www.w3.org/WAI/WCAG21/quickref/#headings-and-labels)
  * [WCAG 2 Success Criterion 2.4.10 Section Headings](https://www.w3.org/WAI/WCAG21/quickref/#section-headings)
* In-depth knowledge of
  * [Foundation Prerequisites](/curricula/developer-modules/#foundation-prerequisites)
  * [Module 1: Clear Content](/curricula/content-author-modules/clear-content/)
  * [Accessible authoring tools](https://www.w3.org/WAI/standards-guidelines/atag/)

{% include excol.html type="end" %}

## Topics to Teach

Topics to achieve the learning outcomes:

{% include excol.html type="start" %}

### Topic: Headings

{% include excol.html type="middle" %}

Headings and their corresponding rank levels communicate the structure of web pages and documents. This helps people with disabilities navigate and identify the different content sections. Explain different purposes of headings and how to include them.

When content authors change the visual appearance of headings, they must ensure headings remain accessible visually and non-visually.

#### Learning Outcomes for Topic

Students should be able to:

* explain how proper heading hierarchy helps users identify and navigate the different content sections
* provide consistent headings and their corresponding rank levels to help users identify and navigate the different content sections
* write descriptive and meaningful heading text depending on the heading purpose
* describe the accessibility considerations when changing the default visual appearance of headings, including:
  * potential inaccessibility of the selected custom visual appearance
  * mismatch between the visual appearance of the heading and the generated markup
* identify requirements for authoring tools to produce appropriate markup for headings and their corresponding rank levels
* identify related requirements for designers and developers to ensure visual and non-visual perception of headings

#### Teaching Ideas for Topic

Optional ideas to teach the learning outcomes:

* Demonstrate the use of voice commands, keystrokes, and gestures provided by assistive technologies and adaptive strategies to navigate web pages through headings. Explore advanced functionality that some tools provide, such as presenting the heading hierarchy in a list where users can select the heading they are interested in. Examples of how people with disabilities interact with the Web are provided in [How People with Disabilities Use the Web](https://www.w3.org/WAI/people-use-web/).
* Discuss the use of headings and their corresponding rank levels for identifying content sections. Explain that it is best practice to use heading level one for including the information of the page title. Some tools automate this process, some require the author to do it manually. 
* Explain other uses of heading text. These include providing a headline for a piece of news and summarizing the content the heading precedes.
* Show examples of what headings can look like visually. Explain that predefining the styles is a designer's and authoring tool vendor's responsibility. When content authors change these styles, they must ensure visual and non-visual accessibility of headings themselves.
* Introduce accessible authoring tools that produce appropriate markup for headings. Explain that changing the font size alone does not produce an accessible heading. It is more efficient to rely on the tool's built-in functionality and then change the style later.

#### Ideas to Assess Knowledge for Topic

Optional ideas to assess knowledge:

* Short Answer Questions &mdash; Ask students about situations where they would use headings. Assess how students identify situations where headings can be used.
* Practical &mdash; Have students include headings and their corresponding rank level in a page using an authoring tool of their choice. Assess how students rely on the tool's built-in functionality to include headings and their corresponding rank level.
* Practical &mdash; Ask students to change the visual appearance of the headings on a given website ensuring that they remain accessible visually and non-visually. Assess how students ensure visual and non-visual accessibility of headings when changing the headings style.

{% include excol.html type="end" %}

{% include excol.html type="start" %}

### Topic: Paragraphs and Lists

{% include excol.html type="middle" %}

Paragraphs and lists group related content. This helps people with disabilities better read and understand content. Explain different types of lists and how to include them.

When content authors change the visual appearance of paragraphs and lists, they must ensure paragraphs and lists remain accessible visually and non-visually.

#### Learning Outcomes for Topic

Students should be able to:

* explain how people with disabilities rely on paragraphs and lists to understand and process related content
* group related content using:
  * paragraph structures to group thematic units
  * unordered lists when the item numbering is not relevant
  * ordered lists when the item numbering is relevant
  * description lists for terms and their definitions
* identify requirements for authoring tools to produce appropriate markup for paragraphs, lists, and other content structures

#### Teaching Ideas for Topic

Optional ideas to teach the learning outcomes:

* Demonstrate the use of voice commands, keystrokes, and gestures provided by assistive technologies and adaptive strategies to navigate web pages through paragraphs and lists. Explore advanced functionality that some tools provide, such as presenting all lists in a list where users can select the list they are interested in. Examples of how people with disabilities interact with the Web are provided in [How People with Disabilities Use the Web](https://www.w3.org/WAI/people-use-web/).
* Explain different uses of paragraphs to group thematic units.
* Explain uses of different types of lists. Ordered lists (where numbering matters), unordered lists (where numbering does not matter), and description lists (for terms and their definitions).
* Reflect with students on how content authors can produce accessible paragraphs and lists. Explain that some authoring tools  natively support the creation of accessible paragraphs, ordered lists, and unordered lists. Emphasize that description lists may require developers to code them.

#### Ideas to Assess Knowledge for Topic

Optional ideas to assess knowledge:

* Short Answer Questions &mdash; Ask students about the purpose of paragraphs, unordered lists, and ordered lists. Assess how students describe the purpose of paragraphs, unordered lists, and ordered lists.
* Practical &mdash; Give students a piece of content and ask them to group related content using paragraphs and lists. Assess how students use paragraphs and lists to group related content.

{% include excol.html type="end" %}

{% include excol.html type="start" %}

### Topic: Orientation and Navigation

{% include excol.html type="middle" %}

Introduce navigation and orientation methods that help people with disabilities orient themselves and navigate content. These include meaningful content sequences, tables of contents, footnotes, and methods for users to move back and forth through long passages of content.

Explain that creating accessible navigation and orientation methods requires collaboration between different team members, including designers and developers. Content authors provide the content. Designers specify the visual appearance and interaction. Developers implement the methods.

#### Learning Outcomes for Topic

Students should be able to:

* explain how people with disabilities rely on meaningful content sequences, tables of contents, and other orientation and navigation methods to orient themselves and navigate content
* utilize tables of contents to:
  * provide a summary of the overall content structure
  * help users navigate to parts of the content
* ensure availability of methods for users to move back and forth through long passages of content, for example using:
  * tables of contents
  * links to get back to the top of the content and to the top of specific sections
  * methods to move from a footnote marker to the footnote content and from the footnote content back to the footnote marker
* identify related requirements for:
  * designers and developers to support visual and non-visual perception and operation of orientation and navigation methods
  * authoring tools to support accessible orientation and navigation methods

#### Teaching Ideas for Topic

Optional ideas to teach the learning outcomes:

* Demonstrate the use of assistive technologies to navigate through long passages of text. Explain that several groups of users rely on orientation and navigation methods to understand where they are in the content and to move back and forth through different content sections.
* Show examples of tables of contents. Explain that they provide a summary of the overall structure of the whole piece of content. They also enable users to get to the specific sections they are interested in.
* Discuss the use of methods to get back to the table of contents, for example "Back to top" links at the end of each section. Explain that these help keyboard users get back to the table of contents when they are finished reading a specific section. Otherwise, they would have to tab back through the whole document, which creates a poorer user experience.
* Demonstrate assistive technology and keyboard interaction with document footnotes. Explain that keyboard users need methods to move from the footnote marker to the footnote content and to move back from the footnote content to the footnote marker.
* Refer back to Foundation Module 5: Getting Started with Accessibility, [Topic Roles and Responsibilities](/foundation-modules/getting-started-with-accessibility/#topic-roles-and-responsibilities). Explain that, when authoring tools do not support accessible orientation and navigation methods, content authors need to collaborate with other team members, including designers and developers, to include them. Designers specify the appearance and interaction of the methods. Developers implement these methods.

#### Ideas to Assess Knowledge for Topic

Optional ideas to assess knowledge:

* Short Answer Questions &mdash; Ask students about different methods to help users orient themselves and navigate long passages of text. Assess how students recall methods to help users orient themselves and navigate long passages of text, including tables of contents and "Back to top" links.
* Practical &mdash; Ask students to provide the table of contents for a resource of a given website. Assess how students provide the table of contents for an article.
* Practical &mdash; Ask students to use an authoring tool of their choice to include accessible footnotes. Assess how students include accessible footnotes.
* Practical &mdash; Ask students to collaborate with other team members to provide accessible navigation and orientation methods. Assess how students collaborate with other team members to provide accessible orientation and navigation methods.

{% include excol.html type="end" %}

{% include excol.html type="all" %}

## Ideas to Assess Knowledge for Module

Optional ideas to assess knowledge:

* Short Answer Questions &mdash; Ask students about methods that people with disabilities use to navigate content based on existing headings, paragraphs, and lists. Assess how students recall methods that people with disabilities use to navigate content based on existing headings, paragraphs, and lists.
* Portfolio &mdash; Have students create a page with accessible content structures, including headings, paragraphs, lists, and others. Assess how students include accessible headings, paragraphs, lists, and others in their pages.

## Teaching Resources

Suggested resources to support your teaching:

* [Writing for Web Accessibility](https://www.w3.org/WAI/tips/writing/) &mdash; Introduces some basic considerations to help you get started writing web content that is more accessible to people with disabilities.
* [Page Structure (WAI Web Accessibility Tutorials)](https://www.w3.org/WAI/tutorials/page-structure) &mdash; Shows how to provide page structures that are accessible to people with disabilities.
* [[How People with Disabilities Use the Web]](https://www.w3.org/WAI/people-use-web/) &mdash; Describes some of the barriers that people encounter using the Web; and introduces types of assistive technologies and adaptive strategies that some people use.
* [Clear Layout and Design (Web Accessibility Perspectives)](https://www.w3.org/WAI/perspective-videos/layout/) &mdash; Is one of the Web accessibility perspectives videos that show accessibility features and how they impact people with disabilities.
* [Understandable Content (Web Accessibility Perspective)](https://www.w3.org/WAI/perspective-videos/understandable/) &mdash; Is one of the Web accessibility perspectives videos that show accessibility features and how they impact people with disabilities.
* [WCAG](https://www.w3.org/WAI/standards-guidelines/wcag/) &mdash; Address accessibility of web content on desktops, laptops, tablets, and mobile devices.
