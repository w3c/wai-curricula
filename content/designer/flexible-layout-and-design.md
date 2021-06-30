---
title: "[Draft] Module 1: Flexible Layout and Design"
nav_title: "Flexible Layout and Design"
permalink: /curricula/designer-modules/flexible-layout-and-design/
ref: /curricula/designer-modules/flexible-layout-and-design/
lang: en
github:
  repository: w3c/wai-curricula
  path: content/designer/flexible-layout-and-design.md
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
  previous: /curricula/designer-modules/
  next: /curricula/designer-modules/navigation/
---

## Introduction
{:.no-display}

Courses based on this module should:

* explain how people with disabilities use different screen sizes, screen configurations, breakpoints, and style sheets to identify, distinguish, and process contents
* explain accessibility requirements for user interface components that relate to color, layout, spacing, and position

## Learning Outcomes for Module

Students should be able to:

* explain how people with disabilities identify and distinguish user interface components based on different features, such as color, layout, spacing, and position
* design user interfaces with headings, landmarks, text cues, patterns, and icons to supplement information conveyed through color alone
* design user interfaces with adjustable font sizes and adequate spacing to support readability
* design user interfaces with appropriate contrast ratios for text, images of text, and controls
* design user interfaces with clear and distinguishable focus indicators, for example using borders, background color, and highlighting
* design user interfaces that support positioning different regions and user interface components where users expect them
* identify related requirements for developers to apply the necessary semantics to user interface components

{% include excol.html type="all" %}

## Competencies

Skills required for this module:

{% include excol.html type="start" %}

### Students

{% include excol.html type="middle" %}

