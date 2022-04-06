---
title: "[Draft] Module 5: Data Tables"
nav_title: "Data Tables"
permalink: /curricula/content-author-modules/data-tables/
ref: /curricula/content-author-modules/data-tables/
lang: en
github:
  repository: w3c/wai-curricula
  path: content/content-author-modules/data-tables.md
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
  previous: /curricula/content-author-modules/images/
  next: /curricula/content-author-modules/multimedia/
---

## Introduction
{:.no-display}

Courses based on this module should:

* demonstrate how people with disabilities rely on the visual and non-visual identification of header and data cells to understand, navigate, and process data tables
* explain accessibility requirements related to data tables

## Learning Outcomes for Module

Students should be able to:

* explain how people with disabilities rely on appropriate table markup and clear relations between header and data cells to understand, navigate, and process information presented in data tables
* collaborate with designers and developers to provide alternatives for:
  * complex images, including charts, diagrams, and infographics, for example using data tables
  * data tables, for example using charts, diagrams, and infographics
* designate the cell role and scope in a table, including header and data cells
* provide table summaries and descriptions to help users understand the purpose of complex tables
* employ accessible authoring tools that produce accessible markup for data tables
* collaborate with designers and developers to achieve the desired visual presentation of multi-column content using styles instead of layout tables
* identify related requirements for designers to ensure appropriate contrast ratio for charts, diagrams, infographics, and data tables

{% include excol.html type="all" %}

## Competencies

Skills required for this module:

{% include excol.html type="start" %}

### Students

{% include excol.html type="middle" %}

