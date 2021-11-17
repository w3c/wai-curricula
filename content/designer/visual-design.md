---
title: "[Draft] Module 1: Visual Design"
nav_title: "Visual Design"
permalink: /curricula/designer-modules/visual-design/
ref: /curricula/designer-modules/visual-design/
lang: en
github:
  repository: w3c/wai-curricula
  path: content/designer/visual-design.md
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
  next: /curricula/designer-modules/information-design/
---

## Introduction
{:.no-display}

Courses based on this module should:

* demonstrate how people with disabilities rely on layouts that adapt to different screen sizes, screen configurations, and style sheets
* explain accessibility requirements for color, layout, spacing, and position of components

## Learning Outcomes for Module

Students should be able to:

* explain how people with disabilities rely on designs that adapt to different colors, layouts, spacing, and positions
* design layouts with sufficient color contrast for text, images of text, and controls
* design clear and distinguishable focus indicators, for example using borders, color, and highlighting
* use headings, spacing, and styling to group related content
* use visual and non-visual cues to convey information, including text, color, patterns, and icons 
* design layouts that adapt to:
  * different font sizes and spacing set by the user in browser and operating system settings
  * different screen sizes, screen configurations, and user style sheets
* evaluate the use of too many design elements and select elements that avoid potential distraction and cognitive overload
* identify related requirements for developers to apply the necessary semantics to interface components

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
  * [WCAG Success Criterion 2.5.5 Target Size](https://www.w3.org/WAI/WCAG21/quickref/#target-size)
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

Explain how sufficient color contrast (contrast ratio in WCAG) is essential for people with disabilities to perceive, distinguish, and understand content.

Describe how some people rely on color to understand and distinguish content. Explain that some people cannot perceive color well or at all. Discuss different ways to supplement information presented using color, such as using shapes and icons.

#### Learning Outcomes for Topic

Students should be able to:

* explain how appropriate use of color enables people with disabilities to read, understand, and distinguish components
* determine sufficient color contrast for text, images of text, and controls
* design text and images of text that have a color contrast of at least 4.5:1 with respect to their background
* design large-scale text and images of text that have a color contrast of at least 3:1 with respect to their background
* design components and graphics that have a color contrast of at least 3:1 with respect to their background
* define layouts to enable users to change colors based on customized screen sizes, screen configurations, and style sheets
* use visual cues in addition to text color, for example using different patterns, shapes, and icons
* use text to complement information provided visually

#### Teaching Ideas for Topic

Optional ideas to teach the learning outcomes:

* Show examples of sufficient and insufficient color contrast for text. Explain that color contrast for text (including images of text) needs to be at least 4.5:1 with respect to their background. For references on how to apply sufficient color contrast to text (including images of text), see technique [G18: Ensuring that a color contrast of at least 4.5:1 exists between text (and images of text) and background behind the text](https://www.w3.org/WAI/WCAG21/Techniques/general/G18.html).
* Show examples of different interactive components, such as buttons and links. Explain that they should have a color contrast of at least 3:1.
* Show examples of interfaces where information is conveyed exclusively with differences in color, such as a form where required fields are marked in red. Explain that some users cannot perceive color well or at all, so they require additional methods to convey that information. For references on how to supplement information conveyed through color, see technique [G182: Ensuring that additional visual cues are available when text color differences are used to convey information](https://www.w3.org/WAI/WCAG21/Techniques/general/G182.html).

#### Ideas to Assess Knowledge for Topic

Optional ideas to assess knowledge:

* Short Answer Questions &mdash; Give students several components and ask them what the color contrast should be. Assess how students understand and distinguish sufficient color contrast for different components.
* Practical &mdash; Students design a prototype and apply sufficient color contrast to text, images of text, components, and graphics. Assess how students understand and apply sufficient color contrast based on the different components that they are designing.
* Practical &mdash; Discuss examples of information presented using color with students and ask them to supplement that information using other visual cues. Assess how students use shapes and icons to supplement information presented using color distinguishable.

{% include excol.html type="end" %}

{% include excol.html type="start" %}

### Topic: Styles

{% include excol.html type="middle" %}

Explain how people with disabilities rely on distinguishable and customizable style properties, such as font types, sizes, and spacing, to support readability.

#### Learning Outcomes for Topic

Students should be able to:

* use clear and distinguishable styles for links, buttons, form labels and instructions, and text
* define customizable style properties to support content readability, including:
  * font types
  * font sizes
  * spacing
  * colors

#### Teaching Ideas for Topic

Optional ideas to teach the learning outcomes:

* Demonstrate the use of styles to distinguish links, buttons, and form labels and instructions, from plain text. Explain how people rely on font types, font sizes, spacing, and color to distinguish components.
* Show examples of usable font sizes and explain how they support readability. Contrast previous examples with fonts that are not as easy to read. Emphasize that several user groups rely on customizable fonts to read and understand content properly.
* Show examples of different page layouts with and without appropriate spacing. Explain how spacing allows for better readability of the content and for better identification of the different parts of the interface.

#### Ideas to Assess Knowledge for Topic

Optional ideas to assess knowledge:

* Practical &mdash; Students design a prototype with adaptable and distinguishable styles that help users perceive different content. Assess how students use different style properties such as font sizes and spacing to make content perceivable and to distinguish components from one another.

{% include excol.html type="end" %}

{% include excol.html type="start" %}

### Topic: Orientation Cues

{% include excol.html type="middle" %}

Explain how people with disabilities orient on web pages and applications using visual and non-visual cues, including focus indicators, as well as spacing and grouping to communicate regions. Present strategies to plan for the inclusion of such cues early in the visual design phase.

#### Learning Outcomes for Topic

Students should be able to:

* design focus indicators that enable people to tell where they are as they move through web pages and applications using the keyboard
* define page regions by using headings, spacing, and grouping
* design layouts that enable to present visual and non-visual cues in different screen sizes, screen configurations, and style sheets
* define methods to help users perceive and understand visual and non-visual cues, for example using text, color, and icons to convey the status of tasks in a project

#### Teaching Ideas for Topic

Optional ideas to teach the learning outcomes:

* Invite students to use a web page that has appropriate focus indicators first, and then invite them to use a web page without focus indicators. Explain how focus indicators allow people using the keyboard only to determine where they are as they move through web pages and applications using the keyboard only. For reference on how to provide appropriate focus indicators, see techniques [G149: Using user interface components that are highlighted by the user agent when they receive focus](https://www.w3.org/WAI/WCAG21/Techniques/general/G149.html) and [G195: Using an author-supplied, highly visible focus indicator](https://www.w3.org/WAI/WCAG21/Techniques/general/G195.html).
* Show examples of different web page regions, such as header, navigation, main, and footer. Explain that several groups of people with disabilities rely on visual and programmatic cues to perceive such regions. Explain that defining the presentation of these cues is a designers' responsibility, whereas implementing such cues and their semantics is a developers' responsibility.
* Show examples of interfaces where information is provided through vision only, such as those with icons and color to convey the status of different tasks in a project. Explain that some people cannot rely on visual means to obtain information, so they need text to understand the information provided. For references on how to complement information presented visually with text, see technique [G96: Providing textual identification of items that otherwise rely only on sensory information to be understood](https://www.w3.org/WAI/WCAG21/Techniques/general/G96.html).

#### Ideas to Assess Knowledge for Topic

Optional ideas to assess knowledge:

* Practical &mdash; Ask students to define the visual presentation of focus indicators on a web page or application. Assess how students understand the importance of focus indicators for users to know where they are on a web page or application.
* Practical &mdash; Give students a web page and ask them to define its regions. Assess how students define web page regions using a variety of methods, including headings, spacing, and grouping.
* Short Answer Questions &mdash; Give students examples of orientation cues conveyed visually and ask them to provide other visual and non-visual cues to help understand the information. Assess how students provide several visual and non-visual cues to help users understand the information.

{% include excol.html type="end" %}

{% include excol.html type="start" %}

### Topic: Flexible Layouts

{% include excol.html type="middle" %}

Explain how people with disabilities rely on layouts that adapt to different screen sizes, screen configurations, and style sheets to identify, distinguish, and process content. Explain that, in addition to using techniques such as responsive design, other elements, including content sequence, focus indicators, and target sizes need to adapt to different screen sizes, screen configurations, and style sheets for an accessible user experience. Emphasize that designers need to plan for these accessible user experiences early on in the visual design phase.

Demonstrate approaches to balance the use of too many design elements to avoid potential overload and distraction for some users.

#### Learning Outcomes for Topic

Students should be able to:

* design layouts to support text resizing without loss of content and functionality
* design layouts to support text zooming and enlarging in different viewport sizes and through multiple breakpoints
* design layouts that adapt their content view and operation to portrait and landscape orientations
* design layouts with target sizes that adapt to different screen sizes, screen configurations, and style sheets, for example when creating responsive designs
* design layouts to support user customization of line height, as well as spacing between paragraphs, words, and letters
* define meaningful focus orders that adapt to different viewports, screen sizes, and multiple breakpoints
* evaluate the use of too many design elements, in particular interactive widgets, images, and moving content) on a page, and select elements that avoid potential distraction and cognitive overload

#### Teaching Ideas for Topic

Optional ideas to teach the learning outcomes:

* Discuss with students the differences between web sites and applications that preserve content and functionality when resized up to 200% and those which do not. Explain that some people often need to resize text to read it properly. For references on how to ensure text resizes up to 200%, see technique [G179: Ensuring that there is no loss of content or functionality when the text resizes and text containers do not change their width](https://www.w3.org/WAI/WCAG21/Techniques/general/G179).
* Discuss the use of multiple screen sizes, screen configurations, and style sheets by people with low vision. Explain that these configurations often go beyond the traditional mobile, tablet, and desktop breakpoints.
* Show examples of user interfaces showing up in both portrait and landscape modes. Explain that the ability to show an interface both in portrait and landscape is essential for people who cannot change their device orientation due to mobility impairments.
* Show examples of different user interfaces that support customizing line height as well as spacing between paragraphs, words, and letters to support readability.
* Show examples of different target sizes and explain that some people have difficulty to tap smaller targets due to mobility impairments. Explain that target sizes need to be large enough to accommodate different people's needs.

#### Ideas to Assess Knowledge for Topic

Optional ideas to assess knowledge:

* Practical &mdash; Students design different layouts considering text resizing, line height, spacing between paragraphs, words, and letters. Assess how students consider text resizing, line height, and spacing between paragraphs, words, and letters.
* Practical &mdash; Students design an interface that adapts to portrait and landscape modes. Assess how students understand the need for interfaces to adapt to both portrait and landscape modes.

{% include excol.html type="end" %}

{% include excol.html type="all" %}

## Ideas to Assess Knowledge for Module

Optional ideas to assess knowledge:

* Short Answer Questions &mdash; Ask students about the color contrast ratios for the different user interface components. Assess how students understand the different color contrast requirements depending on the components.
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