* [Prerequisites for students](/curricula/designer-modules#prerequisites-for-students)
* Basic knowledge of:
  * Visual Design
  * Prototype Design
  * Responsive Design

{% include excol.html type="end" %}

{% include excol.html type="start" %}

### Instructors

{% include excol.html type="middle" %}

* Applied expertise in teaching:
  * [WCAG Success Criterion 1.1.1	Non-text Content](https://www.w3.org/WAI/WCAG21/quickref/#non-text-content)
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
  * [WCAG Success Criterion 2.4.3 Focus Order](https://www.w3.org/WAI/WCAG21/quickref/#focus-order)
  * [WCAG Success Criterion 2.4.6 Headings and Labels](https://www.w3.org/WAI/WCAG21/quickref/#headings-and-labels)
  * [WCAG Success Criterion 2.4.7 Focus Visible](https://www.w3.org/WAI/WCAG21/quickref/#focus-visible)
* In-depth knowledge of:
  * [Prerequisites for students](/curricula/designer-modules#prerequisites-for-students)
  * Visual Design
  * Prototype Design
  * Responsive Design

{% include excol.html type="end" %}

## Topics to Teach

Topics to achieve the learning outcomes:

{% include excol.html type="start" %}

### Topic: Text Styling

{% include excol.html type="middle" %}

Explain how people with disabilities rely on different style properties, such as font sizes and spacing, to perceive contents.

#### Learning Outcomes for Topic

Students should be able to:

* design user interfaces with clear and distinguishable styles for different components, such as links, buttons, form elements, or texts
* design user interfaces with font sizes that enhance content readability
* design user interfaces with adequate spacing to support readability and to help distinguish components from one another

#### Teaching Ideas for Topic

Optional ideas to teach the learning outcomes:

* Demonstrate the use of styles to distinguish user interface components from one another, such as links, buttons, form elements, and texts. Explain how people rely on font sizes, spacing, and typography to distinguish components from one another.
* Demonstrate the use of different font sizes and explain how they affect readability of the content.
* Show examples of different page layouts with and without adequate spacing. Explain how spacing allows to distinguish different user interface components and pieces of content from one another. Emphasize that spacing also allows for better readability of contents and for better identification of the different parts of the user interface.

#### Ideas to Assess Knowledge for Topic

Optional ideas to assess knowledge:

* Practical &mdash; Students design a prototype with distinguishable styles that help perceive different contents. Assess how students use different style properties such as font sizes and spacing to make content perceivable and to distinguish components from one another.

{% include excol.html type="end" %}

{% include excol.html type="start" %}

### Topic: Landmarks and Cues

{% include excol.html type="middle" %}

Discuss strategies to provide mechanisms for users to perceive different web page regions. Present different strategies to supplement various content types using visual and textual cues.

#### Learning Outcomes for Topic

Students should be able to:

* define page regions by using appropriate visual and programmatic landmarks
* design user interfaces with text cues to convey information provided through vision only, for example to convey required form fields
* design user interfaces with focus indicators that enable people to tell where they are as they move through web pages and applications using the keyboard

#### Teaching Ideas for Topic

Optional ideas to teach the learning outcomes:

* Show examples of different regions of web pages, such as header, navigation, main, and footer. Explain that the use of landmarks is needed for people to perceive such regions. Explain that defining landmarks is a designers' responsibility, whereas implementing such landmarks is a responsibility shared with the developer.
* Show examples of interfaces where information is provided through vision only, such as those with icons to convey when a form field is required. Explain that some people cannot rely on visual means to obtain information, so text is needed for them to understand the information provided. For references on how to complement information presented visually with text, see technique [G96: Providing textual identification of items that otherwise rely only on sensory information to be understood](https://www.w3.org/WAI/WCAG21/Techniques/general/G96.html).
* Invite students to navigate a web page with appropriate focus indicators first, and then invite them to navigate a web page without focus indicators. Explain how focus indicators allow people using the keyboard only to determine where they are as they move through web pages and applications using the keyboard only. For reference on how to provide appropriate focus indicators, see techniques [G149: Using user interface components that are highlighted by the user agent when they receive focus](https://www.w3.org/WAI/WCAG21/Techniques/general/G149.html) and [G195: Using an author-supplied, highly visible focus indicator](https://www.w3.org/WAI/WCAG21/Techniques/general/G195.html).

#### Ideas to Assess Knowledge for Topic

Optional ideas to assess knowledge:

* Practical &mdash; Give students a web page and ask them to define the appropriate landmarks for users to perceive such regions. Assess how students provide mechanisms to perceive such regions.
* Practical &mdash: Give students examples of required form fields and ask them to provide text information and visual cues to indicate that they are required. Assess how students provide the necessary textual information and visual cues to supplement information.

{% include excol.html type="end" %}

{% include excol.html type="start" %}

### Topic: Color

{% include excol.html type="middle" %}

Describe how some people use color to understand and distinguish contents. Explain different ways to convey information that is presented using color alone, such as shapes and icons. 
Explain how contrast ratios are essential for people with low vision to perceive, distinguish, and understand contents.

#### Learning Outcomes for Topic

Students should be able to:

* explain how appropriate use of color enables people with disabilities to read, understand, and distinguish user interface components
* design user interfaces with other visual cues in addition to color, for example using different patterns, shapes, and icons
* design user interfaces with texts and images of text that have a contrast ratio of at least 4.5:1 with respect to their background
* design user interfaces with large-scale text and images of text that have a contrast ratio of at least 3:1 with respect to their background
* design user interfaces with components and graphics that have a contrast ratio of at least 3:1 with respect to their background

#### Teaching Ideas for Topic

Optional ideas to teach the learning outcomes:

* Show examples of interfaces where information is conveyed exclusively with differences in color, such as a form where required fields are marked in red. Explain that some users cannot perceive color well or at all, so alternative methods to convey that information are required. For references on how to convey information without using color alone, see technique [G182: Ensuring that additional visual cues are available when text color differences are used to convey information](https://www.w3.org/WAI/WCAG21/Techniques/general/G182.html).
* Show examples of how different pieces of text are perceived depending on their background color. Explain that contrast ratios for text (including images of text) need to be at least 4.5:1 with respect to their background. For references on how to apply contrast ratios to text (including images of text), see technique [G18: Ensuring that a contrast ratio of at least 4.5:1 exists between text (and images of text) and background behind the text](https://www.w3.org/WAI/WCAG21/Techniques/general/G18.html).
* Show examples of different interactive components, such as buttons and links, and explain that they should have a contrast ratio of at least 3:1.

#### Ideas to Assess Knowledge for Topic

Optional ideas to assess knowledge:

* Short Answer Questions &mdash; Give students a set of user interface components and ask them what the contrast ratio should be. Assess how students understand and distinguish contrast ratios for different user interface components.
* Practical &mdash; Students design a paper prototype and apply appropriate contrast ratios to text, images of text, user interface components, and graphics. Assess how students understand and apply contrast ratios based on the different user interface components that they are designing.
* Practical &mdash; Give students information presented using color alone and ask them to provide alternatives to convey such information. Assess how students use shapes and icons to make information presented using color alone distinguishable.

{% include excol.html type="end" %}

{% include excol.html type="start" %}

### Topic: Flexible Design

{% include excol.html type="middle" %}

Explain how people with disabilities use different screen sizes, screen configurations, breakpoints, and style sheets to identify, distinguish, and process contents.

#### Learning Outcomes for Topic

Students should be able to:

* design user interfaces that support text resizing without loss of content and functionality
* design user interfaces that support zooming and enlarging text in different viewport sizes and through multiple breakpoints
* design user interfaces that support content view and operation in both portrait and landscape orientations
* design user interfaces with target sizes and spaces to support tapping by people with mobility impairments and people using different input methods
* design user interfaces that support customizing line height, as well as spacing between paragraphs, words, and letters
* design user interfaces that preserve focus order when accessed using different viewport, screen sizes, and breakpoints

#### Teaching Ideas for Topic

Optional ideas to teach the learning outcomes:

* Discuss with students the differences between web sites and applications that preserve content and functionality when resized up to 200% and those which do not. Explain that people with low vision often need to resize text to read it properly. For references on how to ensure text resizes up to 200%, see technique [G179: Ensuring that there is no loss of content or functionality when the text resizes and text containers do not change their width](https://www.w3.org/WAI/WCAG21/Techniques/general/G179).
* Discuss the use of multiple breakpoints by people with low vision. Explain that these breakpoints often go beyond the traditional mobile, tablet, and desktop breakpoints.
* Show examples of user interfaces showing up in both portrait and landscape modes. Explain that the ability to show an interface both in portrait and landscape is important for people who cannot change their device orientation due to mobility impairments.
* Show examples of different tap targets and explain that some people have difficulty to tap smaller targets due to mobility impairments. Explain that tap targets need to be large enough to accommodate different people's needs.
* Show examples of different user interfaces that support customizing line height as well as spacing between paragraphs, words, and letters to support readability.

#### Ideas to Assess Knowledge for Topic

Optional ideas to assess knowledge:

* Practical &mdash; Students design different paper prototypes with different interface layouts considering text resizing, line height, spacing between paragraphs, words, and letters. Assess how students consider text resizing, line height, and spacing between paragraphs, words, and letters.

{% include excol.html type="end" %}

{% include excol.html type="all" %}

## Ideas to Assess Knowledge for Module

Optional ideas to assess knowledge:

* Portfolio &mdash; Students design a web page. Assess how students use color, layout, spacing, and position to support content perception and identification.

## Teaching Resources

Suggested resources to support your teaching:

* [[How People with Disabilities Use the Web]](/people-use-web/) &mdash; Describes some of the barriers that people encounter using the Web; and introduces types of assistive technologies and adaptive strategies that some people use.
* [WCAG](https://www.w3.org/WAI/standards-guidelines/wcag/) &mdash; Address accessibility of web content on desktops, laptops, tablets, and mobile devices.
