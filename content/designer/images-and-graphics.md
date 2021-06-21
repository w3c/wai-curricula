---
title: "[Draft] Module 4: Images and Graphics"
nav_title: "Images and Graphics"
permalink: /curricula/designer-modules/images-and-graphics/
ref: /curricula/designer-modules/images-and-graphics/
lang: en
github:
  repository: w3c/wai-curricula
  path: content/designer/images-and-graphics.md
license: creative-commons
acknowledgements: /curricula/acknowledgements/
changelog: /curricula/changelog/
footer: >
  <p><strong>Date:</strong> Updated @@ Month 2021. First published December 2019. CHANGELOG</p>
  <p><strong>Editors:</strong> Daniel Montalvo and <a href="http://www.w3.org/People/shadi/">Shadi Abou-Zahra</a>. Contributors: <a href="https://www.w3.org/WAI/EO/EOWG-members">EOWG Participants</a>. ACKNOWLEDGEMENTS lists contributors and credits.</p>
  <p>Developed by the Education and Outreach Working Group (<a href="http://www.w3.org/WAI/EO/">EOWG</a>). Developed with support from the <a href="https://www.w3.org/WAI/about/projects/wai-guide/">WAI-Guide Project</a> funded by the European Commission (EC) under the Horizon 2020 program (Grant Agreement 822245).</p>
navigation:
  previous: /curricula/designer-modules/information-design/
  next: /curricula/designer-modules/multimedia-and-animations/
---

## Introduction
{:.no-display}

Courses based on this module should:

* explain strategies that people with disabilities use to access information contained in images
* explain accessibility requirements related to images and graphics, such as text alternatives, text descriptions, and contrast ratios

## Learning Outcomes for Module

Students should be able to:

* explain how images affect processing of information, content identification, and understanding of functionality by people with disabilities
* provide meaningful and consistent text alternatives for functional images included in the design phase, such as those included in buttons, links, icons, and logos
* design user interfaces with consistent iconography to help users recognize the purpose of icons, thumbnails, and other graphical components
* design user interfaces that present information as text when the desired visual presentation can be achieved by the technology in use, instead of using images of text
* collaborate with developers and content authors to provide the appropriate alternative for images and graphics included in the design phase based on the image purpose
* identify related requirements for developers to code images and text alternatives appropriately
* identify related requirements for content authors to provide appropriate descriptions for images included in the authoring phase, such as charts, diagrams, and other complex graphics

{% include excol.html type="all" %}

## Competencies

Skills required for this module:

{% include excol.html type="start" %}

### Students

{% include excol.html type="middle" %}

