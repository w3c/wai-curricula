---
title: "[Draft] Module 3: Information Design"
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
navigation:
  previous: /curricula/designer-modules/navigation/
  next: /curricula/designer-modules/images-and-graphics/
---

## Introduction
{:.no-display}

Courses based on this module should:

* present strategies to split large blocks of information into smaller pieces 
* present strategies for grouping information that shares a common purpose so that it is easier to understand

## Learning Outcomes for Module

Students should be able to:

* describe approaches to break down different types of content into smaller and more manageable pieces, including:
  * the use of headings, pages, and chapter marks to divide longer passages of text into smaller pieces
  * the use of lists, simpler tables, and plain text to convey information presented in complex tables
  * the use of groups of form controls that share a common purpose
  * the use of filters to display smaller data subsets from a given large data set
* describe the use of labels and instructions to make information in forms more understandable
* identify related requirements for developers to programmatically associate headings, table header cells and data cells, as well as form labels and instructions to their corresponding control

{% include excol.html type="all" %}

## Competencies

Skills required for this module:

{% include excol.html type="start" %}

### Students

{% include excol.html type="middle" %}

* [Prerequisites for students](/curricula/designer-modules#prerequisites-for-students)
* [Module 2: Flexible and Responsive Design](/curricula/designer-modules/flexible-and-responsive-design/)
* [Module 3: Navigation](/curricula/designer-modules/navigation/)

{% include excol.html type="end" %}

{% include excol.html type="start" %}

### Instructors

{% include excol.html type="middle" %}

* Applied expertise in teaching:
  * @@@
  * [WCAG Success Criterion 1.3.1 Info and Relationships](https://www.w3.org/WAI/WCAG21/quickref/#info-and-relationships)
  * [WCAG Success Criterion 1.3.5 Identify Input Purpose](https://www.w3.org/WAI/WCAG21/quickref/#identify-input-purpose)
  * [WCAG Success Criterion 2.1.1 Keyboard](https://www.w3.org/WAI/WCAG21/quickref/#keyboard)
  * [WCAG Success Criterion 3.3.2 Labels or Instructions](https://www.w3.org/WAI/WCAG21/quickref/#labels-or-instructions)
* In-depth knowledge of:
  * [Prerequisites for students](/curricula/designer-modules#prerequisites-for-students)
  * Visual Design
  * Responsive Design
  * Information Architecture

{% include excol.html type="end" %}

## Topics to Teach

Topics to achieve the learning outcomes:

{% include excol.html type="start" %}

### Topic: Textual Information

{% include excol.html type="middle" %}

Refer back to [Module 3: Navigation](/curricula/designer-modules/navigation/). Discuss ways to split large amounts of text into smaller pieces. For example, using headings and their corresponding rank levels, and pages to split the contents into logical units, and chapter markers to indicate chapters in digital publications.

Discuss the use of icons and other visual cues to help people understand the contents presented in text.

#### Learning Outcomes for Topic

Students should be able to:

* design user interfaces that support splitting large amounts of text into several smaller and more manageable pieces by using:
  * headings and their corresponding rank levels
  * sidebars and other page regions
  * pages,
  * chapter markers
* design user interfaces with icons and other visual cues to help users understand information presented in text
* design user interfaces with mechanisms to identify specific definitions of words and meaning of phrases, such as professional terms, idioms, and jargon
* design user interfaces with mechanisms to identify the expanded form or meaning of acronyms and abbreviations
* identify related requirements for developers to make language programmatically determined
* identify related requirements for content authors to provide clear language and easy-to-read texts whenever possible

#### Teaching Ideas for Topic

Optional ideas to teach the learning outcomes:

* Show examples of large amounts of text for example an ebook. Discuss several ways to divide the text both visually and programmatically so that it is easier to understand and to navigate. For example by using headings and their corresponding  rank levels together with pages and chapter markers to indicate the different chapters, sections, and subsections of content.
* Show examples of how icons and other symbols can complement information presented in text. Explain that they help users with reading disabilities understand difficult pieces of text. For reference on how to provide visual illustrations, pictures, and symbols to help explain ideas, events, and processes, see technique [G103: Providing visual illustrations, pictures, and symbols to help explain ideas, events, and processes](https://www.w3.org/WAI/WCAG21/Techniques/general/G103).
* Show examples of words that may be difficult to understand or that are used in a restricted way. Explain that users with cognitive disabilities or those not familiar with such words need definitions to understand the meaning of such words.  Explain that defining the mechanisms to provide such definitions is a designers' responsibility, whereas providing the definitions is a responsibility shared with the content author.
* Show examples of abbreviations,  such as short forms of words and acronyms. Explain that users with cognitive disabilities and those not familiar with the abbreviations need an explanation or an expansion of that abbreviation to understand their meaning. Explain that defining the mechanisms to provide such explanations or expansions is a designers' responsibility, whereas providing the explanations or expansions is a responsibility shared with the content author. abbreviation](https://www.w3.org/WAI/WCAG21/Techniques/general/G102).

#### Ideas to Assess Knowledge for Topic

Optional ideas to support assessment:

* Practical &mdash; Present students with an ebook and ask them to define how it should be split into smaller and more manageable pieces so that it can be easier to navigate and understand. Assess how students use headings and rank levels, pages, and chapter markers to split large amounts of text into smaller and more manageable pieces.
* Practical &mdash; Present students with unusual words and abbreviations and ask them to define a mechanism to provide the explanation of such words or the expansion of the abbreviations. Assess how students define a mechanism to provide explanations of unusual words and expansions of abbreviations.

{% include excol.html type="end" %}

{% include excol.html type="start" %}

### Topic: Tabular Information

{% include excol.html type="middle" %}

Explain different ways in which people with disabilities access tabular information. For example, splitting a complex table into several simpler tables, and splitting the information in the table into individual lists.

#### Learning Outcomes for Topic

Students should be able to:

* identify uses of tables to present data that share a logical relationship
* design user interfaces that support multiple ways of presenting tabular information, such as using several lists, or splitting a complex table into several simpler ones
* define table header cells and data cells, and provide clear and distinguishable styles for each
* identify related requirements for content authors to write table descriptions that provide information about what the table is about
* identify related requirements for developers to programmatically associate table descriptions, data cells, and header cells with their corresponding table

#### Teaching Ideas for Topic

Optional ideas to teach the learning outcomes:

* Show examples of different types of information presented in tables. Explain that tables are used when there is a logical relationship between the information presented, for example when displaying a list of events with their date and venue.
* Refer back to Module 2: Flexible Layout and Design [Topic: Flexible Design](/curricula/designer-modules/flexible-layout-and-design/#topic-flexible-design) and explain that some users may require different ways of presenting tabular information. Explain that these include splitting complex tables into simpler ones and using lists to group the logically related information.
* Show examples of table data cells and header cells. Discuss with students which of these cells should be the header cells and which should be the data cells. Emphasize that the relation between the table data cells and header cells needs to be perceived both visually and programmatically for users to understand their relations, and that clear styles should be provided. Explain that providing the styles is a designer's responsibility, whereas establishing the programmatic relationship is a responsibility shared with the developers.

#### Ideas to Assess Knowledge for Topic

Optional ideas to support assessment:

* Practical &mdash; Give students  a set of tables and ask them to define their header cells and data cells. Assess how students understand the difference between header cells and data cells.
* Practical &mdash; Present students with a set of tables and ask them to provide clear styles to distinguish data cells from header cells. Assess how students provide clear and distinguishable styles for header cells and data cells.

{% include excol.html type="end" %}

{% include excol.html type="start" %}

### Topic: Forms and Controls

{% include excol.html type="middle" %}

Show examples of how different groups of people interact with large amounts of selectable data, such as a list of countries. Explain that some prefer filtering out data into smaller pieces to better handle them, some other prefer to type the first letters of their desire option to select it more efficiently.

#### Learning Outcomes for Topic

Students should be able to:

* design user interfaces that support grouping of related form controls, such as those collecting personal information, payment methods, and consent to legal conditions 
* design user interfaces that support filtering data from data lists and grids, for example using search boxes or splitting the data set into smaller subsets of data
* design user interfaces that support keyboard navigation to specific list items of data lists and grids, for example using first letter navigation
* design user interfaces that support customizing the results that are shown at a given time

#### Teaching Ideas for Topic

Optional ideas to teach the learning outcomes:

* Show examples of form controls that share the same purpose, such as those collecting personal information, payment methods, and consent to legal conditions. Explain that grouping them is essential for some people to interact and fill in such forms and is useful for all users. Discuss several ways to group those controls both visually and programmatically, such as using proximity relations or putting each of the groups on a dedicated step of the process. Explain that designing the grouping relations and defining how they look like is a designers' responsibility, whereas coding those relations is a developers' responsibility.
* Show examples of long lists of data, such as lists of countries or cities on a travel application. Explain that these lists are difficult to navigate with the keyboard, as it takes a long time to go through the different options one by one by pressing the arrow keys. Discuss several ways to make these interactions more efficient, such as providing ways for the user to type the first letters of their desired option, which reduces the amount of shown results, and providing ways for people to filter the data they want revealed by the use of pseudo-search boxes.

#### Ideas to Assess Knowledge for Topic

Optional ideas to support assessment:

* Practical &mdash; Students group related information in a form that asks for information to open a bank account. Asses how students build groups of related information, such as those collecting personal information, payment methods, and consent to legal conditions, and how students provide ways for users to identify each of the groups.

{% include excol.html type="end" %}

{% include excol.html type="all" %}

## Ideas to Assess Knowledge for Module

Optional ideas to support assessment:

* Portfolio &mdash; Students include different pieces of information on a website, for example text, forms, and images. Assess how students provide mechanisms for people to identify different pieces of information, how students split large amounts of information into smaller and more manageable pieces, and how they group related information together.

## Teaching Resources

Suggested resources to support your teaching:

* @@@
* [How People with Disabilities Use the Web](/people-use-web/) &mdash; Provides stories of people with disabilities using the Web; describes types of disabilities and some of the barriers that people encounter using the Web; and introduces types of assistive technologies and adaptive strategies that some people use.
* [Keyboard Compatibility (Web Accessibility Perspectives)](https://www.w3.org/WAI/perspective-videos/keyboard/) &mdash; Is one of the Web accessibility perspectives videos that show accessibility features and how they impact people with disabilities.
* [WCAG](https://www.w3.org/WAI/standards-guidelines/wcag/) &mdash; Address accessibility of web content on desktops, laptops, tablets, and mobile devices.
