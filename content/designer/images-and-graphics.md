---
title: "[Draft] Module 5: Images and Graphics"
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

* explain strategies that people with disabilities use to interact with images
* explain accessibility requirements related to images and graphics, such as text alternatives, text descriptions, or contrast ratios

## Learning Outcomes for Module

Students should be able to:

* explain how images affect processing of information, content identification, and understanding of functionality by people with disabilities
* identify and describe different uses of images, for example informative, functional, and decorative purposes
* provide appropriate text alternatives for graphical components included in the design phase, such as logos, links, and menu items
* design user interfaces with alternative systems to verify captcha and other methods to verify human interaction 
* provide images with appropriate contrast ratios
* create user interfaces that present information as text wherever possible, instead of using images of text
* identify related requirements for developers to code images and text alternatives appropriately
* identify related requirements for content authors to provide appropriate text alternatives for images included in the authoring phase, such as complex graphics and charts

{% include excol.html type="all" %}

## Competencies

Skills required for this module:

{% include excol.html type="start" %}

### Students

{% include excol.html type="middle" %}

* [Prerequisites for students](/curricula/designer-modules#prerequisites-for-students)
* [Module 2: Flexible and Responsive Design](/curricula/designer-modules/flexible-and-responsive-design/)
* [Module 3: Navigation](/curricula/designer-modules/navigation/)
* [Module 4: Information Design](/curricula/designer-modules/information-design/)

{% include excol.html type="end" %}

{% include excol.html type="start" %}

### Instructors

{% include excol.html type="middle" %}

* In-depth knowledge of:
  * [Prerequisites for students](/curricula/designer-modules#prerequisites-for-students)
* Applied expertise in teaching:
  * [WCAG Success Criterion 1.1.1 Non-Text Content](https://www.w3.org/WAI/WCAG21/quickref/#non-text-content)
  * [WCAG Success Criterion 1.4.5 Images of Text](https://www.w3.org/WAI/WCAG21/quickref/#images-of-text)
  * [WCAG Success Criterion 1.4.9 Images of Text (No Exception)](https://www.w3.org/WAI/WCAG21/quickref/#images-of-text-no-exception)

{% include excol.html type="end" %}

## Topics to Teach

Topics to achieve the learning outcomes:

{% include excol.html type="start" %}

### Topic: Text Alternatives

{% include excol.html type="middle" %}

Explain several uses of text alternatives, such as to describe the function of graphical user interface component (functional images) and to describe the images so that users can understand their purpose without looking at them (informational images). Explain that describing the functions of user graphical interface components is a designer's responsibility, whereas providing text alternatives for informative images is a responsibility shared with the content author.

#### Learning Outcomes for Topic

Students should be able to:

* identify situations where it is necessary to provide text alternatives that present equivalent information as that contained in the image
* provide short text alternatives for controls and components that accept user input, for example search, print, and save buttons
* provide text alternatives that identify and describe the purpose of human verification systems, such as captcha 
* collaborate with other team members to implement several modalities of captcha that rely on other sensory characteristics apart from vision, such as visual, auditory, and logical
* describe related requirements for content authors to provide descriptive, equivalent textual information to understand complex images and graphics, such as diagrams or charts

#### Teaching Ideas for Topic

Optional ideas to teach the learning outcomes:

* Show examples of different images used to convey functionality, such as for printing, searching, or saving a document. Explain that it is necessary to provide  and equivalent, succinct text alternative that explains the function rather than a description of the image. For reference on how  to provide a text alternative for an image conveying function, see technique [G94: Providing short text alternative for non-text content that serves the same purpose and presents the same information as the non-text content](https://www.w3.org/WAI/WCAG21/Techniques/general/G94.html).
* Show examples of different images that convey information, such as images to provide instructions, or to identify objects. Explain that such information needs to be provided using text alternatives, so that the purpose of the image can be understood without having to look at the image. Emphasize that these alternatives may require coordination between designers, developers, and content authors. For references on how to provide text alternatives for images, see [G82: Providing a text alternative that identifies the purpose of the non-text content](https://www.w3.org/WAI/WCAG21/Techniques/general/G82.html).
* Show examples of different verification systems, such as captcha, to identify human beings trying to access a service or system. Explain that these mechanisms need to support several sensory characteristics, such as visual, auditory, or cognitive. For references on how to provide accessible captcha, see [G143: Providing a text alternative that describes the purpose of the CAPTCHA](https://www.w3.org/WAI/WCAG21/Techniques/general/G143.html) and [G144: Ensuring that the Web Page contains another CAPTCHA serving the same purpose using a different modality](https://www.w3.org/WAI/WCAG21/Techniques/general/G144.html).

#### Ideas to Assess Knowledge for Topic

Optional ideas to support assessment:

* Practice &mdash; Give students a set of images conveying function, such as print or search buttons, and ask them to provide their corresponding text alternative. Assess how students identify images that convey function and provide their corresponding text alternative.
* Short Answer Questions &mdash; Present students with a situation where a human verification system needs to be used and ask them to provide authentication alternatives for other sensory characteristics apart from vision. Assess how students understand the need for providing human verification systems that rely on different sensory characteristics in addition to captcha.

{% include excol.html type="end" %}

{% include excol.html type="start" %}

### Topic: Data Visualization

{% include excol.html type="middle" %}

Images of text are those which are intended to be read as text, but are coded as an image. Complex images are those whose description requires more than a short phrase. Show examples of these types of images and explain that coordination among different team members is required to create accessible complex images. Explain accessibility requirements that these images have, such as appropriate contrast ratios.

#### Learning Outcomes for Topic

Students should be able to:

* create user interfaces that support appropriate contrast ratios for complex images when they are required to understand the contents
* create user interfaces that support use of text instead of images of text as much as possible
* identify related requirements for content authors to provide descriptions for complex images that serve the same purpose as the graphical object

#### Teaching Ideas for Topic

Optional ideas to teach the learning outcomes:

* Provide examples of complex images and graphics, such as charts and diagrams. Explain that they need to have a contrast ratio requirement of at least 3:1, as they are necessary to understand the content. For references on how to provide complex graphics that meet the required contrast ratio, see technique [G18: Ensuring that a contrast ratio of at least 4.5:1 exists between text (and images of text) and background behind the text](https://www.w3.org/WAI/WCAG21/Techniques/general/G18.html).
* Explain that images of text present information intended to be read as text. Emphasize that sometimes it is difficult to tell visually if text has been coded as a text or as an image. Explain that coding an image of text appropriately is a responsibility of the developer, whereas providing descriptions for images of text is a responsibility shared with the content author.
* Refer back to examples of complex images and graphics. Explain that they need to have text alternatives and descriptions  that allow people to understand and interpret such images without having to look at them. Explain that providing these text alternatives is a designers responsibility, whereas providing the text descriptions is a responsibility shared with the content author.

#### IDeas to Assess Knowledge for Topic

Optional ideas to assess knowledge:

* Practical &mdash; Students add complex images to a website, such as charts or diagrams, and ensure they have the required contrast ratio. Assess how students understand the contrast requirements for complex images.

{% include excol.html type="end" %}

{% include excol.html type="start" %}

### Topic: Ornamental Graphics

{% include excol.html type="middle" %}

Decorative images are used for ornamental purposes and convey no information or function. Explain that these images do not require text alternatives, as these would add clutter to the information that assistive technologies provide to users.

#### Learning Outcomes for Topic

Students should be able to:

* identify and describe different uses of images with decorative purpose, such as ornamental  
* create user interfaces with decorative images that do not overlap with user interface components and contents when viewed using different screen sizes, configurations, and setups
* identify related requirements for developers to code decorative images so that they are ignored by assistive technologies

#### Teaching Ideas for Topic

Optional ideas to teach the learning outcomes:

* Show examples of borders and icons that do not convey function or information. Explain that they serve ornamental purposes.

#### Ideas to Assess Knowledge for Topic

Optional ideas to support assessment:

* Practical &mdash; Ask students to provide decorative images to illustrate a text article and ask them to ensure these icons are visible in different screen sizes and devices. Assess how students understand the need for decorative images to adapt to the different user needs and preferences.

{% include excol.html type="end" %}

{% include excol.html type="all" %}

## Ideas to Assess Knowledge for Module

Optional ideas to support assessment:

[To be developed.]

* Portfolio &mdash; Students design the imagery for a website. Assess how students include accessibility requirements in the images in graphics they design.
## Teaching Resources

Suggested resources to support your teaching:

[To be developed.]
