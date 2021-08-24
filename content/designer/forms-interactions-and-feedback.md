---
title: "[Draft] Module 6: Forms, Interactions, and Feedback"
nav_title: "Forms, Interactions, and Feedback"
permalink: /curricula/designer-modules/forms-interactions-and-feedback/
ref: /curricula/designer-modules/forms-interactions-and-feedback/
lang: en
github:
  repository: w3c/wai-curricula
  path: content/designer/forms-interactions-and-feedback.md
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

* explain strategies that people with disabilities use to interact with components that accept user input, such as forms, buttons, links, and widgets
* describe accessibility requirements related to interactions, instructions, semantics, cues, notifications, and feedback

## Learning Outcomes for Module

Students should be able to:

* explain strategies that people with disabilities use to interact with forms and other components that accept user input
* design user experiences for different input mechanisms, including mouse, touch, keyboard, and speech
* define keyboard interactions and meaningful sequences inside complex widgets, including buttons, carousels, sliders, tabs, and treeviews
* assess the use of custom keyboard shortcuts for complex widgets and applications and provide information about their purpose and scope
* define clear and distinguishable ways to identify form fields and other components that accept user input, including through naming and placement
* define mechanisms to help understand the context, information, and functionality of user interface components, including through textual instructions, color, and other visual cues
* define meaningful and descriptive notifications about imminent time limits, steps, errors, suggestions for correction, success messages, status changes, and feedback from user input
* identify related requirements for developers to provide the necessary semantics for components that accept user input, error messages, notifications, and other feedback
* identify related requirements for developers to code custom keyboard interactions for components that accept user input

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

### Topic: Form Design

{% include excol.html type="middle" %}

