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

* demonstrate how people with disabilities rely on clear labels and instructions to understand and interact with web pages and applications that include forms
* explain accessibility requirements for form fields and controls, including edit boxes, list boxes, buttons, and other form interactions 

## Learning Outcomes for Module

Students should be able to:

* explain how people with disabilities rely on clear labels and meaningful instructions for form fields and controls, including edit boxes, list boxes, buttons, and others, to understand and interact with web pages and applications
* write clear labels for form fields and controls that help users understand their purpose
* provide meaningful instructions that describe the overall purpose and intent of the form
* write instructions about the current step and about the total number of steps in a multi-step process
* collaborate with designers and developers to include:
  * instructions about expected input types and formats
  * error messages that identify the field in error and communicate the problem
  * suggestions for correction when possible based on the selected input formats and the validation methods in use
* identify related requirements for designers and developers to ensure visual and non-visual perception and operation of forms and controls

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
  * Editing
  * Proofreading

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
* In-depth knowledge of:
  * [Foundation Prerequisites](/curricula/developer-modules/#foundation-prerequisites)
  * Prior [Content Author Modules](/curricula/content-author-modules/)
  * Accessible content creation

{% include excol.html type="end" %}

## Topics to Teach

Topics to achieve the learning outcomes:

{% include excol.html type="start" %}

### Topic: Labels

{% include excol.html type="middle" %}

[Intro paragraph TBD].

#### Learning Outcomes for Topic

Students should be able to:

* explain how people with disabilities rely on clear labels to identify and understand the purpose of form fields and controls
* provide unique and descriptive labels for form fields and controls
* explain requirements for authoring tools to programmatically associate labels to their corresponding control
* collaborate with designers and developers to include icons, symbols, and other imagery to make text labels easier to understand
* identify related requirements for developers and designers to ensure visual and non-visual perception of labels

#### Teaching Ideas for Topic

Optional ideas to teach the learning outcomes:

* Demonstrate assistive technology interaction with form fields and controls, including the use of voice commands, keystrokes, and gestures to go directly to specific types of form fields and controls. Explain that providing labels that describe the purpose of the controls is essential for several groups of users.
* Reflect with students about commonly used labels for form fields and controls, including "name", "surname", "address", "phone", "email", and others. Explain that the label should be a unique, clear, and descriptive text that communicates the purpose and intent of the form field or control.
* Explain that some users find it hard to process text labels. They rely on imagery, including icons and symbols, to understand the purpose of these labels. Emphasize that content authors need to collaborate with designers and developers to complement text labels with imagery that helps these users understand the purpose of form fields and controls.
* Introduce accessible authoring tools that programmatically associate labels to the form field and control. Explain that some tools may refer to labels as "names" or similar terminology. Emphasize that content authors should provide these labels and the tool should associate the label to the corresponding form field and control. Standard HTML elements may suffice, and WAI-ARIA properties may be required when building custom form fields and controls.

#### Ideas to Assess Knowledge for Topic

Optional ideas to assess knowledge:

* Short Answer Questions &mdash; Ask students about the type of information that labels should contain. Assess how students understand the type of information  that labels should contain.
* Practical &mdash; Give students several form fields and controls without a label and ask them to provide one for each. Assess how students provide unique, clear and descriptive labels for controls.
* Practical &mdash; Have students collaborate with designers and developers to select icons and symbols that complement text labels. Assess how students relate text labels to complementary imagery.
* Practical &mdash; Have students include labels for form fields and controls in a tool of their choice that programmatically associates the labels with their corresponding control. Assess how students use an authoring tool of their choice to include labels for form fields and controls.

{% include excol.html type="end" %}

{% include excol.html type="start" %}

### Topic: Instructions

{% include excol.html type="middle" %}

[Intro paragraph TBD].

#### Learning Outcomes for Topic

Students should be able to:

* explain how people with disabilities rely on clear instructions to understand the content and to provide input reliably when required
* provide clear instructions about the overall purpose of the form
* write additional instructions that provide examples of expected input when possible
* include instructions about the current step and about the total number of steps in a multi-step process
* explain requirements for authoring tools to programmatically associate instructions to their corresponding form field or control
* identify related requirements for designers and developers to support visual and non-visual perception of instructions

#### Teaching Ideas for Topic

Optional ideas to teach the learning outcomes:

* Demonstrate use of form fields and controls with and without meaningful instructions. Reflect with students on how these instructions help all users, including those with disabilities, to provide the appropriate input and to interact with the form fields and controls.
* Discuss examples of instructions for overall forms, including explanations about what type of data the form collects. Providing these instructions is a content author's responsibility. Defining the appearance of the instructions is a responsibility of the designer. Implementing them is a developer's responsibility.
* Show examples of form fields that collect data in a specific format, for example fields collecting date and phone numbers. Authors should include examples of how to provide the input, unless these examples compromise the security and purpose of the form.
* Demonstrate approaches to providing instructions for multi-step processes. For example, including this information in the page title or before the form.
* Introduce accessible authoring tools that programmatically associate instructions to the corresponding form field or control. Explain that some tools may refer to instructions as "descriptions", "tooltips", and others. Emphasize that content authors should provide these instructions and the tool should associate the instructions to the corresponding form field and control. Standard HTML elements may suffice, and WAI-ARIA properties may be required when building custom form fields and controls.

#### Ideas to Assess Knowledge for Topic

Optional ideas to assess knowledge:

* Short Answer Questions &mdash; Ask students what type for information instructions should contain. Assess how students understand the type of information that instructions should contain.
* Practical &mdash; Give students a multi-step process and ask them to provide the instructions for each of the steps. Assess how students provide the relevant instructions for each of the steps in a multi-step process.
* Practical &mdash; Give students a form field with specific input requirements and ask them to provide instructions about how to provide that input. Assess how students provide instructions to help users complete form fields.

{% include excol.html type="end" %}

{% include excol.html type="start" %}

### Topic: Error Messages

{% include excol.html type="middle" %}

[Intro paragraph TBD]

#### Learning Outcomes for Topic

Students should be able to:

* explain how people with disabilities rely on error messages that communicate the problem and suggest fixes where possible
* provide error messages that communicate the problem by:
  * identifying the field in error
  * specifying the cause of the error
* include suggestions for fixing the errors when possible by providing:
  * examples of expected input
  * additional guidance for users to understand the required input
* explain requirements for authoring tools to programmatically associate error messages with their corresponding control

### Teaching Ideas for Topic

Optional ideas to teach the learning outcomes:

* Demonstrate assistive technology interaction with form fields that contain accessible error messages and with those that do not. Reflect with students on how accessible error messages are essential for people with disabilities and help all interact with form fields and correct errors.
* Demonstrate approaches to communicating error messages. For example, identifying the fields that caused the error and providing suggestions to correct the problem when these do not compromise the security of the interface.

### Ideas to Assess Knowledge for Topic

Optional ideas to assess knowledge:

* Short Answer Questions &mdash; Ask students what type of information error messages should contain. Assess how students understand the information that error messages should contain.
* Practical &mdash; Give students a form submission containing errors and ask them to provide accessible error messages. Assess how students provide error messages that identify the field in error and provide suggestions for correction where possible.

{% include excol.html type="end" %}

{% include excol.html type="all" %}

## Ideas to Assess Knowledge for Module

Optional ideas to assess knowledge:

* Practical &mdash; Supervise students while they navigate form fields and controls using assistive technologies and adaptive strategies. Assess how students navigate form fields and controls using assistive technologies and adaptive strategies.
* Portfolio &mdash; Have students include accessible labels, instructions, and error messages for form fields and controls. Assess how students provide unique, descriptive labels as well as meaningful instructions and error messages for form fields and controls.

## Teaching Resources

Suggested resources to support your teaching:

* [Writing for Web Accessibility](https://www.w3.org/WAI/tips/writing/) -- Introduces some basic considerations to help you get started writing web content that is more accessible to people with disabilities.
* [[How People with Disabilities Use the Web]](/people-use-web/) &mdash; Describes some of the barriers that people encounter using the Web; and introduces types of assistive technologies and adaptive strategies that some people use.
* [Clear Layout and Design (Web Accessibility Perspectives)](https://www.w3.org/WAI/perspective-videos/layout/) &mdash; Is one of the Web accessibility perspectives videos that show accessibility features and how they impact people with disabilities.
* [Understandable Content (Web Accessibility Perspective)](/perspective-videos/understandable/) &mdash; Is one of the Web accessibility perspectives videos that show accessibility features and how they impact people with disabilities.
* [WCAG](https://www.w3.org/WAI/standards-guidelines/wcag/) &mdash; Address accessibility of web content on desktops, laptops, tablets, and mobile devices.