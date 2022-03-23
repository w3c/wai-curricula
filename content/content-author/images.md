---
title: "[Draft] Module 3: Images"
nav_title: "Images"
permalink: /curricula/content-author-modules/images/
ref: /curricula/content-author-modules/images/
lang: en
github:
  repository: w3c/wai-curricula
  path: content/content-author-modules/images.md
license: creative-commons
acknowledgements: /curricula/acknowledgements/
changelog: /curricula/changelog/
footer: >
  <p><strong>Date:</strong> Updated 9 February 2022. First published December 2019.</p>
  <p><strong>Editors:</strong> Daniel Montalvo and <a href="http://www.w3.org/People/shadi/">Shadi Abou-Zahra</a>. Contributors: <a href="https://www.w3.org/WAI/EO/EOWG-members">EOWG Participants</a>. ACKNOWLEDGEMENTS lists contributors and credits.</p>
  <p>Developed by the Education and Outreach Working Group (<a href="http://www.w3.org/WAI/EO/">EOWG</a>). Developed with support from the <a href="https://www.w3.org/WAI/about/projects/wai-guide/">WAI-Guide Project</a> funded by the European Commission (EC) under the Horizon 2020 program (Grant Agreement 822245).</p>
parent_in_h1:
  - ref: /curricula/content-author-modules/
    name: nav_title
  - ref: /curricula/
    name: "Curricula on Web Accessibility"
navigation:
  previous: /curricula/content-author-modules/structure/
  next: /curricula/content-author-modules/data-tables/
---

## Introduction
{:.no-display}

Courses based on this module should:

* demonstrate how text alternatives for images enable people who cannot see the images to understand the image content
* explain accessibility requirements related to images, including text alternatives and long descriptions

## Learning Outcomes for Module

Students should be able to:

* explain how people with disabilities rely on text alternatives for images (including for diagrams, charts, maps, and infographics) to understand information
* explain the purpose of the following types of images:
  * informative (convey information)
  * functional (convey functionality)
  * complex (require long descriptions and sometimes alternative interaction methods)
* write clear and succinct text alternatives for functional images
* write equivalent and understandable text alternatives for informative images
* explain the issues associated with:
  * perception, interpretation, and rendering of images of text
  * automatically generated alternative texts that have not been checked for quality and accuracy
* employ accessible authoring tools that
  * support the inclusion of text alternatives for images
  * enable authors to amend suggested text alternatives when needed
  * support marking an image as decorative when it has an ornamental purpose
  * produce appropriate markup for text alternatives
  * support several modalities of CAPTCHA, including visual, auditory, and biometrics
* identify related requirements for designers and developers to support visual and non-visual perception of images

{% include excol.html type="all" %}

## Competencies

Skills required for this module:

{% include excol.html type="start" %}

### Students

{% include excol.html type="middle" %}

