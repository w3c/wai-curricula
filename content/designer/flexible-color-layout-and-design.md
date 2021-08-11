---
title: "[Draft] Module 1: Flexible Color, Layout, and Design"
nav_title: "Flexible Color, Layout, and Design"
permalink: /curricula/designer-modules/flexible-color-layout-and-design/
ref: /curricula/designer-modules/flexible-color-layout-and-design/
lang: en
github:
  repository: w3c/wai-curricula
  path: content/designer/flexible-colorlayout-and-design.md
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

* explain accessibility requirements for user that can have customized colors, size, and spacing between components
* explain how people with disabilities rely on designs that adapt to different screen sizes, configurations, and style sheets
 
## Learning Outcomes for Module

Students should be able to:

* explain how people with disabilities rely on designs that adapt to different colors, layouts, spacing, and positions
* design layouts with sufficient color contrast for text, images of text, and controls
* use headings, landmarks, text cues, patterns, and icons to supplement information conveyed through color
* design clear and distinguishable focus indicators, for example using borders, color, and highlighting
* design layouts that adapt to different font sizes and spacing set by the user in browser and operating system settings
* position components where users expect them
* identify related requirements for developers to apply the necessary semantics to user interface components

{% include excol.html type="all" %}

## Competencies

Skills required for this module:

{% include excol.html type="start" %}

### Students

{% include excol.html type="middle" %}

