---
title: "[Draft] Module 7: Interaction and Feedback"
nav_title: "Interaction and Feedback"
permalink: /curricula/designer-modules/interaction-and-feedback/
ref: /curricula/designer-modules/interaction-and-feedback/
lang: en
github:
  repository: w3c/wai-curricula
  path: content/designer/interaction-and-feedback.md
license: creative-commons
acknowledgements: /curricula/acknowledgements/
changelog: /curricula/changelog/
footer: >
  <p><strong>Date:</strong> Updated @@ Month 2021. First published December 2019. CHANGELOG</p>
  <p><strong>Editors:</strong> Daniel Montalvo and <a href="http://www.w3.org/People/shadi/">Shadi Abou-Zahra</a>. Contributors: <a href="https://www.w3.org/WAI/EO/EOWG-members">EOWG Participants</a>. ACKNOWLEDGEMENTS lists contributors and credits.</p>
  <p>Developed by the Education and Outreach Working Group (<a href="http://www.w3.org/WAI/EO/">EOWG</a>). Developed with support from the <a href="https://www.w3.org/WAI/about/projects/wai-guide/">WAI-Guide Project</a> funded by the European Commission (EC) under the Horizon 2020 program (Grant Agreement 822245).</p>
navigation:
  previous: /curricula/designer-modules/multimedia-and-animations/
  next: /curricula/designer-modules/flexible-and-responsive-design/
---

## Introduction
{:.no-display}

Courses based on this module should:

[To be developed.]

## Learning Outcomes for Module

Students should be able to:

* explain strategies that people with disabilities use to identify, distinguish, and operate interactive user interface components
* design user interfaces that support different input mechanisms, including mouse, touch, and keyboard
* provide clear and distinguishable ways to identify interactive user interface components, including through naming and placement
* provide methods to help understand the context, information, and functionality of user interface components, including through textual instructions, visual cues, and icons
* provide meaningful and descriptive notifications about imminent time limits, status changes, and feedback from user input, including errors, suggestions for correction, and success messages
* design user interfaces with meaningful sequence of interactive user interface components
* define custom interaction patterns, such as where to place focus when a dialog is open and closed, and what the focus order should be within those dialogs
* define mechanisms to obtain information about custom interaction patterns, such as specific keyboard shortcuts for applications and expected behavior of custom widgets
* identify related requirements for developers to programmatically associate properties of interactive user interface components, such as names, states, and instructions, to their corresponding component
* identify related requirements for developers to write code for custom keyboard interactions that interactive user interface components may require

## Competencies

Skills required for this module:

[To be developed.]

## Topics to Teach

Topics to achieve the learning outcomes:

### Topic: Keyboard Input

#### Learning Outcomes for Topic

Students should be able to:

* design user interfaces that support operation with the keyboard
* identify situations when it may be necessary to provide  additional keyboard shortcuts, for example when designing a custom functionality
* design user interfaces that support keyboard shortcuts that avoid conflicts with the operating system, browser, and assistive technologies keyboard shortcuts
* describe related requirements for developers to ensure every user interface component can be entered, operated, and exited using the keyboard only
  
#### Teaching Ideas for Topic

Optional ideas to teach the learning outcomes:

#### Ideas to Assess Knowledge for Topic

Optional ideas to support assessment:

[To be developed.]

### Topic: Labels and Instructions

#### Learning outcomes for Topic

Students should be able to:

* provide names to help users understand the purpose and intent of interactive user interface components
* design user interfaces that allow to position labels where users expect them, for example
* provide instructions about which input fields are required by:
  * including information about each of the required form fields before the form control
  * including text, icons, and color in the label of each of the required form fields that indicates that they are required
* provide clear instructions about changes in context that happen when there is a change  on a control before the control, for example when launching a new window when the user checks a check box or selects a list item
* provide overall instructions about existing time limits in a form and about how they can be turned off, adjusted, or extended
* provide clear instructions about the current step and about the total number of steps involved in a multi-step form
* identify related requirements for developers to code labels and instructions appropriately

#### Teaching Ideas for Topic

Optional ideas to teach the learning outcomes:

* Show examples of different interactive components, such as buttons, links, or widgets, and emphasize that each should have a clear name that allows to identify its purpose. For reference on how to provide names for different user interface components, see
* Demonstrate how labels for form fields are placed differently depending on the components, the language, and the user expectations. FOr example, labels for edit boxes are placed to the left of the field or above it in left-to-right languages, and to the right of the field or below it in right-to-left languages. Labels for radio buttons are placed to the right of the field or below it in left-to-right languages, or to the left of the field or above it in right-to-left languages. For references on how to place labels for form fields, see
* Show examples of required and non-required form fields. Explain that instructions for which of the fields is required should be provided using several mechanisms, including color, text, or icons. For references on how to communicate that form fields are required, see
* Discuss reasons for implementing time limits, such as exams or security purposes. Explain that instructions need to be provided so that users are aware of the time limits, and mechanisms need to be put in place to stop, adjust, or extend time limits. Explain that providing the instructions is a responsibility of the designer, whereas implementing mechanisms to stop, extend, or adjust time limits is a responsibility shared with the developer.
*( Show examples of multi-step forms. Explain that overall instructions should be provided about the current step in a form and about the total number of steps involved.

#### Ideas to Assess Knowledge for Topic

Optional ideas to support assessment:

[To be developed.]

### Topic: Feedback and Notifications

#### Learning Outcomes for Topic

Students should be able to:

* design user interfaces with  notifications that are easy to understand and that can be distinguished from any other user interface component
* provide meaningful and descriptive messages about errors, suggestions for corrections, successes, or any other event
* design user interfaces that allow to switch notifications on or off to allow notifications processing at the users pace
* design user interfaces that support mechanisms to queue and prioritize application notifications coming from different interactive user interface components, such as form fields and custom widgets
* describe related requirements for developers to code notification messages appropriately

#### Teaching Ideas for Topic

Optional ideas to teach the learning outcomes:

* Show examples of different mechanisms to communicate notifications, such as through text messages, haptic and audio feedback, and pop up windows.
* Demonstrate different types of error messages and explain why it is necessary to communicate the specific field where the error has occurred and, if possible, provide suggestions for users to correct the error.
* Show examples of overlapping notifications in the context of a web applications. Explain that some users may find it daunting to process several notifications at the same time, so there should be a mechanism that allows to prioritize notifications based on their relevance.

#### Ideas to Assess Knowledge for Topic

Optional ideas to support assessment:

[To be developed.]

### Topic: Gestures and Animations

#### Learning Outcomes for Topic

Students should be able to:

* design user interfaces that support alternatives to device or user motion such as shaking, by using user interface components that do not require motion
* design user interfaces that support disabling response to motion to prevent accidental actuation, such as undoing an action by shaking a device
* create designs that support alternatives to multi-pointer gestures (such as swipe or pinch) using single pointer activation
* design user interfaces with down events on single pointer gestures that:
  * do not perform any action, or
  * have available mechanisms to abort or undo any action carried on
S
#### Teaching Ideas for Topic

Optional ideas to teach the learning outcomes:

[To be developed.]

#### Ideas to Assess Knowledge for Topic

Optional ideas to support assessment:

[To be developed.]

## Ideas to Assess Knowledge for Module

Optional ideas to support assessment:

[To be developed.]

## Teaching Resources

Suggested resources to support your teaching:

[To be developed.]
