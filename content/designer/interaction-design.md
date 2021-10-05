---
title: "[Draft] Module 4: Interaction Design [WIP]"
nav_title: "Interaction Design"
permalink: /curricula/designer-modules/interaction-design/
ref: /curricula/designer-modules/interaction-design/
lang: en
github:
  repository: w3c/wai-curricula
  path: content/designer/interaction-design.md
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
  previous: /curricula/designer-modules/navigation-design/
  next: /curricula/designer-modules/images-and-graphics/
---

## Introduction
{:.no-display}

Courses based on this module should:

* demonstrate strategies that people with disabilities use to interact with components, including forms, links, buttons, controls, and widgets
* explain accessibility requirements related to input methods, including mouse, keyboard, touch, and voice

## Learning Outcomes for Module

Students should be able to:

* explain strategies that people with disabilities use to interact with components, including forms, links, buttons, controls, and widgets
* design user experiences for different input methods, including mouse, touch, keyboard, and speech
* define keyboard interactions and meaningful sequences inside complex widgets, including  sliders, tabs, and treeviews
* evaluate the use of custom keyboard shortcuts for complex widgets and applications and provide information about their purpose and scope
* define methods to disable device and user motion to prevent accidental actuation
* define alternatives for complex gestures, including swiping, pinching, and drawing shapes
* identify related requirements for developers to code interactions, including through mouse, keyboard, touch, and voice

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

### Topic: Keyboard Interaction

{% include excol.html type="middle" %}

Demonstrate standard keyboard interactions, for example the use of the tab, enter, escape, and arrow keys, versus specific non-standard shortcuts. Explain that providing custom keyboard interactions can favor efficiency but can also disrupt the users' expectations. Thus, designers need to document these custom interactions and make them consistent throughout the interface.  
Emphasize that defining the keyboard interactions is a designers' responsibility, whereas implementing such interactions is a responsibility shared with the developer.

#### Learning Outcomes for Topic

Students should be able to:

* design user experiences for keyboard navigation through and inside components, for example:
  * using the tab key to move through different components
  * using the enter key to enter a specific component and to select a specific item on a component
  * using the arrow keys to move through elements inside components, including application menus, dialogs, list items, and grid cells
  * using the escape key to exit components
  * using first letter navigation to jump to specific pieces of data in lists and grids
  * specific keyboard shortcuts to support efficiency
* identify situations when it is necessary to provide additional keyboard shortcuts, for example when designing a custom functionality that is not keyboard supported by default
* evaluate the use of custom keyboard interactions and select keyboard interactions that avoid conflicts with the operating system, browser, and assistive technologies when possible
* cooperate with developers to provide methods to remap or disable conflicting shortcuts
* define methods to obtain information about custom keyboard shortcuts, for example those used to support efficiency and those used in custom widgets and complex applications
* define focus indicators that are visible and that have appropriate contrast ratios for complex widgets
* identify related requirements for developers to implement keyboard support for components that have no keyboard support by default
  
#### Teaching Ideas for Topic

Optional ideas to teach the learning outcomes:

* Invite students to try standard keyboard conventions. For example, use of the tab to move through user interface components, use of the arrow keys to move through list items, and use of the enter key to select an item. Explain that these interactions need to be preserved as much as possible when designing custom widgets, as these are mostly expected by users.
* Reflect with students about keystrokes that are not part of standard keyboard interactions. For example, letter keys together with modifier keys to perform specific actions. Explain that designers need to work closely with other team members, including developers and user researchers, on strategies to define custom keyboard shortcuts. This includes researching commonly used keystrokes for complex interaction patterns, defining the keystrokes in the design phase, and working with developers to implement such keystrokes.
* Present examples of keyboard shortcuts that may conflict with browsers, operating systems, and assistive technologies. For example, modifier keys and single letter keys that are used by browsers and assistive technologies to provide built-in functionality. Explain that these keystrokes should be avoided when possible.
* Show examples of help functionality for custom keyboard shortcuts used in rich applications and in complex widgets. Explain that, while custom keyboard shortcuts are preferred by some users for efficiency reasons, using such shortcuts alone can distract others who may not be familiar with such keyboard shortcuts. Explain that providing these help methods is a designers' responsibility, whereas implementing them is a responsibility shared with the developer.

#### Ideas to Assess Knowledge for Topic

Optional ideas to assess knowledge:

* Short Answer Questions &mdash; Ask students about commonly used modifier keys of operating systems, browsers, and assistive technologies. Assess how students identify commonly used modifier keys in operating systems, browsers, and assistive technologies.
* Practical &mdash; Give students an interface that only works with the mouse and ask them to define keyboard interaction patterns. Assess how students understand the need for alternatives to mouse input and how they use standard keyboard interactions when possible.
* Practical &mdash; Students work with developers to avoid custom keyboard shortcut conflicts with existing operating system and assistive technology keystrokes. Assess how students work with developers to develop strategies that avoid custom keyboard shortcut conflicts.

