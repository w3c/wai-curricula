---
title: "[Draft] Module 4: Information Design"
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
* present strategies to group information that shares a common purpose so that it is easier to process

## Learning Outcomes for Module

Students should be able to:

* describe approaches to break down different types of content into smaller and more manageable pieces, including:
  * the use of headings and pages to divide longer passages of text into smaller pieces
  * the use of lists, simpler tables, and plain text to convey information presented in complex tables
  * the use of groups of form controls that share a common purpose
  * the use of filters to display small data subsets from a given data set
* describe the use of labels and instructions to make information in forms more understandable
* identify related requirements for developers to programmatically associate text alternatives, headings, table header cells and data cells, and form labels and instructions, to their corresponding control

{% include excol.html type="all" %}

## Competencies

Skills required for this module:

{% include excol.html type="start" %}

### Students

{% include excol.html type="middle" %}

* [Prerequisites for students](/curricula/designer-modules#prerequisites-for-students)
* [Module 2: Flexible and Responsive Design](/curricula/designer-modules/flexible-and-responsive-design/)
* [Module 3: Navigation](/curricula/designer-mdoules/navigation/)

{% include excol.html type="end" %}

{% include excol.html type="start" %}

### Instructors

{% include excol.html type="middle" %}

* In-depth knowledge of:
  * [Prerequisites for students](/curricula/designer-modules#prerequisites-for-students)
* Applied expertise in teaching:
  * [WCAG Success Criterion 3.3.2 Labels or Instructions](https://www.w3.org/WAI/WCAG21/quickref/#labels-or-instructions)
  * @@@

{% include excol.html type="end" %}

## Topics to Teach

Topics to achieve the learning outcomes:

{% include excol.html type="start" %}

### Topic: Textual Information

{% include excol.html type="middle" %}

Present ways to split large amounts of text into smaller pieces, such as by using headings or pages.

Discuss mechanisms to supplement information presented only with text, such as use of icons and other visual cues.

#### Learning Outcomes for Topic

Students should be able to:

* design user interfaces that support additional ways to convey information presented in text, using icons and other visual cues
* design user interfaces that support mechanisms to identify specific definitions of words and meaning of phrases, such as professional terms, idioms, and jargon
* design user interfaces that support mechanisms to identify the expanded form or meaning of acronyms and abbreviations
* identify related requirements for developers to make language programmatically determined
* identify related requirements for content authors to provide clear language and easy-to-read texts whenever possible

#### Teaching Ideas for Topic

Optional ideas to teach the learning outcomes:

[To be developed.]

#### Ideas to Assess Knowledge for Topic

Optional ideas to support assessment:

[To be developed.]

{% include excol.html type="end" %}

{% include excol.html type="start" %}

### Topic: Tabular Information

{% include excol.html type="middle" %}

Explain different ways in which people with disabilities visualize tabular information, for example split into several simpler tables or putting the information in lists.

#### Learning Outcomes for Topic

Students should be able to:

* identify uses of tables to present data that share a logical relationship
* design user interfaces that support multiple ways of presenting tabular information, such as using several lists, or splitting a complex table into several simpler ones
* define table header cells and data cells, and provide clear and distinguishable styles for each
* identify related requirements for content authors to write table descriptions that provide information about what the table is about
* identify related requirements for developers to programmatically associate table descriptions, data cells, and header cells with their corresponding table

#### Teaching Ideas for Topic

Optional ideas to teach the learning outcomes:

* Show examples of different types of information presented in tables. Explain that tables are used when there is a logical relationship between the information presented, for example when presenting a list of events with their date and venue.
* Refer back to [Module 2: Flexible and Responsive Design](/curricula/designer-modules/flexible-and-responsive-design) and explain that some users may require different ways of presenting tabular information. Explain that these include splitting complex tables into simpler ones and using lists to group the logically related information.
* Show examples of table data cells and header cells. Discuss with students which of these cells should be the header cells and which should be the data cells. Emphasize that the relation between the table data cells and header cells needs to be perceived both visually and programmatically for users to understand the relationship between these two types of cells, and that clear styles should be provided. Explain that providing the styles is a designer's responsibility, whereas establishing the programmatic relationship is a responsibility shared with the developers.

#### Ideas to Assess Knowledge for Topic

Optional ideas to support assessment:

* Practical &mdash; Give students  a set of tables and ask them to define their header cells and data cells. Assess how students understand the difference between header cells and data cells.
* Practical &mdash; Present students with a set of tables and ask them to provide clear styles to distinguish data cells from header cells. Assess how students provide clear and distinguishable styles for header cells and data cells.

{% include excol.html type="end" %}

{% include excol.html type="start" %}

### Topic: Grouping and Sorting Information

{% include excol.html type="middle" %}

#### Learning Outcomes for Topic

Students should be able to:

* design user interfaces that support grouping of related form controls, such as those collecting personal information, payment methods, and consent to legal conditions 
* provide examples of expected input wherever possible, such as how a phone number should be entered and what the different credit card fields should contain
* design user interfaces that support programmatic and visual grouping of related links, such as those from a navigation menu or from a product category

#### Teaching Ideas for Topic

Optional ideas to teach the learning outcomes:

[To be developed.]

#### Ideas to Assess Knowledge for Topic

Optional ideas to support assessment:

[To be developed.]

{% include excol.html type="end" %}

{% include excol.html type="start" %}

### Topic: Data Visualization

{% include excol.html type="middle" %}

#### Learning Outcomes for Topic

Students should be able to:

* create user interfaces that support filtering of data using different mechanisms such as search boxes or subsets of data
* create user interfaces that allow to use the keyboard to navigate to specific pieces of data
* create user interfaces that allow customizing the results that are shown at a given time

#### Teaching Ideas for Topic

Optional ideas to teach the learning outcomes:

[To be developed.]

#### Ideas to Assess Knowledge for Topic

Optional ideas to support assessment:

[To be developed.]

{% include excol.html type="end" %}

## Ideas to Assess Knowledge for Module

Optional ideas to support assessment:

[To be developed].

## Teaching Resources

Suggested resources to support your teaching:

[To be developed].

