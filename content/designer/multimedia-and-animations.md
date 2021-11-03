---
title: "[Draft] Module 6: Multimedia and Animations"
nav_title: "Multimedia and Animations"
permalink: /curricula/designer-modules/multimedia-and-animations/
ref: /curricula/designer-modules/multimedia-and-animations/
lang: en
github:
  repository: w3c/wai-curricula
  path: content/designer/multimedia-and-animations.md
license: creative-commons
acknowledgements: /curricula/acknowledgements/
changelog: /curricula/changelog/
footer: >
  <p><strong>Date:</strong> Updated @@ Month 2021. First published December 2019. CHANGELOG</p>
  <p><strong>Editors:</strong> Daniel Montalvo and <a href="http://www.w3.org/People/shadi/">Shadi Abou-Zahra</a>. Contributors: <a href="https://www.w3.org/WAI/EO/EOWG-members">EOWG Participants</a>. ACKNOWLEDGEMENTS lists contributors and credits.</p>
  <p>Developed by the Education and Outreach Working Group (<a href="http://www.w3.org/WAI/EO/">EOWG</a>). Developed with support from the <a href="https://www.w3.org/WAI/about/projects/wai-guide/">WAI-Guide Project</a> funded by the European Commission (EC) under the Horizon 2020 program (Grant Agreement 822245).</p>
parent_in_h1:
  - ref: /curricula/designer-modules/
    name: nav_title
  - ref: /curricula/
    name: "Curricula on Web Accessibility"
navigation:
  previous: /curricula/designer-modules/images-and-graphics/
  next: /curricula/designer-modules/forms-design/
---

## Introduction
{:.no-display}

Courses based on this module should:

* explain strategies that people with disabilities use to access multimedia content, including audio and video
* explain accessibility requirements for multimedia content, such as description of visual information (also known as audio description, video description, or described video), captions (also known as subtitles), transcripts, and sign languages

## Learning Outcomes for Module

Students should be able to:

* identify accessibility requirements for different types of audio and video content
* design user experiences for description, captions, transcripts, and sign languages, including interactions, placement, and methods to turn on and off the alternatives
* identify accessibility issues associated with media players, including:
  * select media players with support for different methods of interaction, including mouse, keyboard, touch, and voice
  * select media player controls that have clear and descriptive names, that are easy to find, and that are always reachable for users
* define methods to control automatic audio and movement, including:
  * mute and control the volume of auto-playing audio
  * pause, stop, and hide moving, blinking, and auto-updating content, including carousels and other animations
* identify related requirements for:
  * developers to programmatically associate alternatives to their corresponding media content
  * developers to include accessibility support for media players
  * content authors to provide appropriate description, captions, transcripts, and sign languages

{% include excol.html type="all" %}

## Competencies

Skills required for this module:

{% include excol.html type="start" %}

### Students

{% include excol.html type="middle" %}

