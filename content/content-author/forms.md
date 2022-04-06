---
title: "[Draft] Module 3: Forms"
nav_title: "Forms"
permalink: /curricula/content-author-modules/forms/
ref: /curricula/content-author-modules/forms/
lang: en
github:
  repository: w3c/wai-curricula
  path: content/content-author-modules/forms.md
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
  previous: /curricula/content-author-modules/structure/
  next: /curricula/content-author-modules/images/
---

## Introduction
{:.no-display}

Courses based on this module should:

* demonstrate how people with disabilities rely on clear labels and instructions for form fields and controls, including edit boxes, lists, buttons, and others, to understand and interact with web pages and applications
* explain accessibility requirements for labels and instructions for form fields and controls

## Learning Outcomes for Module

Students should be able to:

* explain how people with disabilities rely on clear and meaningful labels and instructions for form fields and controls, including edit boxes, lists, buttons, and others, to understand and interact with web pages and applications
* provide clear and meaningful textual and visual labels for form fields and controls that help users understand their purpose
* provide textual and visual instructions that describe the overall purpose and intent of the form
* provide instructions about the current step and about the total number of steps in a multi-step process
* collaborate with designers and developers to provide:
  * instructions about expected input types and formats
  * error messages that identify the field in error
  * suggestions for correction when possible based on the selected input formats and validation methods
