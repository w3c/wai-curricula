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
  previous: /curricula/designer-modules/flexible-and-responsive-design/
  next: /curricula/designer-modules/information-design/
---

## Introduction
{:.no-display}

Courses based on this module should:

* explain strategies that people with disabilities use to navigate multi page websites and applications
* present some behaviors, visual affordances, and interaction patterns of menus that relate to accessible design

## Learning Outcomes for Module

Students should be able to:

* explain strategies that people with disabilities use to navigate multipage websites and applications
* design user interfaces that support different types of navigations, including menus, breadcrumb trails, tables of contents, and site maps
* define keyboard, mouse, and tactile interactions for menus and other navigation mechanisms
* provide clear and consistent visual cues for menus, menu item states, and other navigation mechanisms
* define blocks of repeated content and coordinate with developers to implement mechanisms that bypass such blocks
* identify related requirements for developers to:
  * implement keyboard, mouse, and tactile interactions for navigation mechanisms
  * implement clear and descriptive names for navigation mechanisms

{% include excol.html type="all" %}

## Competencies

Skills required for this module:

{% include excol.html type="start" %}

### Students

{% include excol.html type="middle" %}

* [Prerequisites for Students](/curricula/designer-modules/#prerequisites-for-students)
* [Module 2: Flexible and Responsive Design](/curricula/designer-modules/flexible-and-responsive-design/) from [Designer Modules](/curricula/designer-modules/)

{% include excol.html type="end" %}

{% include excol.html type="start" %}

### Instructors

{% include excol.html type="middle" %}

* Applied expertise in teaching:
  * [WCAG Success Criterion 1.3.1 Info And Relationships](https://www.w3.org/WAI/WCAG21/quickref/#info-and-relationships)
  * [WCAG 2 Success Criterion 2.4.1 Bypass Blocks](https://www.w3.org/WAI/WCAG21/quickref/#bypass-blocks)
  * [WCAG 2 Success Criterion 2.4.5 Multiple Ways](https://www.w3.org/WAI/WCAG21/quickref/#multiple-ways)
  * [WCAG Success Criterion 2.4.6 Headings and Labels](https://www.w3.org/WAI/WCAG21/quickref/#headings-and-labels)
  * [WCAG 2 Success Criterion 2.4.8 Location](https://www.w3.org/WAI/WCAG21/quickref/#location)
  * [WCAG 2 Success Criterion 3.2.3 Consistent Navigation](https://www.w3.org/WAI/WCAG21/quickref/#consistent-navigation)

{% include excol.html type="end" %}

## Topics to Teach

Topics to achieve the learning outcomes:

{% include excol.html type="start" %}

### Topic: Menu Behaviors and Patterns

{% include excol.html type="middle" %}

Explain menu conventions that relate to accessibility, such as clear and consistent styling to convey menu states. Introduce patterns for mouse, keyboard, and tactile interaction with menus.

#### Learning Outcomes for Topic

Students should be able to:

* identify and describe uses of different types of menus, for example to navigate across web pages, to select categories from a crowded web page, and to navigate across applications
* provide visual cues for menus to distinguish them from other components, and consistent styling for menu identification across a set of web pages
* define mouse, keyboard, and tactile interactions within menus
* design user interfaces that communicate the state of menu items using distinguishable and consistent styles
* identify related requirements for developers to implement semantics for different menu states and properties, such as open, closed, expanded, or collapsed

#### Teaching Ideas

Optional ideas to teach the learning outcomes:

* Show examples of different types of menus, such as navigational, fly-out, and application menus. Explain the different scenarios where each of them can be used. For references on the different types of menus and their uses, see @@@
* Demonstrate menu interaction using different input devices, such as keyboard, mouse, and tactile. For example, activating a menu option by tapping, pressing the Enter key, and mouse clicking. Explain that defining the interactions is a designer's responsibility, whereas providing the underlying code is a developer's responsibility.
* Show examples of different menu states, such as expanded, collapsed, open, and closed menu and submenu items. Emphasize that the states of these menu items need to be communicated using visual cues as well as semantics. Explain that providing the visual cues is a designer's responsibility, whereas providing the underlying code is a developer's responsibility.

#### Ideas to Assess Knowledge for Topic

Optional ideas to support assessment.

* Practical &mdash; Students define mouse, keyboard, and tactile interactions for menus. for example how to open, navigate, activate, and close such menus using the mouse, keyboard, and touch. Assess how students understand the need for different interaction patterns based on the input method in use.
* Practical &mdash; Present students with different menu states, such as expanded, collapsed, open, and closed, and ask them to provide visual cues to distinguish them from one another. Assess how students communicate visually the state of menus and menu items.

{% include excol.html type="end" %}

{% include excol.html type="start" %}

### Topic: Other Navigation Mechanisms

{% include excol.html type="middle" %}

Introduce other navigation mechanisms that may be used depending on the characteristics of the website or application. Emphasize that there should be multiple ways to reach a specific web page or application view, but that it is not required to use every single navigation mechanisms described.

#### Learning Outcomes for Topic

Students should be able to:

* design user interfaces that support skipping blocks of repeated content providing at least one of the following:
  * a link at the top of each page that goes directly to the main content area
  * a link at the beginning of a block of repeated content to go to the end of the block
  * links at the top of the page that go to each area of the content
  * an expandable and collapsible menu to make it easier for users to skip the menu
* assess the need for other navigation mechanisms, such as breadcrumb trails, tables of contents, and sitemaps depending on the characteristics of the user interface
* design user interfaces that support breadcrumb trails to provide information about the user's location in a set of web pages
* design user interfaces that support site maps to provide an overview of the entire website
* design user interfaces that support tables of contents to give an overview of the whole website or document and to allow users to go to specific parts of the content

#### Teaching Ideas for Topic

Optional ideas to teach the learning outcomes:

* Show examples of mechanisms to bypass blocks of repeated content, such as a link at the top of the page and the use of expandable and collapsible components. Explain that people using the keyboard only find it very frustrating to navigate through sets of repeated blocks of content, such as navigation bars or header contents. For references on how to provide a mechanism to bypass blocks of repeated content, see @@@
* Show examples of breadcrumb trails. Explain that they provide information about the user's location within the context of a set of websites. Emphasize that they are useful especially in cases where the navigation contains a lot of nested levels. For reference on how to provide breadcrumb trails, see @@@
* Show examples of site maps and explain that they serve the purpose of providing an overview of the whole site. Explain that some users rely on them to better understand the structure of the site and to more easily find its way through it. For references on how to provide a site map, see @@@
* Show examples of tables of contents, for example in an electronic book or document. Explain that they provide an overview of the whole document and allow navigation to specific parts of the content.

#### Ideas to Assess Knowledge for Topic

Optional ideas to support assessment:

* Practical &mdash; Students define the block of repeated content within a  website and coordinate with developers to provide a way for users to bypass that block. Assess how students identify blocks of repeated content and how they provide a mechanism to bypass it.
* Practical &mdash; Present students with an interface and ask them to provide multiple ways to navigate across the website. Assess how students provide multiple navigation mechanisms where appropriate, such as tables of contents and sitemaps.
* Practice &mdash; Present students with a second-level web page within a website and ask them to provide a breadcrumb trail for users to understand where a page is located with respect to the whole website. Assess how students provide a breadcrumb trail.

{% include excol.html type="end" %}

{% include excol.html type="all" %}

## Ideas to Assess Knowledge for Module

Optional ideas to support assessment:

* Portfolio &mdash; Students add navigation across web pages or applications views. Assess how students understand accessibility features of navigation across multipage websites and applications 

## Teaching Resources

Suggested resources to support your teaching:

* @@@
* [Menus (WAI Web Accessibility Tutorials)](https://www.w3.org/WAI/tutorials/menus/) &mdash; Shows how to develop navigational mechanisms that are accessible to people with disabilities.
* [How People with Disabilities Use the Web](/people-use-web/) &mdash; Provides stories of people with disabilities using the Web; describes types of disabilities and some of the barriers that people encounter using the Web; and introduces types of assistive technologies and adaptive strategies that some people use.
* [Keyboard Compatibility (Web Accessibility Perspectives)](https://www.w3.org/WAI/perspective-videos/keyboard/) &mdash; Is one of the Web accessibility perspectives videos that show accessibility features and how they impact people with disabilities.
* [WCAG](https://www.w3.org/WAI/standards-guidelines/wcag/) &mdash; Address accessibility of web content on desktops, laptops, tablets, and mobile devices.
