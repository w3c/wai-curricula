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
  next:
---

## Introduction
{:.no-display}

Courses based on this module should:

* explain strategies that people with disabilities use to  operate interactive user interface components
* describe some accessibility requirements related to keyboard interactions, input gestures, labels, instructions, notifications, and feedback

## Learning Outcomes for Module

Students should be able to:

* explain strategies that people with disabilities use to operate interactive user interface components
* design user interfaces that support different input mechanisms, including mouse, touch, and keyboard
* provide clear and distinguishable ways to identify interactive user interface components, including through naming and placement
* provide methods to help understand the context, information, and functionality of user interface components, including through textual instructions, color, and other visual cues
* provide meaningful and descriptive notifications about imminent time limits, status changes, and feedback from user input, including errors, suggestions for correction, and success messages
* design user interfaces with meaningful sequence of interactive user interface components
* define custom interaction patterns, such as where to place focus when a dialog is open and closed, and what the focus order should be within those dialogs
* define mechanisms to obtain information about custom interaction patterns, such as specific keyboard shortcuts for applications and expected behavior of custom widgets
* identify related requirements for developers to programmatically associate properties of interactive user interface components, such as names, states, and instructions, to their corresponding component
* identify related requirements for developers to write code for custom keyboard interactions that interactive user interface components may require

{% include excol.html type="all" %}

## Competencies

Skills required for this module:

{% include excol.html type="start" %}

### Students

{% include excol.html type="middle" %}

