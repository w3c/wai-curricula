---
title: "[Draft] Module 2: Information Design [WIP]"
nav_title: "Information Design"
permalink: /curricula/designer-modules/information-design/
ref: /curricula/designer-modules/information-design/
lang: en
github:
  repository: w3c/wai-curricula
  path: content/designer/information-design.md
license: creative-commons
acknowledgements: /curricula/acknowledgements/
changelog: /curricula/changelog/
footer: >
  <p><strong>Date:</strong> Updated @@ Month 2021. First published December 2019. CHANGELOG</p>
  <p><strong>Editors:</strong> Daniel Montalvo and <a href="http://www.w3.org/People/shadi/">Shadi Abou-Zahra</a>. Contributors: <a href="https://www.w3.org/WAI/EO/EOWG-members">EOWG Participants</a>. ACKNOWLEDGEMENTS lists contributors and credits.</p>
  <p>Developed by the Education and Outreach Working Group (<a href="http://www.w3.org/WAI/EO/">EOWG</a>). Developed with support from the <a href="https://www.w3.org/WAI/about/projects/wai-guide/">WAI-Guide Project</a> funded by the European Commission (EC) under the Horizon 2020 program (Grant Agreement 822245).</p>
parent_in_h1:
  - ref: /curricula/designer-modules/
    name: nav_title
  - ref: /curricula/
    name: "Curricula on Web Accessibility"
navigation:
  previous: /curricula/designer-modules/visual-design/
  next: /curricula/designer-modules/navigation-design/
---

## Introduction
{:.no-display}

Courses based on this module should:

* demonstrate how people with disabilities use titles, headings, labels, instructions, imagery, and others to obtain and process information
* describe several approaches to communicate the structure, relations, and purpose  information

## Learning Outcomes for Module

Students should be able to:

* explain how people with disabilities use titles, headings, labels, instructions, imagery, and others to obtain and process information
* describe approaches to break down different types of content into smaller and more manageable pieces, for example using:
  * headings, pages, and chapter markers
  * lists, simpler tables, and plain text to convey information presented in complex tables
  * groups of form controls that share a common purpose
* describe the use of visual and non-visual cues to make information in multi-step processes more understandable
* describe how to communicate the structure of multi-page articles or processes visually and non-visually
* describe how to provide information about the total number of items and about the current item in a multi-step process visually and non-visually
* evaluate the use of different mechanisms to convey the information, including text, tables, grouping, and graphical representations depending on user needs
* identify related requirements for developers to programmatically associate headings, table header cells and data cells, as well as form labels and instructions, to their corresponding control

{% include excol.html type="all" %}

## Competencies

Skills required for this module:

{% include excol.html type="start" %}

### Students

{% include excol.html type="middle" %}