* [Foundation Prerequisites](/curricula/developer-modules/#foundation-prerequisites)
* Prior [Content Author Modules](/curricula/content-author-modules/)
* Basic knowledge of:
  * Content creation
  * Content editing

{% include excol.html type="end" %}

{% include excol.html type="start" %}

### Instructors

{% include excol.html type="middle" %}

* Applied expertise in teaching:
  * [WCAG 2 Success Criterion 1.1.1 Non-Text Content](https://www.w3.org/WAI/WCAG21/quickref/#non-text-content)
  * [WCAG 2 Success Criterion 1.3.1 Info and Relationships](https://www.w3.org/WAI/WCAG21/quickref/#info-and-relationships)
  * @@@
* In-depth knowledge of
  * [Foundation Prerequisites](/curricula/developer-modules/#foundation-prerequisites)
  * Prior [Content Author Modules](/curricula/content-author-modules/)
  * Authoring tools accessibility

{% include excol.html type="end" %}

## Topics to Teach

Topics to achieve the learning outcomes:

{% include excol.html type="start" %}

### Topic: Header Cells

{% include excol.html type="middle" %}

[Intro paragraph TBD].

#### Learning Outcomes for Topic

Students should be able to:

* explain how people with disabilities rely on appropriate visual and non-visual identification of table headers to understand the type of information presented in a row or column
* define table headers as those which provide information about the type of data in a row or column
* provide short, descriptive column and row headers for tables
* employ accessible tools that produce appropriate markup for table headers, including the header scope

#### Teaching Ideas for Topic

Optional ideas to teach the learning outcomes:

* Demonstrate use of assistive technologies to navigate data tables. Emphasize how table headers are announced before or after the data cells they are associated to.
* Show examples of table header cells. Explain that table headers contain succinct and clear information about the data the column or row contains.
* Introduce accessible tools that produce appropriate markup for header cells. Explain how to designate a given cell as header and how to define the header scope using the tool's user interface.

#### Ideas to Assess Knowledge for Topic

Optional ideas to assess knowledge:

* Short Answer Questions &mdash; Ask students to explain what table headers are and what type of information they should contain. Assess how students define table headers and how they understand the type of information headers should contain.
* Practical &mdash; Give students a table without designated headers and ask them to designate the headers and their scope. Assess how students understand the purpose and scope of table headers.
* Practical &mdash; Have students designate the table headers and their scope using an accessible tool of their choice. Assess how students use accessible authoring tools to designate the table headers and their scope.

{% include excol.html type="end" %}

{% include excol.html type="start" %}

### Topic: Data Cells

{% include excol.html type="middle" %}

[Intro paragraph TBD].

#### Learning Outcomes for Topic

Students should be able to:

* explain how assistive technologies associate data cells with their corresponding header cells
* describe data cells as those which contain information of a specific type of data
* provide clear and succinct information in each data cell
* employ accessible tools that produce appropriate markup for table data cells, including the cell scope

#### Teaching Ideas for Topic

Optional ideas to teach the learning outcomes:

* Demonstrate use of assistive technologies to navigate table data cells. Emphasize how data cells are associated to their corresponding header cells. Some assistive technologies announce the header cell before the data cell, others do the opposite way.
* Explain that data cells contain information of a specific type of data. Emphasize that it is good practice to keep tables as simple as possible, providing one specific type of data in one column or row. Explain that merged cells are problematic for some people that have difficulty to understand the cell's scope.
* Introduce accessible authoring tools that produce appropriate markup for data cells. Explain how to designate a cell as data cell and how to define the cell scope using the tool's user interface.

#### Ideas to Assess Knowledge for Topic

Optional ideas to assess knowledge:

* Short Answer Questions &mdash; Ask students to explain what table data cells are and what type of information they should contain. Assess how students define table data cells.
* Practical &mdash; Give students a table and ask them to designate the data cells and their scope. Assess how students understand the purpose and scope of table data cells.
* Practical &mdash; Have students mark the table data cells as such and to define their scope using an accessible tool of their choice. Assess how students use accessible authoring tools to mark the table data cells and their scope.

{% include excol.html type="end" %}

{% include excol.html type="start" %}

### Topic: Summaries and Descriptions

{% include excol.html type="middle" %}

[Intro paragraph [TBD].

#### Learning Outcomes for Topic

Students should be able to:

* explain how people with disabilities rely on meaningful table summaries and descriptions to understand the table purpose and to more easily navigate them
* provide table summaries that help identify the tables purpose
* write captions that:
  * provide navigational hints for complex tables
  * describe how the table is organized
  * provide information about the type of data in each column and row
* employ accessible authoring tools that:
  * support the inclusion of table descriptions
  * produce accessible markup for table descriptions

#### Teaching Ideas for Topic

Optional ideas to teach the learning outcomes:

* Demonstrate how assistive technologies announce the table summary and caption as the user moves through different tables on the same page. Explain that this information helps the user differentiate one table from the other, as well as it provides information on what the table is about.
* Show examples of table summaries. Explain that they provide information on what the table is about. Emphasize that it is good practice to display these summaries on screen, as they are essential for some users and benefit all.
* Explain situations where people need additional information to understand the table purpose and how it is organized. This includes complex tables, tables that are difficult to navigate,  and tables containing information that is difficult to process, among others. Explain that table captions use to hold this additional information.
* Introduce accessible authoring tools that produce appropriate markup for table summaries and descriptions. Explain that some tools may refer to table summaries as titles or names, and may refer to table descriptions as descriptions or captions.

#### Ideas to Assess Knowledge for Topic

Optional ideas to assess knowledge:

* Short Answer Questions &mdash; Ask students what type of information the table summary and the table description should contain. Assess how students explain what type of information the table summary and description should contain.
* Practical &mdash; Have students include the table summary and description using an accessible authoring tool of their choice. Assess how students rely on the tool's built-in functionality to include the table summary and description.

[TBD.]

{% include excol.html type="end" %}

{% include excol.html type="all" %}

## Ideas to Assess Knowledge for Module

Optional ideas to assess knowledge:

* Practical &mdash; Give students a chart and ask them to provide the alternative using a regular data table. Assess how students provide alternatives to charts using regular data tables.
* Portfolio &mdash; Have students include data tables in the web page they are creating. Assess how students designate the role of the cells and how they provide table descriptions where appropriate.

## Teaching Resources

Suggested resources to support your teaching:

* [Writing for Web Accessibility](https://www.w3.org/WAI/tips/writing/) -- Introduces some basic considerations to help you get started writing web content that is more accessible to people with disabilities.
* [[How People with Disabilities Use the Web]](/people-use-web/) &mdash; Describes some of the barriers that people encounter using the Web; and introduces types of assistive technologies and adaptive strategies that some people use.
* [Clear Layout and Design (Web Accessibility Perspectives)](https://www.w3.org/WAI/perspective-videos/layout/) &mdash; Is one of the Web accessibility perspectives videos that show accessibility features and how they impact people with disabilities.
* [Understandable Content (Web Accessibility Perspective)](/perspective-videos/understandable/) &mdash; Is one of the Web accessibility perspectives videos that show accessibility features and how they impact people with disabilities.
* [WCAG](https://www.w3.org/WAI/standards-guidelines/wcag/) &mdash; Address accessibility of web content on desktops, laptops, tablets, and mobile devices.
[TBD]