Refer back to [Designer Module 2: Information Design, Topic Labels and Instructions](/curricula/designer-modules/information-design/#topic-labels-and-instructions). Show examples of labels and instructions in the context of forms and other complex widgets.

Show examples of text and visual notifications for error messages and other types of feedback for forms and other custom widgets. Explain that notifications may have different levels of priority when in the context of a complex application. Defining such levels of priority and which types of notifications each of them should contain is a designers' responsibility.

Show examples of different ways to group large amounts of selectable data. For example, filtering out data into smaller pieces to better handle data, and enable mechanisms to type the first letters of their desire option to select data more efficiently.

#### Learning outcomes for Topic

Students should be able to:

* design user experiences that consider position, appearance, and naming for labels, instructions, and notifications
* define visual and non-visual instructions about which input fields are required by:
* define clear instructions about changes in context before the control that originates such changes
* define overall instructions about existing time limits in a form and about how they can be adjusted, extended, and turned off
* define clear instructions about the current step and about the total number of steps involved in a multi-step form
* define error messages in the page title or before the form control that
  * identify the fields in error
  * describe the cause of the error
  * provide suggestions to correct the error
* define meaningful and descriptive notification messages, for example:
  * on input (to communicate if the provided input is valid or invalid
  * on task completion (to communicate success or failure of a specific task)
* design user experiences to queue and prioritize application notifications coming from different components
* design user experiences to store and check notifications that disappear after a period of time at the users' pace
* identify related requirements for developers to code labels, instructions, and notifications appropriately

#### Teaching Ideas for Topic

Optional ideas to teach the learning outcomes:

* Show examples of different components that accept user input (such as buttons, links, lists, and grids) across rich applications or complex widgets. Emphasize that each should have a clear name that allows to identify its purpose. For reference on how to provide names for different user interface components, see technique [G197: Using labels, names, and text alternatives consistently for content that has the same functionality](https://www.w3.org/WAI/WCAG21/Techniques/general/G197).
* Demonstrate how labels for form fields are placed differently depending on the components, the language, and the user expectations. For example, labels for edit boxes are placed to the left of the field or above it in left-to-right languages, and to the right of the field or below it in right-to-left languages. Labels for radio buttons are placed to the right of the field or below it in left-to-right languages, or to the left of the field or above it in right-to-left languages.
* Show examples of required and non-required form fields. Explain that instructions for which of the fields is required should be provided using several mechanisms, including textual and visual cues.
* Present examples of time limits, such as those warning about session expirations. Explain that instructions need to be provided so that users are aware of the time limits, and mechanisms need to be implemented to stop, adjust, or extend time limits. Explain that defining and providing the instructions is a designers' responsibility, whereas implementing mechanisms to stop, extend, or adjust time limits is a responsibility shared with the developer.
* Show examples of multi-step forms. Explain that overall instructions should be provided about the current step in a form and about the total number of steps involved.

#### Ideas to Assess Knowledge for Topic

Optional ideas to assess knowledge:

* Practical &mdash; Present students with a form and ask them to define labels for each of the fields. Assess how students provide clear and descriptive names for each of the form fields.
* Practical &mdash; Give students an application and ask them to provide names for each of the application subsections. Assess how students identify application subsections and provide clear and understandable names for each.
* Practical &mdash; Give students a form and ask them to provide the necessary instructions for users to understand each of the fields and fill in the form. Assess how students provide clear and concise instructions.

{% include excol.html type="end" %}

{% include excol.html type="start" %}

### Topic: Keyboard Interactions

{% include excol.html type="middle" %}

Discuss standard keyboard interactions, such as the use of the tab, enter, escape, and arrow keys. Explain that providing custom keyboard interactions can favor efficiency, but can also disrupt the users' expectations, thus designers need to document these interactions and make them consistent throughout the interface.
Emphasize that defining the keyboard interactions is a designers' responsibility, whereas implementing them is a responsibility shared with the developer.

#### Learning Outcomes for Topic

Students should be able to:

* design user experiences for keyboard navigation through and inside custom components, for example:
  * using the tab key to move through different components
  * using the enter key to enter a specific component and to select a specific item on a component
  * using the arrow keys to move through elements inside components, such as application menus, dialogs, list items and grid cells
  * using the escape key to exit components
  * using first letter navigation to jump to specific pieces of data in lists and grids
  * specific keyboard shortcuts to support efficiency
* identify situations when it is necessary to provide additional keyboard shortcuts, for example when designing a custom functionality that is not keyboard supported by default
* design user experiences that avoid keyboard shortcut conflicts with the operating system, browser, and assistive technologies when possible
* cooperate with developers to provide mechanisms to remap or disable conflicting shortcuts
* define mechanisms to obtain information about custom keyboard shortcuts, for example those used to support efficiency and those used in custom widgets and complex applications
* define focus indicators that are visible and that have appropriate contrast ratios for complex widgets
* describe related requirements for developers to implement keyboard support for components that accept user input
  
#### Teaching Ideas for Topic

Optional ideas to teach the learning outcomes:

* Invite students to try standard keyboard conventions. For example, use of the tab to move through user interface components, use of the arrow keys to move through list items, and use of the enter key to select an item. Explain that these interactions need to be preserved as much as possible when designing custom widgets, as these are mostly expected by users.
* Reflect with students about keystrokes that are not part of standard keyboard interactions. For example, letter keys together with modifier keys to perform specific actions. Explain that designers need to work closely with other team members, including developers and user researchers, on strategies to define custom keyboard shortcuts. This includes researching commonly used keystrokes for complex interaction patterns, defining the keystrokes in the design phase, and working with developers to implement such keystrokes.
* Present examples of keyboard shortcuts that may conflict with browsers, operating systems, and assistive technologies. For example, modifier keys and single letter keys that are used by browsers and assistive technologies to provide built-in functionality. Explain that these keystrokes should be avoided when possible.
* Show examples of help functionality for custom keyboard shortcuts used in rich applications and in complex widgets. Explain that, while custom keyboard shortcuts are preferred by some users for efficiency reasons, using such shortcuts alone can distract others who may not be familiar with such keyboard shortcuts. Explain that providing these help mechanisms is a designers' responsibility, whereas implementing them is a responsibility shared with the developer.

#### Ideas to Assess Knowledge for Topic

Optional ideas to assess knowledge:

* Short Answer Questions &mdash; Students research about commonly used modifier keys of operating systems and assistive technologies. Assess how students understand the use of modifier keys in operating systems and assistive technologies.
* Practical &mdash; Present students with a user interface that can be interacted only with the mouse and ask them to define keyboard interaction patterns. Assess how students understand the need for alternatives to mouse input and how they use standard keyboard interactions when possible.
* Practical &mdash; Students work with developers to avoid custom keyboard shortcut conflicts with existing operating system and assistive technology keystrokes. Assess how students work with other team members to develop strategies that avoid custom keyboard shortcut conflicts.

{% include excol.html type="end" %}

{% include excol.html type="start" %}

### Topic: Gestures and Motion

{% include excol.html type="middle" %}

Show examples of user interfaces that react to motion, such as shaking the device to perform a specific action. Explain that some people may perform these motion-based gestures inadvertently, some others may not be able to perform them at all. Discuss some alternatives to motion-based gestures. 

Discuss some gestures that require dragging and drawing specific paths on a touch screen. Explain that these are difficult (and sometimes impossible) to perform for some people with mobility impairments.

#### Learning Outcomes for Topic

Students should be able to:

* use components that do not require motion as an alternative for device or user motion such as shaking
* design mechanisms to disable response to motion to prevent accidental actuation, such as undoing an action by shaking a device
* design alternatives to multi-pointer gestures (such as swipe or pinch) using single pointer activation
* design mechanisms to undoing or aborting an action carried out with path-based operations

#### Teaching Ideas for Topic

Optional ideas to teach the learning outcomes:

* Show examples of gestures that require motion, such as shaking the device, to perform an action. Explain that users with mobility impairments cannot perform such gestures, so user interfaces need to have alternatives that do not require motion for these gestures.
* Show examples of gestures such as swipe or pinch. Explain that users with mobility impairments cannot perform such gestures, so user interfaces need to have alternatives that do not require swiping or pinching to perform an action.
* Show examples of operations carried out using path-based  gestures, such as dragging. Explain that people with mobility impairments may inadvertently initiate touch or mouse events, so user interfaces need to support alternatives for people to perform actions associated with multi-pointer gestures or to undo actions carried out inadvertently with multi-pointer gestures.

#### Ideas to Assess Knowledge for Topic

Optional ideas to assess knowledge:

* Practical &mdash; Give students an interface that uses a motion-based gesture to perform an action and ask them to provide alternatives to that gesture. Assess how students provide alternatives to motion-based gestures.
* Practical &mdash; Give students an interface that uses a multi path-based gesture to perform an action and ask them to provide alternatives to that gesture. Assess how students provide alternatives to multi-pointer and path-based gestures.

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