* [Foundation Prerequisites](/curricula/designer-modules#foundation-prerequisites)
* [Designer Module 1: Visual Design](/curricula/designer-modules/visual-design/)
* Basic knowledge of:
  * Visual Design
  * Prototyping
  * Responsive Design
  * Information Architecture

{% include excol.html type="end" %}

{% include excol.html type="start" %}

### Instructors

{% include excol.html type="middle" %}

* Applied expertise in teaching:
  * [WCAG Success Criterion 1.3.1 Info and Relationships](https://www.w3.org/WAI/WCAG21/quickref/#info-and-relationships)
  * [WCAG Success Criterion 2.1.1 Keyboard](https://www.w3.org/WAI/WCAG21/quickref/#keyboard)
  * [WCAG Success Criterion 3.1.1 Unusual Words](https://www.w3.org/WAI/WCAG21/quickref/#unusual-words)
  * [WCAG Success Criterion 3.1.4 Abbreviations](https://www.w3.org/WAI/WCAG21/quickref/#abbreviations)
  * [WCAG Success Criterion 3.2.1 On Focus](https://www.w3.org/WAI/WCAG21/quickref/#on-focus)
  * [WCAG Success Criterion 3.2.2 ON Input](https://www.w3.org/WAI/WCAG21/quickref/#on-input)
  * [WCAG Success Criterion 3.3.2 Labels or Instructions](https://www.w3.org/WAI/WCAG21/quickref/#labels-or-instructions)
* In-depth knowledge of:
  * [Foundation Prerequisites](/curricula/designer-modules#foundation-prerequisites)
  * [Designer Module 1: Visual Design](/curricula/designer-modules/visual-design/)
  * Visual Design
  * Prototyping
  * Responsive Design
  * Information Architecture

{% include excol.html type="end" %}

## Topics to Teach

Topics to achieve the learning outcomes:

{% include excol.html type="start" %}

### Topic: Text

{% include excol.html type="middle" %}

Discuss ways to split large amounts of text into smaller pieces. For example, using headings and their corresponding rank levels, pages to split the contents into logical units, and chapter markers to indicate chapters in digital publications.

#### Learning Outcomes for Topic

Students should be able to:

* design textual content as manageable passages of text, for example by splitting larger blocks of text into smaller and more manageable pieces using:
  * headings (with their corresponding rank levels)
  * sidebars and other page regions
  * pages
  * chapter markers (in digital publications)
* create graphical representations that accompany the text, to make the information easier to understand; for example a diagram representation of the process described in the text” 
* evaluate the use of professional terms, idioms, and jargon, and select definitions for such terms to support readability
* evaluate the use of acronyms and abbreviations, and select expanded forms for such acronyms and abbreviations to support readability
* identify related requirements for developers to make language programmatically determined
* identify related requirements for content authors to provide clear language and easy-to-read texts whenever possible

#### Teaching Ideas for Topic
 
Optional ideas to teach the learning outcomes:

* Show examples of online articles and forms. Discuss how these are divided into manageable pieces so that they are easier to understand and to navigate. For example, by using headings and their corresponding rank levels to indicate the different chapters, sections, and subsections of content.
* Show examples of diagrams and illustrations that can complement the information presented in text.  For example, visual instructions that supplement the textual information of a user manual. Explain that they help users with reading disabilities understand difficult pieces of text. For reference on how to provide visual illustrations, pictures, and symbols to help explain ideas, events, and processes, see technique [G103: Providing visual illustrations, pictures, and symbols to help explain ideas, events, and processes](https://www.w3.org/WAI/WCAG21/Techniques/general/G103).
* Show examples of words that may be difficult to understand or that are used in a restricted way. Explain that people who are not familiar with such words need definitions to understand their meaning.  Explain that defining the mechanisms to provide such definitions is a designers' responsibility, whereas providing the definitions is a responsibility shared with the content author.
* Show examples of abbreviations,  such as short forms of words and acronyms. Explain that people who are not familiar with the abbreviations need an explanation or an expansion of that abbreviation to understand their meaning. Explain that defining the mechanisms to provide such explanations or expansions is a designers' responsibility, whereas providing the explanations or expansions is a responsibility shared with the content author.

#### Ideas to Assess Knowledge for Topic

Optional ideas to assess knowledge:

* Practical &mdash; Present students with an eBook and ask them to define how it should be split into smaller and more manageable pieces so that it can be easier to navigate and understand. Assess how students use headings and rank levels, pages, and chapter markers to split large amounts of text into smaller and more manageable pieces.
f* Practical &mdash; Give students a complex piece of text and ask them to complement it with diagrams and illustrations. Assess how students provide mechanisms to complement processes and instructions presented in text.
* Practical &mdash; Present students with unusual words and abbreviations and ask them to define a mechanism to provide the explanation of such words or the expansion of the abbreviations. Assess how students define a mechanism to provide explanations of unusual words and expansions of abbreviations.

{% include excol.html type="end" %}

{% include excol.html type="start" %}

### Topic: Labels and Instructions

{% include excol.html type="middle" %}

Discuss the use of visual and non-visual cues (including labels, instructions, and graphical representations) to help people understand components. Explain that defining how to present these cues is  a responsibility of the designer, whereas providing such cues is a responsibility shared with the content author.

#### Learning Outcomes for Topic

Students should be able to:

* define clear and distinguishable names for components, including visual and programmatic labels
* define overall instructions to make information in multi-step processes more understandable, for example visual and non-visual cues, and graphical representations 
* define visual and non-visual instructions to communicate the total number of steps and the current step in multi-step forms and processes
* define related controls, such as those collecting personal information, payment methods, and consent to legal conditions, and communicate such relationships visually and non-visually

#### Teaching Ideas for Topic

Optional ideas to teach the learning outcomes:

* Show examples of form controls that share the same purpose, such as those collecting personal information, payment methods, and consent to legal conditions. Explain that grouping them is essential for some people to understand and fill in such forms and is useful for all users. Discuss several ways to group those controls both visually and programmatically, such as using proximity relations or putting each of the groups on a dedicated step of the process. Explain that designing the grouping relations and defining how they look like is a designers' responsibility, whereas coding those relations is a developers' responsibility.
* Show examples of long data lists and grids, such as to select a country. Explain that it takes a lot of time for keyboard users to go one by one using the arrow keys to select their desired option. Present mechanisms to filter  information so that it appears in smaller pieces, such as pseudo-search functionality that allows users to type the first letters of their desired choice.

#### Ideas to Assess Knowledge for Topic

Optional ideas to assess knowledge:

* Practical &mdash; Students group related information in a form that asks for information to open a bank account. Assess how students build groups of related information, such as those collecting personal information, payment methods, and consent to legal conditions, and how students provide ways for users to identify each of the groups.
* Practical &mdash; Present students with a long list of items and ask them to define ways to split the list into smaller subsets. Assess how students use different strategies to group  long sets of data into smaller subsets.

{% include excol.html type="end" %}

{% include excol.html type="start" %}

### Topic: Tables

{% include excol.html type="middle" %}

Build on [Foundation Module 6: Understanding and Involving Users](/curricula/foundation-modules/understanding-and-involving-users/). Research strategies that people with disabilities use to interact with information presented in tables. For example, through textual descriptions, through graphical representation of the table contents, by splitting a complex table into several simpler tables, and by splitting the information in the table into individual lists.

#### Learning Outcomes for Topic

Students should be able to:

* identify uses of tables to present data that share a logical relationship
* identify different ways of presenting tabular information, such as using several lists, or splitting a complex table into several simpler ones
* define table header cells and data cells, and provide clear and distinguishable styles for each
* create designs with graphical representations of complex tables that help users more easily understand its purpose and meaning
* evaluate the use of complex tables and select simpler ways to provide the information, for example:
  * simpler tables
  * charts, diagrams, and other graphical representations
  * plain text
* identify related requirements for developers to programmatically associate table descriptions, data cells, and header cells with their corresponding table
* identify related requirements for content authors to provide table descriptions where appropriate

#### Teaching Ideas for Topic

Optional ideas to teach the learning outcomes:

* Show examples of different types of information presented in tables. Explain that tables are used when there is a logical, tabular relationship between the information presented, for example when displaying a list of events with their date and venue.
* Refer back to [Designer Module 1: Topic Adaptability](/curricula/designer-modules/visual-design/#topic-adaptability) and explain that some users may require different ways of presenting tabular information. For example, providing graphical representations for complex tables, splitting complex tables into simpler ones, and using lists to group the logically related information.
* Show examples of table data cells and header cells. Discuss with students which of these cells should be the header cells and which should be the data cells. Emphasize that the relation between the table data cells and header cells needs to be perceived both visually and programmatically. Explain that providing the styles is a designers' responsibility, whereas establishing the programmatic relationship is a responsibility shared with the developer.

#### Ideas to Assess Knowledge for Topic

Optional ideas to assess knowledge:

* Practical &mdash; Give students  a set of tables and ask them to define their header cells and data cells. Assess how students understand the difference between header cells and data cells.
* Practical &mdash; Present students with a set of tables and ask them to provide clear styles to distinguish data cells from header cells. Assess how students provide clear and distinguishable styles for header cells and data cells.
* Practical &mdash; Present students with a complex table and ask them to split the information using simpler tables, lists, and graphical representations where appropriate. Assess how students provide alternative ways to present tabular information.

{% include excol.html type="end" %}

{% include excol.html type="all" %}

## Ideas to Assess Knowledge for Module

Optional ideas to assess knowledge:

* Portfolio &mdash; Students organize different pieces of information on a website, including text, forms, and images. Assess how students provide mechanisms for people to identify different pieces of information, how students split large amounts of information into smaller and more manageable pieces, and how they group related information together.

## Teaching Resources

Suggested resources to support your teaching:

* [Designing for Web Accessibility](/tips/designing/) &mdash; Tips for user interface and visual design.
* [[How People with Disabilities Use the Web]](/people-use-web/) &mdash; Provides stories of people with disabilities using the Web; describes types of disabilities and some of the barriers that people encounter using the Web; and introduces types of assistive technologies and adaptive strategies that some people use.
* [Keyboard Compatibility (Web Accessibility Perspectives)](https://www.w3.org/WAI/perspective-videos/keyboard/) &mdash; Is one of the Web accessibility perspectives videos that show accessibility features and how they impact people with disabilities.
* [Understandable Content (Web Accessibility Perspective)](/perspective-videos/understandable/) &mdash; Is one of the Web accessibility perspectives videos that show accessibility features and how they impact people with disabilities.
* [WCAG](https://www.w3.org/WAI/standards-guidelines/wcag/) &mdash; Address accessibility of web content on desktops, laptops, tablets, and mobile devices.
