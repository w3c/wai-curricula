---
title: "[Draft] Module 7: Forms Design [WIP]"
nav_title: "Forms Design"
permalink: /curricula/designer-modules/forms-design/
ref: /curricula/designer-modules/forms-design/
lang: en
github:
  repository: w3c/wai-curricula
  path: content/designer/forms-design.md
license: creative-commons
acknowledgements: /curricula/acknowledgements/
changelog: /curricula/changelog/
footer: >
  <p><strong>Date:</strong> Updated @@ Month 2021. First published December 2019. CHANGELOG</p>
  <p><strong>Editors:</strong> Daniel Montalvo and <a href="http://www.w3.org/People/shadi/">Shadi Abou-Zahra</a>. Contributors: <a href="https://www.w3.org/WAI/EO/EOWG-members">EOWG Participants</a>. ACKNOWLEDGEMENTS lists contributors and credits.</p>
  <p>Developed by the Education and Outreach Working Group (<a href="http://www.w3.org/WAI/EO/">EOWG</a>). Developed with support from the <a href="https://www.w3.org/WAI/about/projects/wai-guide/">WAI-Guide Project</a> funded by the European Commission (EC) under the Horizon 2020 program (Grant Agreement 822245).</p>parent_in_h1:
  - ref: /curricula/designer-modules/
    name: nav_title
  - ref: /curricula/
    name: "Curricula on Web Accessibility"
navigation:
  previous: /curricula/designer-modules/multimedia-and-animations/
  next:
---

## Introduction
{:.no-display}

Courses based on this module should:

* demonstrate how people with disabilities interact with forms and other components that accept user input
* explain accessibility requirements related to forms and other components that accept user input, including placement, structure, labels, instructions, and notifications

## Learning Outcomes for Module

Students should be able to:

* demonstrate how people with disabilities rely on placement, structure, labels, instructions, and notifications to understand, navigate, and interact with forms
* define consistent placement and appearance of form fields and other components that accept user input
* define interactions with forms and controls that accept user input, including through mouse, keyboard,touch, and voice
* define clear and distinguishable names for forms and other components that accept user input
* define textual instructions, color, and other visual cues to help understand the context, information, and functionality of components that accept user input
* define clear and descriptive visual and non-visual cues about the current step and about the total number of steps in a multi-step process, including multi-step forms
* define clear and descriptive error messages that identify the field in error and provide suggestions for corrections where possible
* define meaningful and descriptive visual and non-visual notifications, including for imminent time limits, success messages, status changes, and feedback from user input
* describe related requirements for developers to implement semantics and programmatic relationships for forms and other components that accept user input

{% include excol.html type="all" %}

## Competencies

Skills required for this module:

{% include excol.html type="start" %}

### Students

{% include excol.html type="middle" %}