* identify related requirements for designers and developers to ensure visual and non-visual perception of and operation with forms and controls

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
  * [WCAG 2 Success Criterion 1.3.1 Info and Relationships](https://www.w3.org/WAI/WCAG21/quickref/#info-and-relationships)
  * [WCAG 2 Success Criterion 1.3.5 Identify Input Purpose](https://www.w3.org/WAI/WCAG21/quickref/#identify-input-purpose)
  * [WCAG 2 Success Criterion 2.2.1 Timing Adjustable](https://www.w3.org/WAI/WCAG21/quickref/#timing-adjustable)
  * [WCAG 2 Success Criterion 2.4.6 Headings and Labels](https://www.w3.org/WAI/WCAG21/quickref/#headings-and-labels)
  * [WCAG 2 Success Criterion 2.5.3 Label in Name](https://www.w3.org/WAI/WCAG21/quickref/#label-in-name)
  * [WCAG 2 Success Criterion 3.2.2 On Input](https://www.w3.org/WAI/WCAG21/quickref/#on-input)
  * [WCAG 2 Success Criterion 3.3.1 Error Identification](https://www.w3.org/WAI/WCAG21/quickref/#error-identification)
  * [WCAG 2 Success Criterion 3.3.2 Labels or Instructions](https://www.w3.org/WAI/WCAG21/quickref/#labels-or-instructions)
  * [WCAG 2 Success Criterion 3.3.3 Error Suggestion](https://www.w3.org/WAI/WCAG21/quickref/#error-suggestion)
  * [WCAG 2 Success Criterion 3.3.4 Error Prevention](https://www.w3.org/WAI/WCAG21/quickref/#error-prevention-legal-financial-data)
* In-depth knowledge of
  * [Foundation Prerequisites](/curricula/developer-modules/#foundation-prerequisites)
  * Prior [Content Author Modules](/curricula/content-author-modules/)
  * Authoring tools accessibility

{% include excol.html type="end" %}

## Topics to Teach

Topics to achieve the learning outcomes:

{% include excol.html type="start" %}

### Topic: Labels

{% include excol.html type="middle" %}

[Intro paragraph TBD].

#### Learning Outcomes for Topic

Students should be able to:

* explain how people with disabilities rely on clear and meaningful labels to identify and understand the purpose of form fields and controls
* provide unique and descriptive labels for form fields and controls
* employ accessible authoring tools that:
  * support the inclusion of labels for controls
  * programmatically associate labels to their corresponding control
* collaborate with designers and developers to ensure visual and non-visual perception of labels

#### Teaching Ideas for Topic

Optional ideas to teach the learning outcomes:

* Demonstrate assistive technology interaction with form fields and controls, including edit boxes, lists, buttons, and others. Explain that providing labels that describe the purpose of the controls is essential for several groups of users.
* Reflect with students about commonly used labels for form fields and controls, including "name", "surname", "address", "phone", "email", and others. Explain that the label should be a short, succinct, and straightforward text that communicates the purpose and intent of the control.
* Explain that some users rely on imagery and iconography to understand the purpose of these labels.
* Introduce accessible authoring tools that support the inclusion of labels for forms and controls and that programmatically associate these to the form field and control. Explain that some tools may refer to labels as "names" or similar terminology. Emphasize that content authors should provide these labels and the tool should associate the label to the corresponding form field and control.

#### Ideas to Assess Knowledge for Topic

Optional ideas to assess knowledge:

* Short Answer Questions &mdash; Ask students about the type of information that labels should contain. Assess how students recall the type of information  that labels should contain.
* Practical &mdash; Give students several form fields and controls without a label and ask them to provide one for each. Assess how students provide short, succinct, and straightforward labels for controls.
* Practical &mdash; Have students include labels for form fields and controls in a tool of their choice that programmatically associates the labels with their corresponding control. Assess how students use an authoring tool of their choice to include labels for form fields and controls.

{% include excol.html type="end" %}

{% include excol.html type="start" %}

### Topic: Instructions

{% include excol.html type="middle" %}

[Intro paragraph TBD].

#### Learning Outcomes for Topic

Students should be able to:

* explain how people with disabilities rely on clear instructions to understand the content and to provide accurate input when required
* provide clear instructions about the overall purpose of the content
* write additional instructions that provide examples of expected input when possible
* include instructions about the current step and about the total number of steps in a multi-step process
* employ accessible authoring tools that:
  * support the inclusion of instructions for overall content and for specific parts of the content
  * programmatically associate instructions to their corresponding control
* identify related requirements for designers and developers to support visual and non-visual perception of  instructions

#### Teaching Ideas for Topic

Optional ideas to teach the learning outcomes:

[TBD.]

#### Ideas to Assess Knowledge for Topic

Optional ideas to assess knowledge:

[TBD]

{% include excol.html type="end" %}

{% include excol.html type="start" %}

### Topic: Error Messages

{% include excol.html type="middle" %}

[Intro paragraph TBD]

#### Learning Outcomes for Topic

Students should be able to:

* explain how people with disabilities rely on error messages that communicate the problem and suggest possible fixes where possible
* write error messages that communicate the problem by:
  * identifying the field in error
  * specifying the cause of the error
* provide suggestions for fixing the errors when possible by providing:
  * examples of expected input
  * additional guidance for users to understand the required input

### Teaching Ideas for Topic

Optional ideas to teach the learning outcomes:

[TBD]

### Ideas to Assess Knowledge for Topic

Optional ideas to assess knowledge:

[TBD]

{% include excol.html type="end" %}

{% include excol.html type="all" %}

## Ideas to Assess Knowledge for Module

Optional ideas to assess knowledge:

[TBD]

## Teaching Resources

Suggested resources to support your teaching:

* [Writing for Web Accessibility](https://www.w3.org/WAI/tips/writing/) -- Introduces some basic considerations to help you get started writing web content that is more accessible to people with disabilities.
* [[How People with Disabilities Use the Web]](/people-use-web/) &mdash; Describes some of the barriers that people encounter using the Web; and introduces types of assistive technologies and adaptive strategies that some people use.
* [Clear Layout and Design (Web Accessibility Perspectives)](https://www.w3.org/WAI/perspective-videos/layout/) &mdash; Is one of the Web accessibility perspectives videos that show accessibility features and how they impact people with disabilities.
* [Understandable Content (Web Accessibility Perspective)](/perspective-videos/understandable/) &mdash; Is one of the Web accessibility perspectives videos that show accessibility features and how they impact people with disabilities.
* [WCAG](https://www.w3.org/WAI/standards-guidelines/wcag/) &mdash; Address accessibility of web content on desktops, laptops, tablets, and mobile devices.