* [Foundation Prerequisites](/curricula/developer-modules/#foundation-prerequisites)
* Basic knowledge of:
  * Content creation
  * Content editing

{% include excol.html type="end" %}

{% include excol.html type="start" %}

### Instructors

{% include excol.html type="middle" %}

* Applied expertise in teaching:
  * [WCAG Success Criterion 1.1.1 Non-Text Content](https://www.w3.org/WAI/WCAG21/quickref/#non-text-content)
  * [WCAG Success Criterion 1.4.1 Use of Color](https://www.w3.org/WAI/WCAG21/quickref/#use-of-color)
  * [WCAG Success Criterion 1.4.3 Contrast (Minimum)](https://www.w3.org/WAI/WCAG21/quickref/#contrast-minimum)
  * [WCAG Success Criterion 1.4.5 Images of Text](https://www.w3.org/WAI/WCAG21/quickref/#images-of-text)
  * [WCAG Success Criterion 1.4.6 Contrast (Enhanced)](https://www.w3.org/WAI/WCAG21/quickref/#contrast-enhanced)
  * [WCAG Success Criterion 1.4.9 Images of Text (No Exception)](https://www.w3.org/WAI/WCAG21/quickref/#images-of-text-no-exception)
  * [WCAG Success Criterion 1.4.11 Non-Text Contrast](https://www.w3.org/WAI/WCAG21/quickref/#non-text-contrast)

{% include excol.html type="end" %}

## Topics to Teach

Topics to achieve the learning outcomes:

{% include excol.html type="start" %}

### Topic: Informative Images

{% include excol.html type="middle" %}

[Intro paragraph TBD].

#### Learning Outcomes for Topic

Students should be able to:

* provide quality-checked text alternatives for informational images using:
  * clear and descriptive text alternatives associated to the images
  * adjacent text that conveys the same information as the image
* write textual information as text instead of including text content in an image file
* ensure availability of different modalities of CAPTCHA, including visual, auditory, and biometrics
* employ accessible authoring tools that:
  * support the inclusion of alternative text for informative images
  * enable authors to amend suggested text alternatives when needed
  * produce appropriate markup for informative images
  * support different modalities of CAPTCHA, including visual, auditory, and biometrics

#### Teaching Ideas for Topic

Optional ideas to teach the learning outcomes:

* Discuss examples of informative images, including icons, pictures, and illustrations. Relate these images to their adjacent text. Explain that these images are considered informative when they present information that is not otherwise available in the adjacent text.
* Explain the differences between providing textual information as text and providing text in an image file. Explain that some assistive technologies may be able to recognize some text in an image, but may still miss the semantics in the text.
* Reflect with students on available authentication systems to identify humans, including visual, auditory, and logical CAPTCHA, as well as biometrics. Describe challenges associated to relying only on one modality of CAPTCHA. Emphasize that authors must ensure people can authenticate through several modalities of CAPTCHA. This includes ensuring the tool provides such modalities itself or using plugins that include that functionality.

#### Ideas to Assess Knowledge for Topic

Optional ideas to assess knowledge:

* Short Answer Questions &mdash; Ask students about the type of information that alternative text for informative images should contain. Assess how students explain the type of information that alternative text for informative images should contain.
* Practical &mdash; Give students several informative images with adjacent text. Ask them to determine if the adjacent text provides enough information to understand the image and what type of alternative text they would include. Assess how students provide alternative text for informative images based on the information contained in the image and in its adjacent text.

{% include excol.html type="end" %}

{% include excol.html type="start" %}

### Topic: Functional Images

{% include excol.html type="middle" %}

Functional images convey functionality. For example, magnifying glasses for search functionality. @@@

#### Learning Outcomes for Topic

Students should be able to:

* explain how people with disabilities rely on text alternatives for functional images that describe the image function
* write short, succinct, and quality-checked  text alternatives to help people who don't see the image understand its function
* provide information about the image function in the text alternative instead of describing the image appearance
* employ accessible authoring tools that:
  * support the inclusion of text alternatives for images
  * enable authors to amend suggested text alternatives when needed
  * produce appropriate markup for functional images

#### Teaching Ideas for Topic

Optional ideas to teach the learning outcomes:

* Discuss examples of functional images, for example graphical buttons and links. Explain that text alternatives for these images must describe the functionality of the component. For example "Search" instead of "magnifying glasses", and "print" instead of "printer".
* Introduce accessible authoring tools that support the inclusion of text alternatives for images and that produce appropriate markup for those images. Explain that some tools may refer to alternative texts as image descriptions.

#### Ideas to Assess Knowledge for Topic

Optional ideas to assess knowledge:

* Short Answer Questions &mdash; Ask students about the type of information that functional images should convey. Assess how students understand the type of information that functional images should convey.
* Practical &mdash; Give students examples of functional images and ask them to provide their text alternative. Assess how students include information about the image function in the text alternative.

{% include excol.html type="end" %}

{% include excol.html type="start" %}

### Topic: Complex Images

{% include excol.html type="middle" %}

Complex images are charts, diagrams, maps, and infographics. They require short descriptions that identify the complex images, and long descriptions that provide the same information as that in the image provides.

#### Learning Outcomes for Topic

Students should be able to:

* write short, succinct, and clear descriptions that:
  * identify the described complex image
  * include reference to the alternative long description for the image
* provide textual information that helps understand and process the image contents through:
  * additional blocks of content in the same page
  * separate pages containing the long descriptions
* collaborate with designers and developers to ensure:
  * appropriate contrast ratios for complex images and descriptions
  * reliable identification of short and long descriptions for complex images

#### Teaching Ideas for Topic

Optional ideas to teach the learning outcomes:

[TBD]

#### Ideas to Assess Knowledge for Topic

Optional ideas to assess knowledge:

[TBD]

{% include excol.html type="end" %}

{% include excol.html type="all" %}

## Ideas to Assess Knowledge for Module

Optional ideas to assess knowledge:

[TBD]

## Teaching Resources

Suggested resources to support your teaching:

[TBD]
