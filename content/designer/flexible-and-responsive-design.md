---
title: "[Draft] Module 2: Flexible and Responsive Design"
nav_title: "Flexible and Responsive Design"
permalink: /curricula/designer-modules/flexible-and-responsive-design/
ref: /curricula/designer-modules/flexible-and-responsive-design/
lang: en
github:
  repository: w3c/wai-curricula
  path: content/designer/flexible-and-responsive-design.md
license: creative-commons
acknowledgements: /curricula/acknowledgements/
changelog: /curricula/changelog/
footer: >
  <p><strong>Date:</strong> Updated @@ Month 2021. First published December 2019.</p>
  <p><strong>Editors:</strong> Daniel Montalvo and <a href="http://www.w3.org/People/shadi/">Shadi Abou-Zahra</a>. Contributors: <a href="https://www.w3.org/WAI/EO/EOWG-members">EOWG Participants</a>. ACKNOWLEDGEMENTS lists contributors and credits.</p>
  <p>Developed by the Education and Outreach Working Group (<a href="http://www.w3.org/WAI/EO/">EOWG</a>). Developed with support from the <a href="https://www.w3.org/WAI/about/projects/wai-guide/">WAI-Guide Project</a> funded by the European Commission (EC) under the Horizon 2020 program (Grant Agreement 822245).</p>
parent_in_h1:
  - ref: /curricula/designer-modules/
    name: nav_title
  - ref: /curricula/
    name: "Curricula on Web Accessibility"
navigation:
  previous: /curricula/designer-modules/understanding-and-involving-users/
  next: /curricula/designer-modules/navigation/
---

## Introduction
{:.no-display}

Courses based on this module should:

* explain how people with disabilities use different screen sizes, screen configurations, break points, and style sheets to identify, distinguish, and process contents
* explain accessibility requirements that relate to color, layout, spacing, and position

## Learning Outcomes for Module

Students should be able to:

* explain how people with disabilities identify and distinguish user interface components based on different features, such as color, layout, spacing, and position
* design user interfaces with headings, landmarks, text cues, patterns, and icons to supplement information conveyed through color alone
* design user interfaces with adjustable font sizes and adequate spacing to support readability
* design user interfaces with appropriate contrast ratios for text, images of text, and controls
* design user interfaces with clear and distinguishable focus indicators, for example using borders, background color, and highlighting
* design user interfaces that support placement of different regions and user interface components where users expect them
* identify related requirements for developers to apply the necessary semantics to user interface components

{% include excol.html type="all" %}

## Competencies

Skills required for this module:

{% include excol.html type="start" %}

### Students

{% include excol.html type="middle" %}

