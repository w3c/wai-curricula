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
* explain accessibility requirements related to images and graphics, such as text alternatives for images

## Learning Outcomes for Module

Students should be able to:

* explain how images affect processing of information, content identification, and understanding of functionality by people with disabilities
* identify and describe different uses of images, including for informative, functional, and decorative purposes
* provide appropriate text alternatives for graphical components included in the design phase, such as logos, links, and menu items
* design user interfaces with alternative systems to verify captcha and other methods to verify human interaction 
* provide images with appropriate contrast ratios and ensure images  resize as required
* identify related requirements for developers to code images and text alternatives appropriately
* identify related requirements for content authors to provide appropriate text alternatives for images included in the authoring phase
* identify related requirements for content authors to present information as text wherever possible, instead of using images of text

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
  * @@@

{% include excol.html type="end" %}

## Topics to Teach

Topics to achieve the learning outcomes:

{% include excol.html type="start" %}

### Topic: Ornamental Graphics

{% include excol.html type="middle" %}

Decorative images are those which convey no information or function and are used for ornamental purposes. Discuss examples of these types of images and explain accessibility requirements that these images have, such as contrast ratios and ability of the image to resize.

#### Learning Outcomes for Topic

Students should be able to:

* identify and describe different uses of images with decorative meaning, such as visual and ornamental  
* provide decorative images with appropriate contrast ratios when these images are necessary to understand the content
* provide decorative images that resize according to user needs and preferences
* identify related requirements for developers to code decorative images appropriately

#### Teaching Ideas for Topic

Optional ideas to teach the learning outcomes:

* Show examples of borders and icons that do not convey function or information. Explain that they serve ornamental purposes.
* Provide examples of images and graphics that are necessary to understand the overall content and explain that they have a contrast ratio requirement of at least 3:1. 

#### Ideas to Assess Knowledge for Topic

Optional ideas to support assessment:

* Practical &mdash; Ask students to provide decorative images to illustrate a text article and ask them to ensure these icons are visible in different screen sizes and devices. Assess how students understand the requirement for decorative images to have appropriate contrast ratios and to resize depending on the user needs and preferences.

{% include excol.html type="end" %}

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

### Topic: Data Visualization

[to be developed].

{% include excol.html type="all" %}

## Ideas to Assess Knowledge for Module

Optional ideas to support assessment:

[To be developed.]

* Portfolio &mdash; Students design the imagery for a website. Assess how students include accessibility requirements in the images in graphics they design.
## Teaching Resources

Suggested resources to support your teaching:

[To be developed.]