{% include excol.html type="end" %}

{% include excol.html type="start" %}

### Topic: Gestures and Motion

{% include excol.html type="middle" %}

Show examples of user interfaces that react to motion, such as shaking the device to perform a specific action. Explain that some people may perform these motion-based gestures inadvertently, some others may not be able to perform them at all. Present some alternatives to motion-based gestures, for example providing methods to undo, abort, and reverse actions performed using complex gestures.

Discuss some gestures that require dragging and drawing specific paths on a touch screen. Explain that these are difficult (and sometimes impossible) to perform for some people with mobility impairments.

#### Learning Outcomes for Topic

Students should be able to:

* design alternatives to multi-pointer gestures (including swiping, pinching, and drawing shapes) by using single pointer activation
* design methods to undo or abort an action carried out with path-based gestures, including use of the up event to undo, abort, and reverse activation
* define alternatives for device or user motion, for example components performing the same function that do not require user motion 
* design methods to disable response to device or user motion to prevent accidental actuation

#### Teaching Ideas for Topic

Optional ideas to teach the learning outcomes:

* Show examples of gestures such as swipe or pinch. Explain that users with mobility impairments may have difficulty to perform such gestures, so user interfaces need to have alternatives that do not require swiping or pinching to perform an action.
* Show examples of gestures that require motion, such as shaking the device, to perform an action. Explain that users with mobility impairments may have difficulty to perform such gestures, so user interfaces need to have alternatives that do not require motion for these gestures.
* Show examples of operations carried out using path-based  gestures, such as dragging. Explain that people with mobility impairments may inadvertently initiate touch or mouse events, so user interfaces need to support alternatives for people to perform actions associated with multi-pointer gestures or to undo actions carried out inadvertently with multi-pointer gestures.

#### Ideas to Assess Knowledge for Topic

Optional ideas to assess knowledge:

* Practical &mdash; Students design an interface that can be used both in portrait and landscape modes. Assess how students understand the different ways of interacting with components.
* Practical &mdash; Give students an interface that uses a multi path-based gesture to perform an action and ask them to provide alternatives to that gesture. Assess how students provide alternatives to multi-pointer and path-based gestures.
* Practical &mdash; Give students an interface that uses a motion-based gesture to perform an action and ask them to provide alternatives to that gesture. Assess how students provide alternatives to motion-based gestures.

{% include excol.html type="end" %}

{% include excol.html type="all" %}

## Ideas to Assess Knowledge for Module

Optional ideas to assess knowledge:

* Practical &mdash: Give students a web application, such as a web email client, and ask them to provide the necessary custom keyboard shortcuts. Assess how students balance the use of standard versus custom keyboard shortcuts.
* Portfolio &mdash; Students design the interactions for a given interface, including mouse, keyboard, touch, and voice. Assess how students design user experiences for different input methods, including mouse, touch, keyboard, and speech.

## Teaching Resources

Suggested resources to support your teaching:

* [How People with Disabilities Use the Web](/people-use-web/) &mdash; Provides stories of people with disabilities using the Web; describes types of disabilities and some of the barriers that people encounter using the Web; and introduces types of assistive technologies and adaptive strategies that some people use.
* [Keyboard Compatibility (Web Accessibility Perspectives)](https://www.w3.org/WAI/perspective-videos/keyboard/) &mdash; Is one of the Web accessibility perspectives videos that show accessibility features and how they impact people with disabilities.
* [Colors with Good Contrast (Web Accessibility Perspective)](/perspective-videos/contrast/) &mdash; Is one of the Web accessibility perspectives videos that show accessibility features and how they impact people with disabilities.
* [Clear Layout and Design (Web Accessibility Perspective)](/perspective-videos/layout/) &mdash; Is one of the Web accessibility perspectives videos that show accessibility features and how they impact people with disabilities.
* [Large Links, Buttons, and Controls (Web Accessibility Perspectives)](/perspective-videos/controls/) &mdash; Is one of the Web accessibility perspectives videos that show accessibility features and how they impact people with disabilities.
* [Notifications and Feedback (Web Accessibility Perspectives)](https://www.w3.org/WAI/perspective-videos/notifications/) &mdash; Is one of the Web accessibility perspectives videos that show accessibility features and how they impact people with disabilities.
* [WCAG](https://www.w3.org/WAI/standards-guidelines/wcag/) &mdash; Address accessibility of web content on desktops, laptops, tablets, and mobile devices.