* [Prerequisites for students](/curricula/designer-modules#prerequisites-for-students)
* Prior [Designer Modules](/curricula/designer-modules/)

{% include excol.html type="end" %}

{% include excol.html type="start" %}

### Instructors

{% include excol.html type="middle" %}

* Applied expertise in teaching:
  * @@@

{% include excol.html type="end" %}

## Topics to Teach

Topics to achieve the learning outcomes:

{% include excol.html type="start" %}

### Topic: Keyboard Interaction

{% include excol.html type="middle" %}

Discuss standard keyboard interactions, such as the use of the Tab, Enter, or arrow keys. Explain that if non-standard keyboard interactions are to be used,  designers need to define them and collaborate with developers to implement them.

#### Learning Outcomes for Topic

Students should be able to:

* design custom user interfaces that support operation with the keyboard
* identify situations when it is necessary to provide additional keyboard shortcuts, for example when designing a custom functionality that is not keyboard supported by default
* design user interfaces that wherever possible avoid keyboard shortcut conflicts with the operating system, browser, and assistive technologies
* describe related requirements for developers to write code for user interface components to be entered, operated, and exited using the keyboard only
  
#### Teaching Ideas for Topic

Optional ideas to teach the learning outcomes:

* Reflect on standard keyboard conventions. For example, use of the tab to move through interactive controls, use of the arrow keys to move through list items, and use of the Enter key to select an item. Explain that these need to be preserved as much as possible when designing custom functionality, and custom keyboard interaction should be defined when these standard conventions are not enough to achieve the goals of the user interface. Explain that defining keyboard interaction is a designer's responsibility, whereas implementing such interaction is a responsibility shared with the developer.
* Present some examples of keyboard shortcuts that may conflict with browsers, operating systems, and assistive technologies. For example, modifier keys are used by browsers and assistive technologies to provide built-in functionality. Explain that these keystrokes should be avoided wherever possible.

#### Ideas to Assess Knowledge for Topic

Optional ideas to support assessment:

* Practice &mdash; Present students with a user interface that can be interacted only with the mouse and ask them to define keyboard interaction patterns. Assess how students understand the need for alternatives to mouse input and how they use standard keyboard interactions wherever possible.

{% include excol.html type="end" %}

{% include excol.html type="start" %}

### Topic: Labels and Instructions

{% include excol.html type="middle" %}

Show examples of labels and instructions for form controls and custom widgets. Explain that they are essential for cognitive disabilities to understand and interact with these components.

#### Learning outcomes for Topic

Students should be able to:

* provide names to help users understand the purpose and intent of interactive user interface components
* design user interfaces that allow to position labels where users expect them
* provide instructions about which input fields are required by:
  * including information about each of the required form fields before the form control
  * including color, text, and visual cues in the label of each of the required form fields that indicates that they are required
* provide clear instructions about changes in context before the control that originates such changes
* provide overall instructions about existing time limits in a form and about how they can be turned off, adjusted, or extended
* provide clear instructions about the current step and about the total number of steps involved in a multi-step form
* identify related requirements for developers to code labels and instructions appropriately

#### Teaching Ideas for Topic

Optional ideas to teach the learning outcomes:

* Show examples of different interactive components, such as buttons, links, or widgets, and emphasize that each should have a clear name that allows to identify its purpose. For reference on how to provide names for different user interface components, see
* Demonstrate how labels for form fields are placed differently depending on the components, the language, and the user expectations. For example, labels for edit boxes are placed to the left of the field or above it in left-to-right languages, and to the right of the field or below it in right-to-left languages. Labels for radio buttons are placed to the right of the field or below it in left-to-right languages, or to the left of the field or above it in right-to-left languages. For references on how to place labels for form fields, see
* Show examples of required and non-required form fields. Explain that instructions for which of the fields is required should be provided using several mechanisms, including color, text, and other visual cues. For references on how to communicate that form fields are required, see
* Present examples of time limits, such as those warning about session expirations. Explain that instructions need to be provided so that users are aware of the time limits, and mechanisms need to be put in place to stop, adjust, or extend time limits. Explain that defining and providing the instructions is a responsibility of the designer, whereas implementing mechanisms to stop, extend, or adjust time limits is a responsibility shared with the developer.
* Show examples of multi-step forms. Explain that overall instructions should be provided about the current step in a form and about the total number of steps involved.

#### Ideas to Assess Knowledge for Topic

Optional ideas to support assessment:

* Practical &mdash; Present students with a form fields and ask them to define labels for each. Assess how students provide clear and descriptive names for each of the form fields.
* Practical &mdash; Give students a form field and ask them to provide the necessary instructions for users to understand and fill in the form. Assess how students provide clear and concise instructions.

{% include excol.html type="end" %}

{% include excol.html type="start" %}

### Topic: Gestures and Motion

{% include excol.html type="middle" %}

Show examples of user interfaces that react to motion, such as shaking the device to perform a specific action. Explain that some people may perform these motion based gestures inadvertently, some others may not be able to perform them at all. Discuss some alternatives to motion-based gestures. 

Discuss some gestures that require dragging and drawing specific shapes on a tactile screen. Explain that these are difficult (and sometimes impossible) for some people with mobility impairments.

#### Learning Outcomes for Topic

Students should be able to:

* design user interfaces that support alternatives to device or user motion such as shaking, by using user interface components that do not require motion
* design user interfaces that support disabling response to motion to prevent accidental actuation, such as undoing an action by shaking a device
* design user interfaces that support alternatives to multi-pointer gestures (such as swipe or pinch) using single pointer activation
* design user interfaces that support undoing or aborting an action carried out with path-based operations

#### Teaching Ideas for Topic

Optional ideas to teach the learning outcomes:

* Show examples of gestures that require motion, such as shaking the device, to perform an action. Explain that users with mobility impairments cannot perform such gestures, thus user interfaces need to have alternatives that do not require motion for these gestures.
* Show examples of gestures such as swipe or ping. Explain that users with mobility impairments cannot perform such gestures, thus user interfaces need to have alternatives that do not require swiping or pinching to perform an action.
* Show examples of operations carried out using path-based  gestures, such as dragging. Explain that people with mobility impairments may inadvertently initiate touch or mouse events, thus user interfaces need to support alternatives for people to perform actions associated with multi-pointer gestures or to undo actions carried out inadvertently with multi-pointer gestures.

#### Ideas to Assess Knowledge for Topic

Optional ideas to support assessment:

* Practical &mdash; Give students an interface that uses a motion-based gesture to perform an action and ask them to provide alternatives to that gesture. Assess how students provide alternatives to motion-based gestures.
* Practical &mdash; Give students an interface that uses a multi path based gesture to perform an action and ask them to provide alternatives to that gesture. Assess how students provide alternatives to multi-pointer and path-based gestures.

{% include excol.html type="end" %}

{% include excol.html type="start" %}

### Topic: Feedback and Notifications

{% include excol.html type="middle" %}

Show examples of notification messages. Explain that they need to be distinguishable by all users, including through visual cues and programmatically.

Explain that applications may have different levels of priority when in the context of a complex application. Defining such levels of priority and which types of notifications each of them should contain is a designers responsibility.

#### Learning Outcomes for Topic

Students should be able to:

* design user interfaces with  notifications that are easy to understand and that can be distinguished from any other user interface component
* provide meaningful and descriptive messages about errors, suggestions for corrections, successes, or any other event
* design user interfaces that allow to switch notifications on or off to allow notifications processing at the users' pace
* design user interfaces that support mechanisms to queue and prioritize application notifications coming from different interactive user interface components, such as form fields and custom widgets
* describe related requirements for developers to code notification messages appropriately

#### Teaching Ideas for Topic

Optional ideas to teach the learning outcomes:

* Show examples of different mechanisms to communicate notifications, such as through text messages, haptic and audio feedback, and popup windows.
* Demonstrate different types of error messages and explain why it is necessary to communicate the specific field where the error has occurred and, if possible, provide suggestions for users to correct the error.
* Show examples of overlapping notifications in the context of web applications. Explain that some users may find it daunting to process several notifications at the same time, so there should be a mechanism that allows to prioritize notifications based on their relevance.

#### Ideas to Assess Knowledge for Topic

Optional ideas to support assessment:

* Practical &mdash; Present students with a form field submission containing errors and ask them to provide notifications about each form field that contains errors, together with suggestions for corrections whenever possible. Assess how students provide adequate error messages for each of the wrong fields and how they provide suggestions for corrections whenever possible.

{% include excol.html type="end" %}

{% include excol.html type="all" %}

## Ideas to Assess Knowledge for Module

Optional ideas to support assessment:

[To be developed.]

## Teaching Resources

Suggested resources to support your teaching:

[To be developed.]
