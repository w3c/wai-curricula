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

* explain strategies that people with disabilities use to access information contained in images and graphics
* explain accessibility requirements related to images and graphics, such as text alternatives and contrast ratios

## Learning Outcomes for Module

Students should be able to:

* explain how images and graphics help people with disabilities to process information, identify content, and understand functionality
* explain how text alternatives are essential for people with disabilities to understand the information contained in images
* provide meaningful and consistent text alternatives for functional images, such as those included in buttons, links, icons, and logos
* design consistent imagery to help users recognize the purpose of icons, thumbnails, and other graphical components
* explain the issues associated with images of text, and explain how to avoid these when the desired visual presentation can be achieved by the technology in use
* cooperate with developers and content authors to provide the appropriate alternative for images and graphics included in the design phase based on the image purpose
* identify related requirements for developers to code images and text alternatives appropriately
* identify related requirements for content authors to provide appropriate descriptions for images included in the authoring phase, such as charts, diagrams, and other complex graphics

{% include excol.html type="all" %}

## Competencies

Skills required for this module:

{% include excol.html type="start" %}

### Students

{% include excol.html type="middle" %}

* [Foundation Prerequisites](/curricula/designer-modules#foundation-prerequisites)
* [Module 1: #foundation-prerequisitesFlexible Color, Layout, and Design](/curricula/designer-modules/flexible-color-layout-and-design/)
* [Module 3: Navigation](/curricula/designer-modules/navigation/)
* [Module 2: Information Design](/curricula/designer-modules/information-design/)
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
  * [WCAG Success Criterion 1.1.1 Non-Text Content](https://www.w3.org/WAI/WCAG21/quickref/#non-text-content)
  * [WCAG Success Criterion 1.4.5 Images of Text](https://www.w3.org/WAI/WCAG21/quickref/#images-of-text)
  * [WCAG Success Criterion 1.4.9 Images of Text (No Exception)](https://www.w3.org/WAI/WCAG21/quickref/#images-of-text-no-exception)
* In-depth knowledge of:
  * [Foundation Prerequisites](/curricula/designer-modules#foundation-prerequisites)
  * Visual Design
  * Prototyping
  * Responsive Design
  * Information Architecture
  * Content Design
  * Technical Writing

{% include excol.html type="end" %}

## Topics to Teach

Topics to achieve the learning outcomes:

{% include excol.html type="start" %}

### Topic: Functional Images

{% include excol.html type="middle" %}

Functional images convey functionality of a user interface component. For example search, print, and save functionality. Explain requirements related to color and contrast to help users distinguish these images from other components. Show examples of graphical links and buttons as well as logos. Discuss with students how they would describe each of those examples.

#### Learning Outcomes for Topic

Students should be able to:

* provide text alternatives for functional images by using the following mechanisms:
  * text alternatives for images
  * combinations of text alternatives of images and adjacent text inside components
  * adjacent text inside components to understand its function
* use consistent naming and imagery for components that have the same functionality across web pages
* explain the benefits of using text labels and decorative images for functionality, instead of using images with text alternatives that are only available to some users, such as screen reader users
* apply appropriate contrast ratios for functional images

#### Teaching Ideas for Topic

Optional ideas to teach the learning outcomes:

* Show examples of different images used to convey functionality, such as for printing, searching, or saving a document. Explain that it is necessary to provide  and equivalent, succinct text alternative that explains the function rather than a description of the image. For reference on how  to provide a text alternative for an image conveying function, see technique [G94: Providing short text alternative for non-text content that serves the same purpose and presents the same information as the non-text content](https://www.w3.org/WAI/WCAG21/Techniques/general/G94.html).

#### Ideas to Assess Knowledge for Topic

Optional ideas to assess knowledge:

* Practical &mdash; Give students a set of images conveying function, such as a printer for a "print" button and a magnifying glass for a "search" button. Ask students to provide an appropriate text alternative. Assess how students identify images that convey function and how they provide text alternatives that describe the functionality of the component the image is attached to.
* Practical &mdash; Ask students to design a series of graphical buttons and links in a way that they are perceivable and distinguishable by all users. Assess how students apply accessibility requirements, such as contrast ratios, to graphical buttons and links.

{% include excol.html type="end" %}

{% include excol.html type="start" %}

### Topic: Informative Images

{% include excol.html type="middle" %}

Informative images convey information that is necessary to understand the content. Their description requires generally a short phrase or sentence. Show examples of images that convey information, such as pictures in a piece of news. Discuss with students how they would describe them. 

Explain that providing text alternatives for informative images is a responsibility shared with the content author.

#### Learning Outcomes for Topic

Students should be able to:

* provide text alternatives that present equivalent information as that contained in informative images, by using the following mechanisms:
  * boilerplate descriptions that would then be completed and maintained through the development and authoring phases
  * adjacent textual information to complement images and icons, for example in a news headline
  * text alternatives that describe the information conveyed by images
* apply the appropriate contrast ratio to images that are necessary to understand the contents
* use styled text instead of images of text when the technology in use can provide the desired visual presentation
* provide alternatives to CAPTCHA and biometrics, for example by providing visual, auditory, and logical CAPTCHA
* explain the issues associated with relying only on one form of biometrics and CAPTCHA, and describe alternative approaches for authentication
* identify related requirements for developers to code alternative texts for informative images

### Teaching Ideas for Topic

Optional ideas to teach the learning outcomes:

* Show examples of different images that convey information, such as images to provide instructions, and to identify people and objects. Explain that such information needs to be provided using text alternatives, so that the purpose of the image can be understood without having to look at the image. Emphasize that these alternatives may require coordination among designers, developers, and content authors. For references on how to provide text alternatives for images, see [G82: Providing a text alternative that identifies the purpose of the non-text content](https://www.w3.org/WAI/WCAG21/Techniques/general/G82.html).
* Explain that images of text present information intended to be read as text. Emphasize that sometimes it is difficult to tell visually if text has been coded as a text or as an image, so coordination among designers, developers, and content authors is needed to determine if the technologies in use can achieve the desired visual presentation. Emphasize that, if an image of text is still required, there needs to be a text alternative that conveys the same information as the image of text. Explain that coding an image of text appropriately is a responsibility of the developer, whereas providing descriptions for images of text is a responsibility shared with the content author.
* Show examples of different verification systems, such as CAPTCHA, to identify human beings trying to access a service or system. Explain that these mechanisms need to support several modalities, such as visual, auditory, and cognitive. For references on how to provide accessible CAPTCHA, see technique [G143: Providing a text alternative that describes the purpose of the CAPTCHA](https://www.w3.org/WAI/WCAG21/Techniques/general/G143.html) and [G144: Ensuring that the Web Page contains another CAPTCHA serving the same purpose using a different modality](https://www.w3.org/WAI/WCAG21/Techniques/general/G144.html).

#### Ideas to Assess Knowledge for Topic

Optional ideas to support assessment.

* Practical &mdash; Present students with an image of text and ask them to cooperate with other team roles such as developers and content authors to ensure the image has an equivalent alternative text. Assess how students identify the need for alternative text for images of text.
* Short Answer Questions &mdash; Present students with a situation where a human verification system needs to be used and ask them to provide authentication alternatives for other sensory characteristics apart from vision. Assess how students understand the need for providing human verification systems that rely on different sensory characteristics in addition to vision.

{% include excol.html type="end" %}

{% include excol.html type="start" %}

### Topic: Complex Images

{% include excol.html type="middle" %}

Complex images are those whose description requires more than a short phrase or sentence. Show examples of complex images, including diagrams and charts, and explain accessibility requirements that these images have, such as appropriate contrast ratios and appropriate text descriptions.

Explain that coordination among different team members is required to assess the use of complex images based on their adjacent components (for example text and other images) and on the overall context, so that the relations are perceived and understood visually and through the provided descriptions.

#### Learning Outcomes for Topic

Students should be able to:

* use appropriate contrast ratios for complex images when these images are required to understand the contents
* identify related requirements for content authors to provide descriptive, equivalent textual information to understand complex images and graphics, such as diagrams, charts, maps and infographics
* determine if and how complex images are operated using the mouse, keyboard, and other input devices

#### Teaching Ideas for Topic

Optional ideas to teach the learning outcomes:

* Provide examples of complex images and graphics, such as charts, diagrams, maps, and infographics. Explain that they need to have a contrast ratio of at least 3:1, as they are necessary to understand the content. For references on how to provide complex graphics that meet the required contrast ratio, see technique [G18: Ensuring that a contrast ratio of at least 4.5:1 exists between text (and images of text) and background behind the text](https://www.w3.org/WAI/WCAG21/Techniques/general/G18.html).
* Explain that complex images also need to have text descriptions that allow people to understand and interact with such images without having to look at them. Explain that providing these text alternatives is a designers' responsibility, whereas providing the text descriptions is a responsibility shared with the content author.

#### Ideas to Assess Knowledge for Topic

Optional ideas to assess knowledge:

* Practical &mdash; Students add complex images to a website, such as charts or diagrams, and ensure they have the required contrast ratio. Assess how students understand the contrast requirements for complex images.
* Practical &mdash; Students cooperate with developers and content authors to implement a map in a way that everybody can understand its meaning and interact with it. Assess how students identify the need for text alternatives for complex images and cooperate with other team members to ensure such alternatives exist.

{% include excol.html type="end" %}

{% include excol.html type="start" %}

### Topic: Decorative Images

{% include excol.html type="middle" %}

Decorative images are used for ornamental purposes and convey no information or function. Build on [Module 1: Flexible Color, Layout, and Design](/curricula/designer-modules/flexible-color-layout-and-design/) to explain that decorative images also need to adhere to accessibility requirements such as use of color, ability to resize, and flexibility. Decorative images require empty text alternatives, so that they can be ignored by assistive technologies, and reduce noise. Explain that determining if an image is decorative is a responsibility shared with the content author.

#### Learning Outcomes for Topic

Students should be able to:

* describe the differences between decorative and non-decorative images depending on the type of information conveyed by the image, the presence of similar information in the adjacent content, and the overall context
* describe different ways to present information contained in an image in the surrounding content so that the image can be considered decorative
* assess the use of decorative images based on other images in the content and on the overall context where it is included
* explain how the overuse of decorative images could become distracting for some users and slow down loading times and interaction for other users
* identify related requirements for developers to code decorative images so that they are skipped by assistive technologies

#### Teaching Ideas for Topic

Optional ideas to teach the learning outcomes:

* Show examples of images and graphics that do not convey function or information, such as ornamental icons. Explain that they serve ornamental purposes as long as people can understand and interact with the user interface with or without such icons. Explain that deciding what is the images role is a designers' responsibility, whereas coding the images so that they render with the appropriate role is a developers' responsibility.

#### Ideas to Assess Knowledge for Topic

Optional ideas to assess knowledge:

* Practical &mdash; Ask students to provide decorative images to illustrate a text article and ask them to ensure these icons are visible in different screen sizes and devices. Assess how students understand the need for decorative images to adapt to the different user needs and preferences.

{% include excol.html type="end" %}

{% include excol.html type="all" %}

## Ideas to Assess Knowledge for Module

Optional ideas to assess knowledge:

* Portfolio &mdash; Students design the imagery for a website. Assess how students include accessibility requirements in the images in graphics they design, for example contrast ratios,  text alternatives that belong to the design phase, and placeholders for any other text alternative that is planned for later stages of the design and development process.

## Teaching Resources

Suggested resources to support your teaching:

* [Designing for Web Accessibility](/tips/designing/) &mdash; Tips for user interface and visual design.
* [Images (WAI Web Accessibility Tutorials)](https://www.w3.org/WAI/tutorials/images/) &mdash; Shows how to provide alternatives to images that are accessible to people with disabilities.
* [[How People with Disabilities Use the Web]](/people-use-web/) &mdash; Provides stories of people with disabilities using the Web; describes types of disabilities and some of the barriers that people encounter using the Web; and introduces types of assistive technologies and adaptive strategies that some people use.
* [Keyboard Compatibility (Web Accessibility Perspectives)](https://www.w3.org/WAI/perspective-videos/keyboard/) &mdash; Is one of the Web accessibility perspectives videos that show accessibility features and how they impact people with disabilities.
* [Colors with Good Contrast (Web Accessibility Perspective)](/perspective-videos/contrast/) &mdash; Is one of the Web accessibility perspectives videos that show accessibility features and how they impact people with disabilities.
* [Clear Layout and Design (Web Accessibility Perspective)](/perspective-videos/layout/) &mdash; Is one of the Web accessibility perspectives videos that show accessibility features and how they impact people with disabilities.
* [WCAG](https://www.w3.org/WAI/standards-guidelines/wcag/) &mdash; Address accessibility of web content on desktops, laptops, tablets, and mobile devices.

