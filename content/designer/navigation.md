---
title: "[Draft] Module 3: Navigation"
nav_title: "Navigation"
permalink: /curricula/designer-modules/navigation/
ref: /curricula/designer-modules/navigation/
lang: en
github:
  repository: w3c/wai-curricula
  path: content/designer/navigation.md
license: creative-commons
acknowledgements: /curricula/acknowledgements/
changelog: /curricula/changelog/
footer: >
  <p><strong>Date:</strong> Updated @@ Month 2021. First published December 2019. CHANGELOG</p>
  <p><strong>Editors:</strong> Daniel Montalvo and <a href="http://www.w3.org/People/shadi/">Shadi Abou-Zahra</a>. Contributors: <a href="https://www.w3.org/WAI/EO/EOWG-members">EOWG Participants</a>. ACKNOWLEDGEMENTS lists contributors and credits.</p>
   <p>Developed by the Education and Outreach Working Group (<a href="http://www.w3.org/WAI/EO/">EOWG</a>). Developed with support from the <a href="https://www.w3.org/WAI/about/projects/wai-guide/">WAI-Guide Project</a> funded by the European Commission (EC) under the Horizon 2020 program (Grant Agreement 822245).</p>
navigation:
  previous: /curricula/designer-modules/flexible-color-layout-and-design/
  next: /curricula/designer-modules/information-design/
---

## Introduction
{:.no-display}

Courses based on this module should:

* explain strategies that people with disabilities use to navigate websites and applications
* describe accessible behaviors, visual affordances, and interaction patterns of navigation menus, including static navigation menus, fly-out menus, and mega menus

## Learning Outcomes for Module

Students should be able to:

* explain strategies that people with disabilities use to navigate websites and applications
* design different types of navigation mechanisms, including menus, tables of contents, and site maps
* define different interactions for menus and other navigation mechanisms, including keyboard, mouse, and touch
* provide clear and consistent visual presentation of menus and menu items
* provide clear and consistent visual indication of state changes for menu items
* provide mechanisms for developers to identify blocks of repeated content
* cooperate with developers to implement mechanisms that bypass blocks of repeated content
* provide mechanisms to help users to locate specific web pages within sets of web pages, for example by providing breadcrumb trails, site maps, and descriptive page titles
* identify related requirements for developers to implement:
  * interactions for navigation mechanisms, including keyboard, mouse, and touch
  * clear and descriptive names for navigation mechanisms
  * necessary semantics for menus, menu items, and menu item states

{% include excol.html type="all" %}

## Competencies

Skills required for this module:

{% include excol.html type="start" %}

### Students

{% include excol.html type="middle" %}