* [Prerequisites for students](/curricula/designer-modules#prerequisites-for-students)
* [Module 2: Flexible Layout and Design](/curricula/designer-modules/flexible-layout-and-design/)
* [Module 3: Navigation](/curricula/designer-modules/navigation/)
* [Module 4: Information Design](/curricula/designer-modules/information-design/)

{% include excol.html type="end" %}

{% include excol.html type="start" %}

### Instructors

{% include excol.html type="middle" %}

* Applied expertise in teaching:
  * [WCAG Success Criterion 1.1.1 Non-Text Content](https://www.w3.org/WAI/WCAG21/quickref/#non-text-content)
  * [WCAG Success Criterion 1.4.5 Images of Text](https://www.w3.org/WAI/WCAG21/quickref/#images-of-text)
  * [WCAG Success Criterion 1.4.9 Images of Text (No Exception)](https://www.w3.org/WAI/WCAG21/quickref/#images-of-text-no-exception)
* In-depth knowledge of:
  * [Prerequisites for students](/curricula/designer-modules#prerequisites-for-students)
  *  Visual Design
  * Responsive Design
  * Information Architecture

{% include excol.html type="end" %}

## Topics to Teach

Topics to achieve the learning outcomes:

{% include excol.html type="start" %}

### Topic: Functional Images

{% include excol.html type="middle" %}

Functional images convey functionality of a user interface component. For example search, print, and save functionality. Explain requirements related to color and contrast to help users distinguish these images from other components. Show examples of graphical links and buttons as well as logos. Discuss with students how they would describe each of those examples.

#### Learning Outcomes for Topic

Students should be able to:

* design user interfaces with text alternatives for functional images by using one of the following:
  * providing a text alternative for the image
  * combining the text alternative of the image with the adjacent text inside the component
  * providing adjacent text inside the component to understand its function
* create designs with consistent naming and iconography for user interface components that have the same functionality across web pages
* decide if the alternative text should be visible to screen readers only or to all users, to allow for better recognition of the conveyed functionality
* apply appropriate contrast ratios for functional images belonging to components that accept user input

#### Teaching Ideas for Topic

Optional ideas to teach the learning outcomes:

* Show examples of different images used to convey functionality, such as for printing, searching, or saving a document. Explain that it is necessary to provide  and equivalent, succinct text alternative that explains the function rather than a description of the image. For reference on how  to provide a text alternative for an image conveying function, see technique [G94: Providing short text alternative for non-text content that serves the same purpose and presents the same information as the non-text content](https://www.w3.org/WAI/WCAG21/Techniques/general/G94.html).

#### Ideas to Assess Knowledge for Topic

Optional ideas to assess knowledge:

* Practical &mdash; Give students a set of images conveying function, such as a printer for a "print" button and a magnifying glass for a "search" button. Ask students to provide an appropriate text alternative. Assess how students identify images that convey function and provide text alternatives that describe the functionality of the component the image is attached to.
* Practical &mdash; Ask students to design a series of graphical buttons and links in a way that they are perceivable and distinguishable by all users. Assess how students apply accessibility requirements, such as contrast ratios, to graphical buttons and links.

{% include excol.html type="end" %}

{% include excol.html type="start" %}

### Topic: Informative Images

{% include excol.html type="middle" %}

Informative images convey information that is necessary to understand the content. Show examples of thumbnails and other icons that convey information. Discuss with students how they would describe them. 
Explain that providing text alternatives for informative images is a responsibility shared with the content author.

#### Learning Outcomes for Topic

Students should be able to:

* provide text alternatives that present equivalent information as that contained in informative images, by using one of the following:
  * including a boilerplate description that would then be completed in the authoring phase with real descriptions
  * complementing thumbnails and icons with adjacent textual information, for example in a news headline
  * providing a text alternative that describes the information conveyed by the image
* apply the appropriate contrast ratio to images that are necessary to understand the contents
* identify related requirements for developers to code alternative texts for informative images

### Teaching Ideas for Topic

Optional ideas to teach the learning outcomes:

* Show examples of different images that convey information, such as images to provide instructions, and to identify people and objects. Explain that such information needs to be provided using text alternatives, so that the purpose of the image can be understood without having to look at the image. Emphasize that these alternatives may require coordination among designers, developers, and content authors. For references on how to provide text alternatives for images, see [G82: Providing a text alternative that identifies the purpose of the non-text content](https://www.w3.org/WAI/WCAG21/Techniques/general/G82.html).

#### Ideas to Assess Knowledge for Topic

Optional ideas to support assesment.

[To be developed].

{% include excol.html type="end" %}

{% include excol.html type="start" %}

### Topic: Decorative Images

{% include excol.html type="middle" %}

Decorative images are used for ornamental purposes and convey no information or function. Explain that these images do not require text alternatives, as these would add clutter to the information that assistive technologies provide. Explain that deciding if an image is decorative is a responsibility shared with the content author.

#### Learning Outcomes for Topic

Students should be able to:

* design user interfaces with decorative images that do not overlap with user interface components and contents when viewed using different screen sizes, configurations, and setups
* indicate to developers which of the images provided in the design phase are decorative, so that they can code them appropriately
* identify related requirements for developers to code decorative images so that they are skipped by assistive technologies

#### Teaching Ideas for Topic

Optional ideas to teach the learning outcomes:

* Show examples of images and graphics that do not convey function or information, such as ornamental icons. Explain that they serve ornamental purposes as long as people can understand and interact with the user interface with or without such icons. Explain that deciding what is the images' role is a designers' responsibility, whereas coding the images so that they rendered with the appropriate role is a developers' responsibility.

#### Ideas to Assess Knowledge for Topic

Optional ideas to assess knowledge:

* Practical &mdash; Ask students to provide decorative images to illustrate a text article and ask them to ensure these icons are visible in different screen sizes and devices. Assess how students understand the need for decorative images to adapt to the different user needs and preferences.

{% include excol.html type="end" %}

{% include excol.html type="start" %}

### Topic: Complex and Textual Images

{% include excol.html type="middle" %}

Show examples of complex images and images of text. Images of text are those which are intended to be read as text but are coded as an image. Complex images are those whose description requires more than a short phrase or sentence. Explain accessibility requirements that these images have, such as appropriate contrast ratios and appropriate text descriptions.

Explain that coordination among different team members is required to establish the relations between  parts of complex images and their adjacent components (for example text and other images) so that the relations are perceived and understood visually and through the provided descriptions.

#### Learning Outcomes for Topic

Students should be able to:

* design user interfaces that support appropriate contrast ratios for complex images when these images are required to understand the contents
* design user interfaces that support use of text instead of images of text when the technology in use can provide the desired visual presentation
* design user interfaces with alternatives to visual CAPTCHA, for example auditory CAPTCHA, logical CAPTCHA, and biometrics
* identify related requirements for content authors to provide descriptive, equivalent textual information to understand complex images and graphics, such as diagrams or charts
* determine if and how complex images are operated using the mouse, keyboard, and other input devices

#### Teaching Ideas for Topic

Optional ideas to teach the learning outcomes:

* Provide examples of complex images and graphics, such as charts and diagrams. Explain that they need to have a contrast ratio of at least 3:1, as they are necessary to understand the content. For references on how to provide complex graphics that meet the required contrast ratio, see technique [G18: Ensuring that a contrast ratio of at least 4.5:1 exists between text (and images of text) and background behind the text](https://www.w3.org/WAI/WCAG21/Techniques/general/G18.html).
* Explain that images of text present information intended to be read as text. Emphasize that sometimes it is difficult to tell visually if text has been coded as a text or as an image, so coordination among designers, developers, and content authors is needed to determine if the technologies in use can achieve the desired visual presentation. Emphasize that, if an image of text is still required, there needs to be a text alternative that conveys the same information as the image of text. Explain that coding an image of text appropriately is a responsibility of the developer, whereas providing descriptions for images of text is a responsibility shared with the content author.
* Show examples of complex images and graphics, such as maps, diagrams, and charts. Explain that they need to have text descriptions  that allow people to understand and interpret such images without having to look at them. Explain that providing these text alternatives is a designers' responsibility, whereas providing the text descriptions is a responsibility shared with the content author.
* Show examples of different verification systems, such as CAPTCHA, to identify human beings trying to access a service or system. Explain that these mechanisms need to support several sensory characteristics, such as visual, auditory, or cognitive. For references on how to provide accessible CAPTCHA, see technique [G143: Providing a text alternative that describes the purpose of the CAPTCHA](https://www.w3.org/WAI/WCAG21/Techniques/general/G143.html) and [G144: Ensuring that the Web Page contains another CAPTCHA serving the same purpose using a different modality](https://www.w3.org/WAI/WCAG21/Techniques/general/G144.html).

#### Ideas to Assess Knowledge for Topic

Optional ideas to assess knowledge:

* Practical &mdash; Students add complex images to a website, such as charts or diagrams, and ensure they have the required contrast ratio. Assess how students understand the contrast requirements for complex images.
* Short Answer Questions &mdash; Present students with a situation where a human verification system needs to be used and ask them to provide authentication alternatives for other sensory characteristics apart from vision. Assess how students understand the need for providing human verification systems that rely on different sensory characteristics in addition to vision.

{% include excol.html type="end" %}

{% include excol.html type="all" %}

## Ideas to Assess Knowledge for Module

Optional ideas to assess knowledge:

* Portfolio &mdash; Students design the imagery for a website. Assess how students include accessibility requirements in the images in graphics they design, for example contrast ratios,  text alternatives that belong to the design phase, and placeholders for any other text alternative that is planned for later stages of the design and development process.

## Teaching Resources

Suggested resources to support your teaching:

* @@@
* [Images (WAI Web Accessibility Tutorials)](https://www.w3.org/WAI/tutorials/images/) &mdash; Shows how to provide alternatives to images that are accessible to people with disabilities.
* [How People with Disabilities Use the Web](/people-use-web/) &mdash; Provides stories of people with disabilities using the Web; describes types of disabilities and some of the barriers that people encounter using the Web; and introduces types of assistive technologies and adaptive strategies that some people use.
* [WCAG](https://www.w3.org/WAI/standards-guidelines/wcag/) &mdash; Address accessibility of web content on desktops, laptops, tablets, and mobile devices.