* [Foundation Prerequisites](/curricula/designer-modules#foundation-prerequisites)
* Prior [Designer Modules](/curricula/designer-modules/)
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
  * [WCAG Success Criterion 1.2.1	Audio-only and Video-only (Prerecorded)](https://www.w3.org/WAI/WCAG21/quickref/#captions-prerecorded)
  * [WCAG Success Criterion 1.2.2	Captions (Prerecorded)](https://www.w3.org/WAI/WCAG21/quickref/#captions-prerecorded)
  * [WCAG Success Criterion 1.2.3	Audio Description or Media Alternative (Prerecorded)](https://www.w3.org/WAI/WCAG21/quickref/#audio-description-or-media-alternative-prerecorded)
  * [WCAG Success Criterion 1.2.4 Captions (Live)](https://www.w3.org/WAI/WCAG21/quickref/#captions-live)
  * [WCAG Success Criterion 1.2.5 Audio Description (Prerecorded)](https://www.w3.org/WAI/WCAG21/quickref/#audio-description-prerecorded)
  * [WCAG Success Criteria 1.4.2 Audio Control](https://www.w3.org/WAI/WCAG21/quickref/#audio-control)
  * [WCAG Success Criterion 1.4.6 Sign Language (prerecorded](https://www.w3.org/WAI/WCAG21/quickref/#sign-language-prerecorded)
  * [WCAG Success Criterion 2.2.2 Pause, Stop, Hide](https://www.w3.org/WAI/WCAG21/Understanding/pause-stop-hide)
  * [WCAG Success Criterion 2.3.1 Three Flashes or Below Threshold](https://www.w3.org/WAI/WCAG21/quickref/#three-flashes-or-below-threshold)
  * [WCAG Success Criterion 3.2.1 On Focus](https://www.w3.org/WAI/WCAG21/quickref/#on-focus)
  * [WCAG Success Criterion 3.2.5 Change on Request](https://www.w3.org/WAI/WCAG21/quickref/#change-on-request)
* In-depth knowledge of:
  * [Foundation Prerequisites](/curricula/designer-modules#foundation-prerequisites)
  * Prior [Designer Modules](/curricula/designer-modules/)
  * Visual Design
  * Prototyping
  * Responsive Design
  * Information Architecture

{% include excol.html type="end" %}

## Topics to Teach

Topics to achieve the learning outcomes:

{% include excol.html type="start" %}

### Topic: Alternatives to Multimedia Content

{% include excol.html type="middle" %}

Description of visual information is essential for people who cannot see the visuals. Captions are essential for people who cannot hear the audio. Text transcripts provide an alternative to visual and audio information.

Discuss the need for planning in the design phase to accommodate alternatives to multimedia content such as description, captions, text transcripts, and sign languages. Present methods to turn on and off alternatives to multimedia content depending on user needs. Explain that these methods need to have clear names and need to be always reachable for users. Explain that defining such methods is a designer's responsibility, whereas providing the alternatives is a responsibility shared with the content author.

#### Learning Outcomes for Topic

Students should be able to

* identify accessibility requirements for the different types of multimedia content, including description, captions, transcripts, and sign languages
* describe the following alternatives to multimedia content:
  * description of visual information
  * captions
  * transcripts
  * sign language
* design user experiences of alternatives for multimedia content, including:
  * placement of the alternatives
  * methods to turn on and off the alternatives
* evaluate the need for designing custom media players and select existing media players with support for accessibility where possible
* describe characteristics of accessible media player controls, including:
  * keyboard support
  * visible keyboard focus indicators
  * clear labels
  * sufficient contrast between colors for text, controls, and backgrounds
  
#### Teaching Ideas for Topic

Optional ideas to teach the learning outcomes:

* Show examples of description of visual information. Emphasize how these alternatives describe the visual information (including text) for people who cannot see the videos. Explain that different standards and policies may refer to description of visual information using different terms, such as audio description, video description, and described videos. Explain that defining the methods to turn on and off the description is a designers' responsibility, whereas providing the description is a responsibility shared with the content author.
* Show examples of captions. Explain that captions are a synchronized text version of the speech and non-speech audio information needed to understand the content. Explain that different standards and policies may refer to captions using different terms, such as subtitles. Explain that defining the methods to turn on and off the description is a designers' responsibility, whereas providing the description is a responsibility shared with the content author. Explain that determining where to place captions is a designers' responsibility, whereas providing such captions is a responsibility shared with the content author.
* Show examples of text transcripts. Explain that transcripts are a text version of the speech and non-speech audio information needed to understand the content. Explain that defining the placement and spacing for the transcripts is a designers' responsibility, whereas providing the transcripts is a responsibility shared with the content author.
* Show examples of sign language. Explain that sign language is essential for people who are deaf and who do not understand written language well. Explain that defining the methods to enable and disable sign language is a designers' responsibility, whereas providing the sign language interpretation is a responsibility shared with the content author.
* Show examples of accessible and inaccessible media players. Emphasize that it is generally more reliable to use an existing media player with support for accessibility than to design one from scratch. Emphasize how accessible media players are operable by keyboard, make keyboard focus visible, have clear labels, have appropriate contrast ratios, and are easy to find. For an overview on skills needed to develop a media player, expected functionality, and existing players, see the resource Making Audio and Video Media Accessible, [Media players](/media/av/player/).

#### Ideas to Assess Knowledge for Topic

Optional ideas to assess knowledge:

* Short Answer Questions &mdash; Ask students what description, captions, transcripts, and sign language mean in the context of accessible media content. Assess how students define alternatives to multimedia content.
* Practical &mdash; Give students pieces of multimedia content and ask them to define the user experiences for the alternatives of those pieces. Assess how students define placement, interactions, and methods to turn the alternatives on and off.

{% include excol.html type="end" %}

{% include excol.html type="start" %}

### Topic: Movement and Animations

{% include excol.html type="middle" %}

Show moving content, such as carousels and animations. Present methods to avoid distractions, seizures and physical reactions, and unpredictable keyboard focus management caused by moving content. For example, support for pausing, stopping, or hiding moving content, as well as using flashing that is below the accepted ratios where possible.

#### Learning Outcomes for Topic

Students should be able to:

* define methods for pausing, stopping, or hiding any content that blinks, moves, or auto-updates, for example animations, carousels, and decorative gimmicks
* create designs that avoid flashing entirely or only flash below the acceptable thresholds
* create designs with enough time for users to read parts of moving content, for example different slides in a carousel
* define visual and non-visual identification of animated content and its different parts, for example identifying a carousel region and its different slides
* define focus order within animated content, including how to move to different parts of the carousel and how to get to the carousel controls
* define methods for stopping or controlling the volume of any audio that plays automatically for more than 3 seconds

#### Teaching Ideas for Topic

Optional ideas to teach the learning outcomes:

* Show examples of content that moves or blinks, such as animations and carousels. Explain that these animations can cause problems for some users that cannot keep up with the pace of the auto-updating content. Emphasize that, in addition, these animations can cause seizures and physical reactions. For references on how to design interfaces that allow to pause, stop, and hide moving, blinking, or auto-updating content, see the following techniques:
  * [G4: Allowing the content to be paused and restarted from where it was paused](https://www.w3.org/WAI/WCAG21/Techniques/general/G4),
  * [G11: Creating content that blinks for less than 5 seconds](https://www.w3.org/WAI/WCAG21/Techniques/general/G11),
  * [G152: Setting animated gif images to stop blinking after n cycles (within 5 seconds)](https://www.w3.org/WAI/WCAG21/Techniques/general/G152),
  * [G186: Using a control in the Web page that stops moving, blinking, or auto-updating content](https://www.w3.org/WAI/WCAG21/Techniques/general/G186), and
  * [G187: Using a technology to include blinking content that can be turned off via the user agent](https://www.w3.org/WAI/WCAG21/Techniques/general/G187).
* Show examples of flashing content and explain that it can cause seizures and physical reactions for some people. Emphasize that all interface components need to be below the general flash and red flash thresholds, as any flashing interferes with the ability to use the whole interface. For references on how to design interfaces that flash below the general flash and red flash thresholds or that flash below 3 seconds, see techniques [G19: Ensuring that no component of the content flashes more than three times in any 1-second period](https://www.w3.org/WAI/WCAG21/Techniques/general/G19.html) and [G15: Using a tool to ensure that content does not violate the general flash threshold or red flash threshold](https://www.w3.org/WAI/WCAG21/Techniques/general/G15.html).
* Show examples of interactions triggered by animations, such as additional movements when scrolling and decorative gimmicks. Explain that these animations can cause distraction and vestibular disorders (such as dizziness, nausea, and headaches) for some people. Discuss the use of preferences as well as technology specific properties to reduce or disable such animations.
* Demonstrate the use of a screen reader to navigate an application that plays audio automatically for more than 3 seconds. Explain that the playing audio interferes with the ability to hear the screen reader output. Emphasize that there should be a method to pause or control the volume of that audio. Explain that the operating system often provides such method. For references on how to design interfaces with methods to pause or control the volume of any audio that plays automatically, see the following techniques:
  * [G60: Playing a sound that turns off automatically within three seconds](https://www.w3.org/WAI/WCAG21/Techniques/general/G60.html),
  * [G170: Providing a control near the beginning of the Web page that turns off sounds that play automatically](https://www.w3.org/WAI/WCAG21/Techniques/general/G170.html), and
  * [G171: Playing sounds only on user request](https://www.w3.org/WAI/WCAG21/Techniques/general/G171.html).

#### Ideas to Assess Knowledge for Topic

Optional ideas to assess knowledge:

* Practical &mdash; Give students flashing content and ask them to determine if it is below the general flash and red flash thresholds. Assess how students understand accessibility requirements for flashing content.
* Practical &mdash; Give students an interface containing animations and ask them to make them accessible. Assess how students define methods to reduce or disable the animations.

{% include excol.html type="end" %}

{% include excol.html type="all" %}

## Ideas to Assess Knowledge for Module

Optional ideas to assess knowledge:

* Portfolio &mdash; Students include accessible video and audio content on a website. Assess how students understand the accessibility requirements of video and audio content, including description, captions, transcripts, and sign language.

## Teaching Resources

Suggested resources to support your teaching:

* [Making Audio and Video Media Accessible](https://www.w3.org/WAI/media/av/) &mdash; Covers captions/subtitles, audio description of visual information, descriptive transcripts, and sign language. Includes guidance for creating new videos, and on media player accessibility. Introduces user experiences and benefits to organizations.
* [Designing for Web Accessibility](/tips/designing/) &mdash; Tips for user interface and visual design.
* [How People with Disabilities Use the Web](/people-use-web/) &mdash; Provides stories of people with disabilities using the Web; describes types of disabilities and some of the barriers that people encounter using the Web; and introduces types of assistive technologies and adaptive strategies that some people use.
* [Video Captions (Web Accessibility Perspectives)](https://www.w3.org/WAI/perspective-videos/captions/) &mdash; Is one of the Web accessibility perspectives videos that show accessibility features and how they impact people with disabilities.
* [Keyboard Compatibility (Web Accessibility Perspectives)](https://www.w3.org/WAI/perspective-videos/keyboard/) &mdash; Is one of the Web accessibility perspectives videos that show accessibility features and how they impact people with disabilities.
* [Colors with Good Contrast (Web Accessibility Perspective)](/perspective-videos/contrast/) &mdash; Is one of the Web accessibility perspectives videos that show accessibility features and how they impact people with disabilities.
* [Clear Layout and Design (Web Accessibility Perspective)](/perspective-videos/layout/) &mdash; Is one of the Web accessibility perspectives videos that show accessibility features and how they impact people with disabilities.
* [Large Links, Buttons, and Controls (Web Accessibility Perspectives)](/perspective-videos/controls/) &mdash; Is one of the Web accessibility perspectives videos that show accessibility features and how they impact people with disabilities.
* [WCAG](https://www.w3.org/WAI/standards-guidelines/wcag/) &mdash; Address accessibility of web content on desktops, laptops, tablets, and mobile devices.
