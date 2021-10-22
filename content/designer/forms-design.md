---
title: "[Draft] Module 7: Forms Design"
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

* demonstrate how people with disabilities interact with forms 
* explain accessibility requirements related to forms, including placement, structure, labels, instructions, and notifications

## Learning Outcomes for Module

Students should be able to:

* demonstrate how people with disabilities rely on placement, structure, labels, instructions, and notifications to understand, navigate, and interact with forms
* define consistent placement and appearance of form controls and input fields
* define interactions with form  controls and input fields, including through mouse, keyboard, touch, and voice
* define clear and distinguishable names as well as visual and non-visual instructions to understand the purpose and functionality of controls and input fields
* define clear and descriptive visual and non-visual instructions about the current step and about the total number of steps in multi-step forms
* define clear and descriptive error messages that:
  * identify the field in error 
  * provide suggestions for correction where possible
* define meaningful and descriptive visual and non-visual notifications, including for:
  * imminent time limits
  * success messages
  * status changes
  * feedback from user input
* describe related requirements for developers to implement semantics and programmatic relationships for forms

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

### Topic: Labels and Instructions

{% include excol.html type="middle" %}

Refer back to [Designer Module 2: Information Design, Topic: Naming and Grouping](/curricula/designer-modules/information-design/#topic-naming-and-grouping). Show examples of labels and instructions in the context of forms.

#### Learning outcomes for Topic

Students should be able to:

* design user experiences that consider position and appearance for labels and instructions
* define clear and consistent names for form controls and input fields across websites and applications
* define visual and non-visual instructions about which input fields are required
* define clear visual and non-visual instructions about changes in context before the component that originates such changes
* define overall visual and non-visual instructions about existing time limits in a form and about how to adjust them, extend them, and turn them off
* define clear visual and non-visual instructions about the current step and about the total number of steps involved in a multi-step form
* identify related requirements for developers to provide semantics for labels and instructions

#### Teaching Ideas for Topic

Optional ideas to teach the learning outcomes:

* Demonstrate how labels for form fields are placed differently depending on the components, the language, and the user expectations. For example, labels for edit boxes are placed to the left of the field or above it in left-to-right languages, and to the right of the field or below it in right-to-left languages. Labels for radio buttons are placed to the right of the field or below it in left-to-right languages, or to the left of the field or above it in right-to-left languages.
* Show examples of different form controls and input fields , for example buttons, checkboxes, text boxes, and listboxes, across websites and applications. Emphasize that each should have a clear name that identifies its purpose. For reference on how to provide consistent names for different form elements across websites and applications, see technique [G197: Using labels, names, and text alternatives consistently for content that has the same functionality](https://www.w3.org/WAI/WCAG21/Techniques/general/G197).
* Show examples of required and non-required form fields. Explain that instructions about which of the fields are required should be provided using several methods, including visual and non-visual instructions.
* Present examples of time limits, such as those warning about session expirations. Explain that visual and non-visual instructions need to be provided so that users are aware of the time limits, and methods need to be implemented to stop, adjust, or extend time limits. Explain that defining and providing the instructions is a designers' responsibility, whereas implementing methods to stop, extend, or adjust time limits is a responsibility shared with the developer.
* Show examples of multi-step forms. Explain that overall instructions should be provided about the current step in a form and about the total number of steps involved.

#### Ideas to Assess Knowledge for Topic

Optional ideas to assess knowledge:

* Practical &mdash; Give students a form and ask them to define labels for each of the fields. Assess how students provide clear and descriptive names for each of the form fields.
* Practical &mdash; Give students a form with required and non-required fields and ask them to provide visual and non-visual instructions to communicate the required   fields. Assess how students provide clear and understandable instructions for each required field.
* Practical &mdash; Give students a form and ask them to provide the necessary instructions for users to understand each of the fields and fill in the form. Assess how students provide clear and concise instructions.

{% include excol.html type="end" %}

{% include excol.html type="start" %}

### Topic: Error Prevention

{% include excol.html type="middle" %}

Show examples of common input errors and possible ways to correct them. Explain that users rely on clear indications of each of the fields in error and on suggestions for correction where possible.

#### Learning Outcomes for Topic

Students should be able to:

* define the placement and appearance of error messages
* define error messages in the page title or before the form control that:
  * identify the fields in error
  * describe the cause of the error
  * provide suggestions to correct the error where possible

#### Teaching Ideas for Topic

Optional ideas to teach the learning outcomes:

* Show examples of placement and appearance of error messages. Explain that some users rely on consistent placement and appearance of these messages to identify the errors.
* Show examples of overall information about submission errors. Explain that this information makes users aware that their submission contains errors and help them search for specific error messages in the rest of the content.
* Show examples of specific messages that identify each of the fields in error. Explain that these messages help users identify and locate the specific fields that contain errors. Mention that it is best practice to keep the original submision where possible, so that users can understand what needs to be corrected.
* Show examples of suggestions for correction. Explain that these suggestions help users understand what the right way is to submit the form. Emphasize that these suggestions should be provided when possible, unless they compromise the security and the purpose of the form.

#### Ideas to Assess Knowledge for Topic

Optional ideas to assess knowledge:

* Practical &mdash; Give students an interface containing errors and ask them to provide an overall descriptive message informing that there are submission errors. Assess how students provide overall informative messages when there are submission errors
* Practical &mdash; Give students a form field submission containing errors and ask them to provide messages about each of the wrongly submitted field. Assess how students provide appropriate error messages for wrongly submitted fields and how they provide suggestions for correction when possible.
* Practical &mdash; Give students a form field submission containing errors and ask them to provide suggestion for correction when possible. Assess how students provide suggestion for correction.

{% include excol.html type="end" %}

{% include excol.html type="start" %}

### Topic: Notifications

{% include excol.html type="middle" %}

Show examples of notification messages. Explain that they need to be distinguishable by all users, including visually and programmatically.

Show examples of text and visual notifications for error messages and other types of feedback for forms. Explain that notifications may have different levels of priority when in the context of a complex form. Explain that defining such levels of priority and which types of notifications each of these levels should contain is a designers' responsibility whereas implementing these levels is a developers' responsibility.

#### Learning Outcomes for Topic

Students should be able to:

* define the placement and appearance of notifications
* define meaningful and descriptive notification messages, including:
  * on input (to communicate if the provided input is valid or invalid
  * on task completion (to communicate success or failure of a specific task)
* design user experiences to queue and prioritize application notifications coming from different components
* design user experiences to store notifications that disappear after a period of time to be checked at the users' pace
* identify related requirements for developers to implement notifications

#### Teaching Ideas for Topic
  
Optional ideas to teach the learning outcomes:

* Show examples of placement and appearance of notifications. Explain that these notifications need to be distinguishable both visually and non-visually. Explain that defining the notifications placement and appearance is responsibility of the designer, whereas implementing such notifications is a developer's responsibility.
* Show examples of different methods to communicate notifications, such as through text messages, semantic relations, haptic and audio feedback, and popup windows. Explain that there needs to be a variety of methods available to allow interaction by different groups of users.
* Show examples of overlapping notifications. Explain that some users may find it daunting to process several notifications at the same time, so a method needs to be defined that allows to prioritize notifications based on their relevance. Explain that defining methods to prioritize notifications based on their relevance is a designers' responsibility, whereas implementing the methods is a developers' responsibility.
* Demonstrate examples of notification processing using assistive technologies, including screen readers and voice assistants. Explain that the notifications may come at a faster pace than the technology is able to process, so users may end up missing information. Emphasize that it is good practice to design methods to store the notifications to allow users to check the notifications at their own pace.

#### Ideas to Assess Knowledge for Topic

Optional ideas to assess knowledge:

* Practical &mdash; Give students a form field that validate on user input and ask them to provide descriptive validation messages. Assess how students provide clear validation messages for fields that validate on user input.
* Practical &mdash; Give students a form with notifications coming from different fields and ask them to define methods to queue and prioritize such notifications. Assess how students prioritize and organize notifications coming from different views.

{% include excol.html type="end" %}

{% include excol.html type="all" %}

## Ideas to Assess Knowledge for Module

Optional ideas to assess knowledge:

* Short Answer Questions &mdash; Ask students when it is possible to provide suggestions for correction and when it is not. Assess how students identify scenarios where it is possible to provide suggestions for correction and scenarios where it is not.
* Portfolio &mdash; Students design a form. Assess how students consider placement, structure, labels, instructions, and notifications when designing accessible forms.

## Teaching Resources

Suggested resources to support your teaching:

* [Designing for Web Accessibility](/tips/designing/) &mdash; Tips for user interface and visual design.
* [How People with Disabilities Use the Web](/people-use-web/) &mdash; Provides stories of people with disabilities using the Web; describes types of disabilities and some of the barriers that people encounter using the Web; and introduces types of assistive technologies and adaptive strategies that some people use.
* [Keyboard Compatibility (Web Accessibility Perspectives)](https://www.w3.org/WAI/perspective-videos/keyboard/) &mdash; Is one of the Web accessibility perspectives videos that show accessibility features and how they impact people with disabilities.
* [Colors with Good Contrast (Web Accessibility Perspective)](/perspective-videos/contrast/) &mdash; Is one of the Web accessibility perspectives videos that show accessibility features and how they impact people with disabilities.
* [Clear Layout and Design (Web Accessibility Perspective)](/perspective-videos/layout/) &mdash; Is one of the Web accessibility perspectives videos that show accessibility features and how they impact people with disabilities.
* [Large Links, Buttons, and Controls (Web Accessibility Perspectives)](/perspective-videos/controls/) &mdash; Is one of the Web accessibility perspectives videos that show accessibility features and how they impact people with disabilities.
* [Notifications and Feedback (Web Accessibility Perspectives)](https://www.w3.org/WAI/perspective-videos/notifications/) &mdash; Is one of the Web accessibility perspectives videos that show accessibility features and how they impact people with disabilities.
* [WCAG](https://www.w3.org/WAI/standards-guidelines/wcag/) &mdash; Address accessibility of web content on desktops, laptops, tablets, and mobile devices.