* [Prerequisites for students](/curricula/designer-modules#prerequisites-for-students)

{% include excol.html type="end" %}

{% include excol.html type="start" %}

### Instructors

{% include excol.html type="middle" %}

* In-depth knowledge of:
  * [Prerequisites for students](/curricula/designer-modules#prerequisites-for-students)
* Applied expertise in teaching:
  * [WCAG Success Criterion 1.1.1	Non-text Content](https://www.w3.org/WAI/WCAG21/quickref/#time-based-media)
  * [WCAG Success Criterion 1.3.1 Info and Relationships](https://www.w3.org/WAI/WCAG21/quickref/#info-and-relationships)
  * [WCAG Success Criterion 1.3.2 Meaningful Sequence](https://www.w3.org/WAI/WCAG21/quickref/#meaningful-sequence)
  * [WCAG Success Criterion 1.3.3 Sensory Characteristics](https://www.w3.org/WAI/WCAG21/quickref/#sensory-characteristics)
  * [WCAG Success Criterion 1.3.4 Orientation](https://www.w3.org/WAI/WCAG21/quickref/#orientation)
  * [WCAG Success Criterion 1.4.1 Use of Color](https://www.w3.org/WAI/WCAG21/quickref/#use-of-color)
  * [WCAG Success Criterion 1.4.3 Contrast (Minimum)](https://www.w3.org/WAI/WCAG21/quickref/#contrast-minimum)
  * [WCAG Success Criterion 1.4.4 Resize Text](https://www.w3.org/WAI/WCAG21/quickref/#resize-text)
  * [WCAG Success Criterion 1.4.6 Contrast (Enhanced)](https://www.w3.org/WAI/WCAG21/quickref/#contrast-enhanced)
  * [WCAG Success Criterion 1.4.10 Reflow](https://www.w3.org/WAI/WCAG21/quickref/#reflow)
  * [WCAG Success Criterion 1.4.11 Non-Text Contrast](https://www.w3.org/WAI/WCAG21/quickref/#non-text-contrast)
  * [WCAG Success Criterion 1.4.12 Text Spacing](https://www.w3.org/WAI/WCAG21/quickref/#text-spacing)
  * [WCAG Success Criterion 2.4.2 Page Titled](https://www.w3.org/WAI/WCAG21/quickref/#page-titled)
  * [WCAG Success Criterion 2.4.3 Focus Order](https://www.w3.org/WAI/WCAG21/quickref/#focus-order)
  * [WCAG Success Criterion 2.4.6 Headings and Labels](https://www.w3.org/WAI/WCAG21/quickref/#headings-and-labels)
  * [WCAG Success Criterion 2.4.7 Focus Visible](https://www.w3.org/WAI/WCAG21/quickref/#focus-visible)

{% include excol.html type="end" %}

## Topics to Teach

Topics to achieve the learning outcomes:

{% include excol.html type="start" %}

### Topic: Content Perception

{% include excol.html type="middle" %}

Explain how people with disabilities rely on different style properties, such as font sizes and spacing, to perceive contents.

#### Learning Outcomes for Topic

Students should be able to:

* design user interfaces with clear and distinguishable styles for different components, such as links, buttons, form elements, or texts
* design user interfaces with font sizes that allow content readability
* design user interfaces with adequate spacing to support readability
* design user interfaces with text cues to convey information provided through vision only, such as an asterisk to convey required form fields in a form
* design user interfaces with other visual cues in addition to color, for example using different patterns, shapes, and icons

#### Teaching Ideas for Topic

Optional ideas to teach the learning outcomes:

* Demonstrate the use of styles for distinguishing user interface components from one another, such as links, buttons, form elements, and texts. Explain how people rely on font sizes, spacing, and typography to distinguish components from one another. For references on how to apply distinguishable styles for user interface components, see @@@
* Demonstrate use of different font sizes and explain how they affect readability of the content. For reference on how to apply font sizes that allow content readability, see @@@
* Show examples of different page layouts with and without adequate spacing. Explain how spacing allows to distinguish different pieces of content from one another. For references on how to apply adequate spacing, see @@@
* Show examples of interfaces where information is provided through vision only, such as those with icons to convey when a store is open or closed. Explain that some people cannot rely on visual means to obtain information, so text is needed for them to understand the information provided. 
* Show examples of interfaces where information is conveyed exclusively with differences in color, such as a form where required fields are marked in red. Explain that some users cannot perceive color well or at all, so alternative methods to convey that information are required. For references on how to convey information without using color alone, see @@@

#### Ideas to Assess Knowledge for Topic

Optional ideas to support assessment:

* Practical &mdash; Students design a paper prototype with distinguishable styles that help perceive different contents. Assess how students use different style properties to make content perceivable and to distinguish contents from one another.
* Practical &mdash: Give students examples of color alone used to provide information and ask them to provide text information and visual cues to supplement that information. Assess how students provide the necessary textual information and visual cues to supplement information provided exclusively with color.

{% include excol.html type="end" %}

{% include excol.html type="start" %}

### Topic: Contrast Ratios

{% include excol.html type="middle" %}

Explain how contrast ratios are essential for people with low vision to perceive, distinguish, and understand contents.

#### Learning Outcomes for Topic

Students should be able to:
 
* explain how appropriate contrast ratios allow people with disabilities to read, understand, and distinguish user interface components
* design user interfaces with texts and images of text that have a contrast ratio of at least 4.5:1 with respect to their background
* design user interfaces with large-scale text and images of text that have a contrast ratio of at least 3:1 with respect to their background
* design user interfaces with components and graphics that have a contrast ratio of at least 3:1 with respect to their background

#### Teaching Ideas for Topic

Optional ideas to teach the learning outcomes:

* Show examples of different foreground and background color combinations. Explain how contrast ratios between foreground and background allow users to perceive content and distinguish components from one another. For references on contrast ratios , see @@@
* Show examples of how different pieces of text are perceived depending on their background color. Explain that contrast ratios need to be at least 4.5:1. For references on how to apply contrast ratios to text (including images of text), see @@@
* Show examples of different interactive components, such as buttons and links, and explain that they should have a contrast ratio of at least 3:1. For techniques on how to add contrast ratios for graphics and interface components, see@@@

#### Ideas to Assess Knowledge for Topic

Optional ideas to support assessment:

* Short Answer Questions &mdash; Give students a set of user interface components and ask them what the contrast ratio should be. Assess how students understand and distinguish contrast ratios for different user interface components.
* Practical &mdash; Students design a paper prototype and apply appropriate contrast ratios to text, images of text, user interface components and graphics. Assess how students understand and apply contrast ratios based on the different user interface components that they are designing

{% include excol.html type="end" %}

{% include excol.html type="start" %}

### Topic: Flexible Design

{% include excol.html type="middle" %}

Explain how people with disabilities use different screen sizes, screen configurations, break points, and style sheets to identify, distinguish, and process contents.

#### Learning Outcomes for Topic

Students should be able to:

* design user interfaces that support customizing line height, as well as spacing between paragraphs, words, and letters
* design user interfaces that support text resizing without loss of content and functionality
* design user interfaces that support content view and operation in both portrait and landscape orientations
* design user interfaces with target sizes and spaces to support tapping by people with mobility impairments and people using different input methods

#### Teaching Ideas for Topic

Optional ideas to teach the learning outcomes:

* Show examples of different user interfaces that support customizing line height as well as spacing between paragraphs, words, and letters to support readability.
* Explain that people with low vision often need to resize text to be able to read it properly. This includes resizing settings in the assistive technology, browser, and operating system.
* Show examples of user interfaces showing up in both portrait and landscape modes. Explain that the ability to show an interface both in portrait and landscape is crucial for people who cannot change their device orientation due to mobility impairments.
* Show examples of different tap targets, and explain that some people have difficulty to tap smaller targets due to mobility impairments.  Explain that tap targets need to be large enough to accommodate different people's needs.

#### Ideas to Assess Knowledge for Topic

Optional ideas to support assessment:

* Practice &mdash; Students design different paper prototypes with different interface layouts considering text resizing, line height, spacing between paragraphs, words, and letters. Assess how students consider text resizing, line height, and spacing between paragraphs, words, and letters while designing user interfaces.

{% include excol.html type="end" %}

{% include excol.html type="all" %}

## Ideas to Assess Knowledge for Module

Optional ideas to support assessment:

* Portfolio &mdash; Students design a prototype of a single web page. Assess how students use color, layout, spacing, and position to support content perception and identification.

## Teaching Resources

Suggested resources to support your teaching:

* @@@
* [WCAG](https://www.w3.org/WAI/standards-guidelines/wcag/) &mdash; Address accessibility of web content on desktops, laptops, tablets, and mobile devices.