* [Foundation Prerequisites](/curricula/designer-modules#foundation-prerequisites)
* Prior [Designer Modules](/curricula/designer-modules/)
* Knowledge of:
  * Visual Design
  * Prototyping
  * Responsive Design
  * Information Design
  * Interaction Design

{% include excol.html type="end" %}

{% include excol.html type="start" %}

### Instructors

{% include excol.html type="middle" %}

* Applied expertise in teaching:
  * [WCAG Success Criterion 1.3.1 Info and Relationships](https://www.w3.org/WAI/WCAG21/quickref/#info-and-relationships)
  * [WCAG Success Criterion 1.3.2 Meaningful Sequence](https://www.w3.org/WAI/WCAG21/quickref/#meaningful-sequence)
  * [WCAG Success Criterion 1.3.3 Sensory Characteristics](https://www.w3.org/WAI/WCAG21/quickref/#sensory-characteristics)
  * [WCAG Success Criterion 1.3.4 Orientation](https://www.w3.org/WAI/WCAG21/quickref/#orientation)
  * [WCAG Success Criterion 1.4.1 Use of Color](https://www.w3.org/WAI/WCAG21/quickref/#use-of-color)
  * [WCAG Success Criterion 1.4.3 Contrast (Minimum)](https://www.w3.org/WAI/WCAG21/quickref/#contrast-minimum)
  * [WCAG Success Criterion 1.4.4 Resize Text](https://www.w3.org/WAI/WCAG21/quickref/#resize-text)
  * [WCAG Success Criterion 1.4.6 Contrast (Enhanced)](https://www.w3.org/WAI/WCAG21/quickref/#contrast-enhanced)
  * [WCAG Success Criterion 1.4.8 Visual Presentation](https://www.w3.org/WAI/WCAG21/quickref/#visual-presentation)
  * [WCAG Success Criterion 1.4.10 Reflow](https://www.w3.org/WAI/WCAG21/quickref/#reflow)
  * [WCAG Success Criterion 1.4.11 Non-Text Contrast](https://www.w3.org/WAI/WCAG21/quickref/#non-text-contrast)
  * [WCAG Success Criterion 1.4.12 Text Spacing](https://www.w3.org/WAI/WCAG21/quickref/#text-spacing)
  * [WCAG Success Criterion 2.1.1 Keyboard](https://www.w3.org/WAI/WCAG21/quickref/#keyboard)
  * [WCAG Success Criterion 2.1.2 No Keyboard Trap](https://www.w3.org/WAI/WCAG21/quickref/#no-keyboard-trap)
  * [WCAG Success Criterion 2.2.1 Timing Adjustable](https://www.w3.org/WAI/WCAG21/quickref/#timing-adjustable)
  * [WCAG Success Criterion 2.2.5 Re-Authenticating](https://www.w3.org/WAI/WCAG21/quickref/#re-authenticating)
  * [WCAG Success Criterion 2.2.6 Timeouts](https://www.w3.org/WAI/WCAG21/quickref/#timeouts)
  * [WCAG Success Criterion 2.4.3 Focus Order](https://www.w3.org/WAI/WCAG21/quickref/#focus-order)
  * [WCAG Success Criterion 2.4.6 Headings and Labels](https://www.w3.org/WAI/WCAG21/quickref/#headings-and-labels)
  * [WCAG Success Criterion 2.4.7 Focus Visible](https://www.w3.org/WAI/WCAG21/quickref/#focus-visible)
  * [WCAG Success Criterion 3.3.1 Error Identification](https://www.w3.org/WAI/WCAG21/quickref/#error-identification)
  * [WCAG Success Criterion 3.3.3 Error Suggestion](https://www.w3.org/WAI/WCAG21/quickref/#error-suggestion)
  * [WCAG Success Criterion 3.3.4 Error Prevention](https://www.w3.org/WAI/WCAG21/quickref/#error-prevention-legal-financial-data)
  * [WCAG Success Criterion 4.1.3 Status Messages](https://www.w3.org/WAI/WCAG21/quickref/#status-messages)
* In-depth knowledge of:
  * [Foundation Prerequisites](/curricula/designer-modules/#foundation-prerequisites)
  * Prior [Designer Modules](/curricula/designer-modules/)
  * Visual Design
  * Prototyping
  * Responsive Design
  * Information Design
  * Interaction Design
* Basic knowledge of coding techniques

{% include excol.html type="end" %}

## Topics to Teach

Topics to achieve the learning outcomes:

{% include excol.html type="start" %}

### Topic: Naming, Grouping, and Placement

{% include excol.html type="middle" %}

Refer back to [Designer Module 2: Information Design, Topic Labels and Instructions](/curricula/designer-modules/information-design/#topic-labels-and-instructions). Show examples of labels and instructions in the context of forms and other complex widgets.

Show examples of different ways to group large amounts of selectable data. For example, filtering out data into smaller pieces to better handle data, and enable mechanisms to type the first letters of their desired option to select data more efficiently.

#### Learning outcomes for Topic

Students should be able to:

* design user experiences that consider position, appearance, and naming for labels and instructions
* define visual and non-visual instructions about which input fields are required
* define clear instructions about changes in context before the control that originates such changes
* define overall instructions about existing time limits in a form and about how to adjust them, extend them, and turn them off
* define clear instructions about the current step and about the total number of steps involved in a multi-step form
* define error messages in the page title or before the form control that:
  * identify the fields in error
  * describe the cause of the error
  * provide suggestions to correct the error where possible
* identify related requirements for developers to provide semantics for labels and instructions appropriately

#### Teaching Ideas for Topic

Optional ideas to teach the learning outcomes:

* Show examples of different components that accept user input (such as buttons, links, lists, and grids) across rich applications or complex widgets. Emphasize that each should have a clear name that allows to identify its purpose. For reference on how to provide names for different user interface components, see technique [G197: Using labels, names, and text alternatives consistently for content that has the same functionality](https://www.w3.org/WAI/WCAG21/Techniques/general/G197).
* Demonstrate how labels for form fields are placed differently depending on the components, the language, and the user expectations. For example, labels for edit boxes are placed to the left of the field or above it in left-to-right languages, and to the right of the field or below it in right-to-left languages. Labels for radio buttons are placed to the right of the field or below it in left-to-right languages, or to the left of the field or above it in right-to-left languages.
* Show examples of required and non-required form fields. Explain that instructions for which of the fields is required should be provided using several mechanisms, including textual and visual cues.
* Present examples of time limits, such as those warning about session expirations. Explain that instructions need to be provided so that users are aware of the time limits, and mechanisms need to be implemented to stop, adjust, or extend time limits. Explain that defining and providing the instructions is a designers' responsibility, whereas implementing mechanisms to stop, extend, or adjust time limits is a responsibility shared with the developer.
* Show examples of multi-step forms. Explain that overall instructions should be provided about the current step in a form and about the total number of steps involved.
* Show examples of different types of error messages, including overall information about errors, specific information about each of the fields in error, and suggestions for correcting such errors when possible. Show examples of user interfaces with and without such error messages and explain that these enable several groups of people with disabilities to better interact and understand the contents.
* Show examples of different mechanisms to communicate notifications, such as through text messages, semantic relations, haptic and audio feedback, and popup windows.
* Show examples of overlapping notifications in the context of complex applications. Explain that some users may find it daunting to process several notifications at the same time, so a mechanism needs to be defined that allows to prioritize notifications based on their relevance. Explain that defining mechanisms to prioritize notifications based on their relevance is a designers' responsibility, whereas implementing the mechanisms is a developers' responsibility.

#### Ideas to Assess Knowledge for Topic

Optional ideas to assess knowledge:

* Practical &mdash; Present students with a form and ask them to define labels for each of the fields. Assess how students provide clear and descriptive names for each of the form fields.
* Practical &mdash; Give students an application and ask them to provide names for each of the application subsections. Assess how students identify application subsections and provide clear and understandable names for each.
* Practical &mdash; Give students a form and ask them to provide the necessary instructions for users to understand each of the fields and fill in the form. Assess how students provide clear and concise instructions.

{% include excol.html type="end" %}

{% include excol.html type="start" %}

### Topic: Errors and Notifications

{% include excol.html type="middle" %}

Show examples of notification messages. Explain that they need to be distinguishable by all users, including through visual cues and programmatically.

Show examples of text and visual notifications for error messages and other types of feedback for forms and widgets. Explain that notifications may have different levels of priority when in the context of a complex application. Explain that defining such levels of priority and which types of notifications each of these levels should contain is a designers' responsibility whereas implementing these levels is a developers' responsibility.

#### Learning Outcomes for Topic

Students should be able to:

* define meaningful and descriptive notification messages, for example:
  * on input (to communicate if the provided input is valid or invalid
  * on task completion (to communicate success or failure of a specific task)
* design user experiences to queue and prioritize application notifications coming from different components
* design user experiences to store and check notifications that disappear after a period of time at the users' pace
* identify related requirements for developers to implement notifications

#### Teaching Ideas for Topic

Optional ideas to teach the learning outcomes:

* Demonstrate different types of error messages, including overall information about errors, specific information about each of the fields in error, and suggestions for correcting such errors when possible. Show examples of user interfaces with and without such error messages and explain that these enable several groups of people with disabilities to better interact and understand the contents.
* Show examples of different mechanisms to communicate notifications, such as through text messages, semantic relations, haptic and audio feedback, and popup windows.
* Show examples of overlapping notifications in the context of complex applications. Explain that some users may find it daunting to process several notifications at the same time, so a mechanism needs to be defined that allows to prioritize notifications based on their relevance. Explain that defining mechanisms to prioritize notifications based on their relevance is a designers' responsibility, whereas implementing the mechanisms is a developers' responsibility.

#### Ideas to Assess Knowledge for Topic

Optional ideas to assess knowledge:

* Practical &mdash; Give students an interface containing errors and ask them to provide an overall descriptive message informing that there are submission errors. Assess how students provide overall informative messages when there are submission errors
* Practical &mdash; Present students with a form field submission containing errors and ask them to provide notifications about each of the wrongly submitted field, together with suggestions for corrections when possible. Assess how students provide appropriate error messages for wrongly submitted fields and how they provide suggestions for corrections when possible.
* Practical &mdash; Give students a form field that validate on user input and ask them too provide descriptive validation messages. Assess how students provide clear validation messages for fields that validate on user input.
* Practical &mdash; 

{% include excol.html type="end" %}

{% include excol.html type="all" %}

## Ideas to Assess Knowledge for Module

Optional ideas to assess knowledge:

[To be developed.]

## Teaching Resources

Suggested resources to support your teaching:

* [How People with Disabilities Use the Web](/people-use-web/) &mdash; Provides stories of people with disabilities using the Web; describes types of disabilities and some of the barriers that people encounter using the Web; and introduces types of assistive technologies and adaptive strategies that some people use.
* [Keyboard Compatibility (Web Accessibility Perspectives)](https://www.w3.org/WAI/perspective-videos/keyboard/) &mdash; Is one of the Web accessibility perspectives videos that show accessibility features and how they impact people with disabilities.
* [Colors with Good Contrast (Web Accessibility Perspective)](/perspective-videos/contrast/) &mdash; Is one of the Web accessibility perspectives videos that show accessibility features and how they impact people with disabilities.
* [Clear Layout and Design (Web Accessibility Perspective)](/perspective-videos/layout/) &mdash; Is one of the Web accessibility perspectives videos that show accessibility features and how they impact people with disabilities.
* [Large Links, Buttons, and Controls (Web Accessibility Perspectives)](/perspective-videos/controls/) &mdash; Is one of the Web accessibility perspectives videos that show accessibility features and how they impact people with disabilities.
* [Notifications and Feedback (Web Accessibility Perspectives)](https://www.w3.org/WAI/perspective-videos/notifications/) &mdash; Is one of the Web accessibility perspectives videos that show accessibility features and how they impact people with disabilities.
* [WCAG](https://www.w3.org/WAI/standards-guidelines/wcag/) &mdash; Address accessibility of web content on desktops, laptops, tablets, and mobile devices.