* [Foundation Prerequisites](/curricula/designer-modules/#foundation-prerequisites)
* [Designer Module 1: #foundation-prerequisitesFlexible Color, Layout, and Design](/curricula/designer-modules/flexible-color-layout-and-design/)
* Basic knowledge of:
  * Visual Design
  * Prototyping
  * Responsive Design
  * Information Architecture

{% include excol.html type="end" %}

{% include excol.html type="start" %}

### Instructors

{% include excol.html type="middle" %}

* Applied expertise in teaching:
  * [WCAG Success Criterion 1.3.1 Info and Relationships](https://www.w3.org/WAI/WCAG21/quickref/#info-and-relationships)
  * [WCAG Success Criterion 2.1.1 Keyboard](https://www.w3.org/WAI/WCAG21/quickref/#keyboard)
  * [WCAG Success Criterion 2.1.2 No Keyboard Trap](https://www.w3.org/WAI/WCAG21/quickref/#no-keyboard-trap)
  * [WCAG 2 Success Criterion 2.4.1 Bypass Blocks](https://www.w3.org/WAI/WCAG21/quickref/#bypass-blocks)
  * [WCAG Success Criterion 2.4.2 Page Titled](https://www.w3.org/WAI/WCAG21/quickref/#page-titled)
  * [WCAG 2 Success Criterion 2.4.5 Multiple Ways](https://www.w3.org/WAI/WCAG21/quickref/#multiple-ways)
  * [WCAG Success Criterion 2.4.6 Headings and Labels](https://www.w3.org/WAI/WCAG21/quickref/#headings-and-labels)
  * [WCAG 2 Success Criterion 2.4.8 Location](https://www.w3.org/WAI/WCAG21/quickref/#location)
  * [WCAG 2 Success Criterion 3.2.3 Consistent Navigation](https://www.w3.org/WAI/WCAG21/quickref/#consistent-navigation)
* In-depth knowledge of:
  * [Foundation Prerequisites](/curricula/designer-modules#foundation-prerequisites)
  * Visual Design
  * Prototyping
  * Responsive Design
  * Information Architecture

{% include excol.html type="end" %}

## Topics to Teach

Topics to achieve the learning outcomes:

{% include excol.html type="start" %}

### Topic: Menu Behaviors and Patterns

{% include excol.html type="middle" %}

Show examples of different types of navigation menus, such as static, fly-out, and mega menus. Explain the different scenarios where each of them can be used. For references on the different types of menus and their uses, see the WAI tutorials on [Menus](https://www.w3.org/WAI/tutorials/menus/).

Explain styling conventions for menus, such as location, appropriate size, and ability for menus and menu items to resize depending on different user configurations. For references on how to apply accessible menu styles, see the WAI tutorial on [Menu Styling](https://www.w3.org/WAI/tutorials/menus/styling/).

#### Learning Outcomes for Topic

Students should be able to:

* identify and describe uses of different types of navigation menus, such as static, fly-out, and mega menus
* provide visual cues to distinguish menus from other components, 
* provide consistent styling for menu identification across a set of web pages
* define interactions inside navigation menus, including mouse, keyboard, and touch
* design navigation menus that adapt to the different text sizes, screen magnifications, and screen sizes and resolutions 
* design distinguishable and consistent styles for menu items in their different states, for example in fly-out menus
* identify related requirements for developers to implement:
  * non-visual identification (and naming)of menus,
  * semantics for different menu states and properties, such as hover, focus, current, active, and visited
  * support for different interaction methods, including keyboard, mouse, and touch
  * support for different text and screen sizes
 
#### Teaching Ideas

Optional ideas to teach the learning outcomes:

* Present different types of navigation menus, such as static, fly-out, and mega menus. Explain conventions for accessible navigation menus, such as clear and consistent styling to convey menu behaviors and states. Introduce patterns for mouse, keyboard, and touch interaction with navigation menus.
* Demonstrate navigation menu interaction using different input devices, such as keyboard, mouse, and touch. For example, activating a menu option by tapping, pressing the Enter key, and mouse clicking. Explain that defining the interactions is a designers' responsibility, whereas providing the underlying code is a developers' responsibility.
* Show examples of navigation menus and menu items large text. Explain that, when used in smaller viewports and with different screen configurations, these text needs to wrap so that it is perceived in its entirety. Explain that different languages may have different word sizes, so designers need to consider provisions for different word lengths.
* Show examples of different menu and submenu item states, such as hover, focus, current, active, and visited. Emphasize that the states of these menu items need to be communicated using visual cues as well as semantics. Explain that providing the visual cues is a designers' responsibility, whereas providing the underlying code is a developers' responsibility.

#### Ideas to Assess Knowledge for Topic

Optional ideas to assess knowledge:

* Practical &mdash; Students define mouse, keyboard, and touch interactions for navigation menus. for example, how to open, navigate, activate, and close such menus using the mouse, keyboard, and touch. Assess how students understand the need for different interaction patterns based on the input method in use.
* Practical &mdash; Present students with different navigation menu states, such as hover, focus, current, active, and visited, and ask them to provide visual cues to distinguish them from one another. Assess how students communicate visually the state of navigation menus and menu items.
* Practical &mdash; Present students with navigation menus containing long strings of text and ask them to ensure the text is shown irrespective of the viewport and screen configuration used. Assess how students understand the diversity among different languages, viewports, and screen configurations.

{% include excol.html type="end" %}

{% include excol.html type="start" %}

### Topic: Other Navigation Mechanisms

{% include excol.html type="middle" %}

Introduce other navigation mechanisms that may be used depending on the characteristics of the website or application. Emphasize that different groups of users rely on different navigation mechanisms, so designers need to assess which ones to use to favor user various experiences.

#### Learning Outcomes for Topic

Students should be able to:

* define blocks of repeated content, such as navigation bars and header contents, and define mechanisms to skip such blocks using the following approaches:
  * a link at the top of each page that goes directly to the main content area
  * a link at the beginning of a block of repeated content to go to the end of the block
  * tables of contents at the top of the page that go to each area of the content
  * expandable and collapsible contents to make it easier for users to skip over them
* provide other navigation mechanisms to ensure web pages and application views can be reached using the following methods:
  * search functionalities that support navigating to specific parts of the site
  * site maps to provide an overview of the entire website
* balance the use of navigation mechanisms to avoid distractions and unnecessary noise

#### Teaching Ideas for Topic

Optional ideas to teach the learning outcomes:

* Show examples of mechanisms to bypass blocks of repeated content, such as a link at the top of the page and the use of expandable and collapsible components. Explain that navigating through sets of repeated blocks of content using only the tab key is time consuming. For examples on how to provide a mechanism to bypass blocks of repeated content, see the following techniques:
  * [G1: Adding a link at the top of each page that goes directly to the main content area](https://www.w3.org/WAI/WCAG21/Techniques/general/G1.html),
  * [G123: Adding a link at the beginning of a block of repeated content to go to the end of the block](https://www.w3.org/WAI/WCAG21/Techniques/general/G123.html), and
  * [G124: Adding links at the top of the page to each area of the content](https://www.w3.org/WAI/WCAG21/Techniques/general/G124.html).
* Show examples of search functionalities. Explain that they help users find content by supporting navigation to different parts of the site. Emphasize that some users prefer this way of navigating, especially when they are already familiar with the site and know what they are looking for. For references on how to provide a search functionality, see technique [G161: Providing a search function to help users find content](https://www.w3.org/WAI/WCAG21/Techniques/general/G161).
* Show examples of site maps and explain that they serve the purpose of providing an overview of the whole site. Explain that some users rely on them to better understand the structure of the site and to find its way more easily through it. For references on how to provide a site map, see [G63: Providing a site map](https://www.w3.org/WAI/WCAG21/Techniques/general/G63.html).
* Show examples of tables of contents, for example in an electronic book or document. Explain that they provide an overview of the whole document and allow navigation to specific parts of the content. For references on how to provide a table of contents, see technique [G64: Providing a Table of Contents](https://www.w3.org/WAI/WCAG21/Techniques/general/G64.html).

#### Ideas to Assess Knowledge for Topic

Optional ideas to assess knowledge:

* Practical &mdash; Students define the blocks of repeated content in a website and cooperate with developers to provide a way for users to bypass such blocks. Assess how students identify blocks of repeated content and how they work with developers to provide a mechanism to bypass such blocks.
* Practical &mdash; Present students with an interface and ask them to provide multiple ways to navigate across the website. Assess how students provide multiple navigation mechanisms where appropriate, such as search functionalities, breadcrumb trails, site maps, and tables of contents.
* Practical &mdash; Give students an interface with excessive use of navigation mechanisms and ask them to determine which of these navigation mechanisms should stay and which should be removed. Assess how students balance the use of navigation mechanisms to avoid distraction and unnecessary noise.

{% include excol.html type="end" %}

{% include excol.html type="start" %}

### Topic: Location

{% include excol.html type="middle" %}

Build on [Foundation Module 6: Understanding and Involving Users](/curricula/foundation-modules/understanding-and-involving-users/) to research strategies that people with disabilities use to locate a specific web page in a set of web pages. Discuss examples like breadcrumb trails, page titles, and visual cues to indicate the current page.

#### Learning Outcomes for Topic

Students should be able to:

* design mechanisms  for users to locate specific web pages within sets of web pages, for example:
  * descriptive page titles
  * breadcrumb trails
  * textual and visual cues in the navigation menu to indicate the current page
  * descriptive page headings
* identify related requirements for developers to code location mechanisms
* balance the use of location mechanisms to avoid distractions and unnecessary noise

### Teaching Ideas

Optional ideas to teach the learning outcomes:

* Show examples of breadcrumb trails. Explain that they provide information about the users location in the context of a set of web pages. Emphasize that they are useful especially in cases where the navigation contains a lot of nested levels. For reference on how to provide breadcrumb trails, see technique [G65: Providing a breadcrumb trail](https://www.w3.org/WAI/WCAG21/Techniques/general/G65).
* Invite students to give examples of page titles they are familiar with and reflect with them on how well the titles describe the page contents. Explain that page titles are useful to identify the purpose of a specific web page within a set of web pages. Mention that it is best practice to put the title text both in the page title and in the first heading of level 1 on the page, as some browsers and assistive technologies do not show the information on the title. Explain that providing page titles is a responsibility shared with the content author. For references on how to provide descriptive page titles, see technique [G88: Providing descriptive titles for Web pages](https://www.w3.org/WAI/WCAG21/Techniques/general/G88.html).

#### Ideas to Assess Knowledge

Optional ideas to assess knowledge:

* Practical &mdash; Present students with a specific web page inside a website and ask them to provide appropriate indications about the page location with respect to the entire website. Assess how students balance the use of appropriate indications to communicate the location of a web page within a set of web pages.
* Practical &mdash; Present students with a set of web pages and ask them to provide descriptive titles that identify each of the pages and describe what they are about. Assess how students provide clear and descriptive page titles.

{% include excol.html type="end" %}

{% include excol.html type="all" %}

## Ideas to Assess Knowledge for Module

Optional ideas to assess knowledge:

* Portfolio &mdash; Students design the navigation menu and other navigational mechanisms for a set of web pages. Assess how students understand accessibility features of navigation across websites and applications.

## Teaching Resources

Suggested resources to support your teaching:

* [Menus (WAI Web Accessibility Tutorials)](https://www.w3.org/WAI/tutorials/menus/) &mdash; Shows how to design navigational mechanisms that are accessible to people with disabilities.
* [[How People with Disabilities Use the Web]](/people-use-web/) &mdash; Provides stories of people with disabilities using the Web; describes types of disabilities and some of the barriers that people encounter using the Web; and introduces types of assistive technologies and adaptive strategies that some people use.
* [Keyboard Compatibility (Web Accessibility Perspectives)](https://www.w3.org/WAI/perspective-videos/keyboard/) &mdash; Is one of the Web accessibility perspectives videos that show accessibility features and how they impact people with disabilities.
* [Colors with Good Contrast (Web Accessibility Perspective)](/perspective-videos/contrast/) &mdash; Is one of the Web accessibility perspectives videos that show accessibility features and how they impact people with disabilities.
* [Text to Speech (Web Accessibility Perspectives)](/perspective-videos/speech/) &mdash; Is one of the Web accessibility perspectives videos that show accessibility features and how they impact people with disabilities.
* [Large Links, Buttons, and Controls (Web Accessibility Perspectives)](/perspective-videos/controls/) &mdash; Is one of the Web accessibility perspectives videos that show accessibility features and how they impact people with disabilities.
* [WCAG](https://www.w3.org/WAI/standards-guidelines/wcag/) &mdash; Address accessibility of web content on desktops, laptops, tablets, and mobile devices.
