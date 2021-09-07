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

## Learning Outcomes for Module

Students should be able to:

* demonstrate how people with disabilities rely on form structures, labels, instructions, and notifications to understand and interact with forms
* define clear and distinguishable ways to identify form fields and other components that accept user input, including through naming and placement
* define textual instructions, color, and other visual cues to help understand the context, information, and functionality of user interface components
* define meaningful and descriptive notifications about imminent time limits, steps, errors, suggestions for correction, success messages, status changes, and feedback from user input

{% include excol.html type="all" %}

{% include excol.html type="start" %}


### Topic: Naming, Grouping, and Placement

{% include excol.html type="middle" %}

Refer back to [Designer Module 2: Information Design, Topic Labels and Instructions](/curricula/designer-modules/information-design/#topic-labels-and-instructions). Show examples of labels and instructions in the context of forms and other complex widgets.

Show examples of different ways to group large amounts of selectable data. For example, filtering out data into smaller pieces to better handle data, and enable mechanisms to type the first letters of their desired option to select data more efficiently.

#### Learning outcomes for Topic

Students should be able to:

* design user experiences that consider position, appearance, and naming for labels andinstructions
* define visual and non-visual instructions about which input fields are required
* define clear instructions about changes in context before the control that originates such changes
* define overall instructions about existing time limits in a form and about how to adjust them, extend them, and turn them off
* define clear instructions about the current step and about the total number of steps involved in a multi-step form
* define error messages in the page title or before the form control that:
  * identify the fields in error
  * describe the cause of the error
  * provide suggestions to correct the error
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