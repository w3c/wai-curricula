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
* provide data tables as alternative data visualizations for charts, diagrams, and infographics
* designate the cell role and scope in a table, including header and data cells
* provide table summaries and descriptions to help users understand the purpose of complex tables
* collaborate with designers and developers to present multi-column content using CSS styles instead of layout tables
* ensure presentation of data table content in a meaningful sequence for different user configuration and assistive technologies
* identify related requirements for:
  * designers to ensure appropriate contrast ratio for data tables
  * authoring tools to produce appropriate markup for data tables

{% include excol.html type="all" %}

## Competencies

Skills required for this module:

{% include excol.html type="start" %}

### Students

{% include excol.html type="middle" %}

* [Foundation Prerequisites](/curricula/developer-modules/#foundation-prerequisites)
* Prior [Content Author Modules](/curricula/content-author-modules/)
* Basic knowledge of:
  * Writing
  * Copy-editing
  * Proofreading
  * Content creation

{% include excol.html type="end" %}

{% include excol.html type="start" %}

### Instructors

{% include excol.html type="middle" %}

* Applied expertise in teaching:
  * [WCAG 2 Success Criterion 1.1.1 Non-Text Content](https://www.w3.org/WAI/WCAG21/quickref/#non-text-content)
  * [WCAG 2 Success Criterion 1.3.1 Info and Relationships](https://www.w3.org/WAI/WCAG21/quickref/#info-and-relationships)
  * [WCAG Success Criterion 1.3.2 Meaningful Sequence](https://www.w3.org/WAI/WCAG21/quickref/#meaningful-sequence)
* In-depth knowledge of
  * [Foundation Prerequisites](/curricula/developer-modules/#foundation-prerequisites)
  * Prior [Content Author Modules](/curricula/content-author-modules/)
  * Accessible content creation

{% include excol.html type="end" %}

## Topics to Teach

Topics to achieve the learning outcomes:

{% include excol.html type="start" %}

### Topic: Table Header Cells

{% include excol.html type="middle" %}

Table header cells and their scope identify the information provided in a row or column. Explain how specifying the table header cells is essential for some groups of people with disabilities to understand the table contents.

#### Learning Outcomes for Topic

Students should be able to:

* explain how people with disabilities rely on appropriate visual and non-visual identification of table header cells to understand the type of information presented in a row or column
* define table headers as those cells which provide information about the type of data in a row or column
* provide short, descriptive column and row headers for tables
* specify the scope for headers that span multiple rows or columns
* identify related requirements for authoring tools to produce appropriate markup for table headers, including the headers scope

#### Teaching Ideas for Topic

Optional ideas to teach the learning outcomes:

* Demonstrate use of assistive technologies to navigate data tables. Emphasize how header cells are announced before or after the data cells they are associated to.
* Show examples of header cells. Explain that these cells contain clear and succinct information about the data the column or row contains.
* Give students tables with headers that span multiple rows and columns. Help them brainstorm which of the cells should be the header cells and how many rows and columns the headers should span. Emphasize that content authors should provide this information through an accessible authoring tool or through annotations for designers and developers to implement these tables.
* Introduce accessible tools that produce appropriate markup for header cells. Explain how to designate a given cell as header and how to define the header scope via the tool's user interface.

#### Ideas to Assess Knowledge for Topic

Optional ideas to assess knowledge:

* Short Answer Questions &mdash; Ask students what type of information header cells should contain. Assess how students understand the type of information table headers cells should contain.
* Practical &mdash; Give students a table without designated headers. Ask them to tell which cells should be the header cells and how many rows and/or columns the headers should span. Assess how students recognize the header cells as well as their scope.
* Practical &mdash; Have students designate the header cells and their scope using an accessible authoring tool of their choice. Assess how students use accessible authoring tools to designate the header cells and their scope.

{% include excol.html type="end" %}

{% include excol.html type="start" %}

### Topic: Table Data Cells

{% include excol.html type="middle" %}

Table data cells contain information about a specific type of data in a row or column. Explain how clearly specifying the type of information contained in table dat cells as well as specifying the cell scope helps people with disabilities understand the table contents.

#### Learning Outcomes for Topic

Students should be able to:

* explain how assistive technologies associate data cells with their corresponding header cells
* describe data cells as those which contain information of a specific type of data
* provide clear and succinct information in each data cell
* ensure content in data cells can be navigated sequentially and is clearly understood when navigated one cell at a time
* identify related requirements for authoring tools to produce appropriate markup for table data cells, including the cell scope

#### Teaching Ideas for Topic

Optional ideas to teach the learning outcomes:

* Demonstrate use of assistive technologies to navigate data cells. Emphasize how data cells are associated to their corresponding header cells. Some assistive technologies announce the header cell before the data cell, others do the opposite way.
* Explain that data cells contain information about a specific type of data. Emphasize that it is good practice to keep tables as simple as possible, providing one specific type of data in one column or row. Explain that merged cells are problematic for some people that have difficulty to understand the cell's scope.
* Introduce accessible authoring tools that produce appropriate markup for data cells. Explain how to designate a cell as data cell and how to define the cell scope using the tool's user interface.

#### Ideas to Assess Knowledge for Topic

Optional ideas to assess knowledge:

* Short Answer Questions &mdash; Ask students what type of information data cells should contain. Assess how students understand the information that the cells should contain.
* Practical &mdash; Give students a table. Ask them to tell which cells should be the data cells and how many columns and/or rows these cells should span. Assess how students recognize the data cells as well as their scope.
* Practical &mdash; Have students mark the data cells as such and to define their scope using an accessible tool of their choice. Assess how students use accessible authoring tools to mark the data cells and their scope.

{% include excol.html type="end" %}

{% include excol.html type="start" %}

### Topic: Table Summaries and Descriptions

{% include excol.html type="middle" %}

Table summaries identify the table purpose. Table descriptions explain what the table is about and how it is organized. Both summaries and descriptions help people with disabilities distinguish tables from one another on a page.

#### Learning Outcomes for Topic

Students should be able to:

* explain how people with disabilities rely on meaningful table summaries and descriptions to understand the table purpose and to distinguish tables from one another
* provide summaries that explain what the table is about
* write descriptions that:
  * explain how the table is organized
  * provide information about the type of data in each column and row
* identify related requirements for authoring tools to:
  * support the inclusion of summaries and descriptions
  * produce appropriate markup for summaries and descriptions

#### Teaching Ideas for Topic

Optional ideas to teach the learning outcomes:

* Demonstrate how assistive technologies announce the summary and description as the user moves through different tables on the same page. Explain that this information helps users distinguish one table from the other when there are several tables on the page. 
* Show examples of table summaries. Explain that summaries provide information about what the table is about. Emphasize that it is good practice to display these summaries on screen, as they are beneficial for all users.
* Reflect with students on situations where some groups of users need additional information to understand the table purpose and how it is organized. This includes tables with headers that span multiple rows or columns, tables that are difficult to navigate, and tables containing information that is difficult to process. Explain that table descriptions use to hold this additional information.
* Give students tables that need summaries and descriptions and help them brainstorm which information they would include in the summary and which information they would include in the description.
* Introduce accessible authoring tools that produce appropriate markup for table summaries and descriptions. Some tools may refer to summaries as "titles" or "names" and may refer to descriptions as "descriptions" or "captions".

#### Ideas to Assess Knowledge for Topic

Optional ideas to assess knowledge:

* Short Answer Questions &mdash; Ask students what type of information the table summary and description should contain. Assess how students explain what type of information the table summary and description should contain.
* Practical &mdash; Have students include the table summary and description using an accessible authoring tool of their choice. Assess how students rely on the tool's built-in functionality to include the table summary and description.

{% include excol.html type="end" %}

{% include excol.html type="all" %}

## Ideas to Assess Knowledge for Module

Optional ideas to assess knowledge:

* Practical &mdash; Give students a chart and ask them to provide an alternative data visualization using a regular data table. Assess how students provide alternative data visualizations to charts using regular data tables.
* Portfolio &mdash; Have students include data tables in the web page they are creating. Assess how students designate the table header and data cells and their scope as well as how they provide table summaries and descriptions where appropriate.

## Teaching Resources

Suggested resources to support your teaching:

* [Writing for Web Accessibility](https://www.w3.org/WAI/tips/writing/) -- Introduces some basic considerations to help you get started writing web content that is more accessible to people with disabilities.
* [[How People with Disabilities Use the Web]](/people-use-web/) &mdash; Describes some of the barriers that people encounter using the Web; and introduces types of assistive technologies and adaptive strategies that some people use.
* [Clear Layout and Design (Web Accessibility Perspectives)](https://www.w3.org/WAI/perspective-videos/layout/) &mdash; Is one of the Web accessibility perspectives videos that show accessibility features and how they impact people with disabilities.
* [Understandable Content (Web Accessibility Perspective)](/perspective-videos/understandable/) &mdash; Is one of the Web accessibility perspectives videos that show accessibility features and how they impact people with disabilities.
* [WCAG](https://www.w3.org/WAI/standards-guidelines/wcag/) &mdash; Address accessibility of web content on desktops, laptops, tablets, and mobile devices.