* [Foundation Prerequisites](/curricula/designer-modules#foundation-prerequisites)
* Basic knowledge of:
  * Visual Design
  * Prototyping
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
  * [Foundation Prerequisites](/curricula/designer-modules#foundation-prerequisites)
  * Visual Design
  * Prototyping
  * Responsive Design

{% include excol.html type="end" %}

## Topics to Teach

Topics to achieve the learning outcomes:

{% include excol.html type="start" %}

### Topic: Color

{% include excol.html type="middle" %}

Describe how some people use color to understand and distinguish content. Explain different ways to supplement information that is presented using color, such as using shapes and icons. 
Explain how sufficient color contrast (contrast ratios in WCAG) are essential for people with low vision to perceive, distinguish, and understand content.

#### Learning Outcomes for Topic

Students should be able to:

* explain how appropriate use of color enables people with disabilities to read, understand, and distinguish user interface components
* design text and images of text that have a contrast ratio of at least 4.5:1 with respect to their background
* design large-scale text and images of text that have a contrast ratio of at least 3:1 with respect to their background
* design components and graphics that have a contrast ratio of at least 3:1 with respect to their background
* use visual cues in addition to color, for example using different patterns, shapes, and icons
* use non-visual cues for people who do not perceive color, for example using text to complement information provided visually

#### Teaching Ideas for Topic

Optional ideas to teach the learning outcomes:

* Show examples of how different pieces of text are perceived depending on their background color. Explain that contrast ratios for text (including images of text) need to be at least 4.5:1 with respect to their background. For references on how to apply contrast ratios to text (including images of text), see technique [G18: Ensuring that a contrast ratio of at least 4.5:1 exists between text (and images of text) and background behind the text](https://www.w3.org/WAI/WCAG21/Techniques/general/G18.html).
* Show examples of different interactive components, such as buttons and links, and explain that they should have a contrast ratio of at least 3:1.
* Show examples of interfaces where information is conveyed exclusively with differences in color, such as a form where required fields are marked in red. Explain that some users cannot perceive color well or at all, so supplemental methods to convey that information are required. For references on how to supplement information conveyed through color, see technique [G182: Ensuring that additional visual cues are available when text color differences are used to convey information](https://www.w3.org/WAI/WCAG21/Techniques/general/G182.html).

#### Ideas to Assess Knowledge for Topic

Optional ideas to assess knowledge:

* Short Answer Questions &mdash; Give students a set of user interface components and ask them what the contrast ratio should be. Assess how students understand and distinguish contrast ratios for different user interface components.
* Practical &mdash; Students design a paper prototype and apply appropriate contrast ratios to text, images of text, user interface components, and graphics. Assess how students understand and apply contrast ratios based on the different user interface components that they are designing.
* Practical &mdash; Give students information presented using color and ask them to supplement that information using other visual cues. Assess how students use shapes and icons to supplement information presented using color distinguishable.

{% include excol.html type="end" %}

{% include excol.html type="start" %}

### Topic: Styles

{% include excol.html type="middle" %}

Explain how people with disabilities rely on different style properties, such as font types, sizes, and spacing, to support readability.

#### Learning Outcomes for Topic

Students should be able to:

* use clear and distinguishable styles for links, buttons, form elements, and text
* define customizable font types to support content readability
* define customizable font sizes to support readability
* define adequate spacing to support readability
* define customizable colors to support readability

#### Teaching Ideas for Topic

Optional ideas to teach the learning outcomes:

* Demonstrate the use of styles to distinguish user interface components, such as links, buttons, form labels and instructions, and text. Explain how people rely on font types, font sizes, spacing, and color to distinguish components.
* Show examples of usable font sizes and explain how they support readability. Contrast previous examples with fonts that are not as easy to read. Emphasize that several user groups rely on customizable fonts to be able to read and understand content properly.
* Show examples of different page layouts with and without adequate spacing. Explain how spacing allows for better readability of content and for better identification of the different parts of the user interface.

#### Ideas to Assess Knowledge for Topic

Optional ideas to assess knowledge:

* Practical &mdash; Students design a prototype with adaptable and distinguishable styles that help users perceive different content. Assess how students use different style properties such as font sizes and spacing to make content perceivable and to distinguish components from one another.

{% include excol.html type="end" %}

{% include excol.html type="start" %}

### Topic: Landmarks and Cues

{% include excol.html type="middle" %}

Explain how people with disabilities perceive different web page regions and content through text and visual landmarks and cues. Present different strategies to include such cues early in the design phase.

#### Learning Outcomes for Topic

Students should be able to:

* define page regions by using appropriate visual and programmatic landmarks, such as headings
* use text cues to supplement information provided through vision only, for example to convey required form fields represented with an icon and available dates in a calendar represented with a different background color
* design focus indicators that enable people to tell where they are as they move through web pages and applications using the keyboard

#### Teaching Ideas for Topic

Optional ideas to teach the learning outcomes:

* Show examples of different regions of web pages, such as header, navigation, main, and footer. Explain that several groups of people with disabilities rely on visual and programmatic landmarks to perceive such regions. Explain that defining landmarks and their styles is a designers' responsibility, whereas implementing such landmarks and their semantics is a developers' responsibility.
* Show examples of interfaces where information is provided through vision only, such as those with icons to convey when a form field is required and those with colors to convey available dates in a calendar. Explain that some people cannot rely on visual means to obtain information, so text is needed for them to understand the information provided. For references on how to complement information presented visually with text, see technique [G96: Providing textual identification of items that otherwise rely only on sensory information to be understood](https://www.w3.org/WAI/WCAG21/Techniques/general/G96.html).
* Invite students to use a web page that has appropriate focus indicators first, and then invite them to use a web page without focus indicators. Explain how focus indicators allow people using the keyboard only to determine where they are as they move through web pages and applications using the keyboard only. For reference on how to provide appropriate focus indicators, see techniques [G149: Using user interface components that are highlighted by the user agent when they receive focus](https://www.w3.org/WAI/WCAG21/Techniques/general/G149.html) and [G195: Using an author-supplied, highly visible focus indicator](https://www.w3.org/WAI/WCAG21/Techniques/general/G195.html).

#### Ideas to Assess Knowledge for Topic

Optional ideas to assess knowledge:

* Practical &mdash; Give students a web page and ask them to define the appropriate landmarks and their styling for users to perceive such regions. Assess how students provide mechanisms to perceive such regions.
* Practical &mdash: Give students examples of information conveyed visually and ask them to provide text information to help understand the information. Assess how students provide the necessary textual information and visual cues to supplement information.

{% include excol.html type="end" %}

{% include excol.html type="start" %}

### Topic: Flexible Design

{% include excol.html type="middle" %}

Explain how people with disabilities use different screen sizes, screen configurations, and style sheets to identify, distinguish, and process content.

#### Learning Outcomes for Topic

Students should be able to:

* design layouts that support text resizing without loss of content and functionality
* design layouts that support zooming and enlarging text in different viewport sizes and through multiple breakpoints
* design layouts that support content view and operation in both portrait and landscape orientations
* design layouts with target sizes and spaces to support tapping by people with mobility impairments and people using different input methods
* design layouts that support customizing line height, as well as spacing between paragraphs, words, and letters
* design user interfaces that preserve focus order when accessed using different viewport, screen sizes, and breakpoints

#### Teaching Ideas for Topic

Optional ideas to teach the learning outcomes:

* Explain that people with low vision often need to resize text to read it properly. Discuss with students the differences between web sites and applications that preserve content and functionality when resized up to 200% and those which do not. For references on how to ensure text resizes up to 200%, see technique [G179: Ensuring that there is no loss of content or functionality when the text resizes and text containers do not change their width](https://www.w3.org/WAI/WCAG21/Techniques/general/G179).
* Discuss the use of multiple screen sizes, screen configurations, and style sheets by people with low vision. Explain that these configurations often go beyond the traditional mobile, tablet, and desktop breakpoints.
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

* Portfolio &mdash; Students design a web page. Assess how students use customizable color, layout, spacing, and position to support content perception, identification, and readability.

## Teaching Resources

Suggested resources to support your teaching:

* [Designing for Web Accessibility](/tips/designing/) &mdash; Tips for user interface and visual design.
* [[How People with Disabilities Use the Web]](/people-use-web/) &mdash; Describes some of the barriers that people encounter using the Web; and introduces types of assistive technologies and adaptive strategies that some people use.
* [Keyboard Compatibility (Web Accessibility Perspective)](/perspective-videos/keyboard/) &mdash; Is one of the Web accessibility perspectives videos that show accessibility features and how they impact people with disabilities.
* [Colors with Good Contrast (Web Accessibility Perspective)](/perspective-videos/contrast/) &mdash; Is one of the Web accessibility perspectives videos that show accessibility features and how they impact people with disabilities.
* [Clear Layout and Design (Web Accessibility Perspective)](/perspective-videos/layout/) &mdash; Is one of the Web accessibility perspectives videos that show accessibility features and how they impact people with disabilities.
* [Customizable Text (Web Accessibility Perspective)](/perspective-videos/customizable/) &mdash; Is one of the Web accessibility perspectives videos that show accessibility features and how they impact people with disabilities.
* [WCAG](https://www.w3.org/WAI/standards-guidelines/wcag/) &mdash; Address accessibility of web content on desktops, laptops, tablets, and mobile devices.
