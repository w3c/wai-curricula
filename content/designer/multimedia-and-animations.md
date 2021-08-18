---
title: "[Draft] Module 5: Multimedia and Animations"
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
  next: /curricula/designer-modules/forms-interactions-and-feedback/
---

## Introduction
{:.no-display}

Courses based on this module should:

* explain strategies that people with disabilities use to access multimedia contents, such as audio and video
* explain accessibility requirements for multimedia content, such as audio descriptions of visual information, captions (also known as subtitles), transcripts, and sign languages

## Learning Outcomes for Module

Students should be able to:

* identify accessibility requirements for different types of audio and video content
* design the placement and spacing for alternatives to multimedia content, such as transcripts, audio descriptions, captions, and sign language
* design user experiences that consider audio descriptions of visual information, captions, transcripts, and sign language, including
  * mechanisms for turning on and off such alternatives 
  * ways for users to interact with the alternatives
* assess the need for designing a custom media player based on the project requirements and on existing media players supporting accessibility
* design multimedia player controls that have clear and descriptive names, that are easy to find, and that are always reachable for users
* design multimedia players that support different methods of interaction, including mouse, keyboard, touch, and voice
* design mechanisms to mute and control the volume of auto-playing audio
* design mechanisms to pause, stop, and hide moving, blinking, and auto-updating content, including animations and carousels
* identify related requirements for developers to programmatically associate alternatives and descriptions to their corresponding media content 
* identify related requirements for developers to include accessibility support for multimedia players
* identify related requirements for content authors to provide appropriate text transcripts, captions, audio descriptions, and sign language

{% include excol.html type="all" %}

## Competencies

Skills required for this module:

{% include excol.html type="start" %}

### Students

{% include excol.html type="middle" %}

* [Foundation Prerequisites](/curricula/designer-modules#foundation-prerequisites)
* [Module 1: Flexible and Responsive Design](/curricula/designer-modules/flexible-and-responsive-design/)
* [Module 3: Navigation](/curricula/designer-modules/navigation/)
* [Module 2: Information Design](/curricula/designer-modules/information-design/)
* [Module 4: Images and Graphics](/curricula/designer-modules/images-and-graphics)
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
  * [WCAG Success Criterion 1.2.5 Audio Descriptions (Prerecorded)](https://www.w3.org/WAI/WCAG21/quickref/#audio-description-prerecorded)
  * [WCAG Success Criteria 1.4.2 Audio Control](https://www.w3.org/WAI/WCAG21/quickref/#audio-control)
  * [WCAG Success Criterion 1.4.6 Sign Language (prerecorded](https://www.w3.org/WAI/WCAG21/quickref/#sign-language-prerecorded)
  * [WCAG Success Criterion 2.2.2 Pause, Stop, Hide](https://www.w3.org/WAI/WCAG21/Understanding/pause-stop-hide)
  * [WCAG Success Criterion 2.3.1 Three Flashes or Below Threshold](https://www.w3.org/WAI/WCAG21/quickref/#three-flashes-or-below-threshold)
  * [WCAG Success Criterion 3.2.1 On Focus](https://www.w3.org/WAI/WCAG21/quickref/#on-focus)
  * [WCAG Success Criterion 3.2.5 Change on Request](https://www.w3.org/WAI/WCAG21/quickref/#change-on-request)
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

### Topic: Alternatives to Multimedia Content

{% include excol.html type="middle" %}

Audio descriptions are essential for people who cannot see the visuals. Captions are essential for people who cannot hear the audio. Text transcripts provide an alternative to visual and audio information.

Discuss the need for planning in the design phase to accommodate media alternatives such as audio description of visual information, captions, text transcripts, and sign language. Present mechanisms to turn on and off alternatives to multimedia content depending on user needs. Explain that these mechanisms need to have clear name and need to be always reachable for users. Explain that defining such mechanisms is a designer's responsibility, whereas providing the alternatives is a responsibility shared with the content author.

#### Learning Outcomes for Topic

Students should be able to

* identify accessibility requirements for the different types of multimedia content, such as auio descriptions for visual information, captions, transcripts, and sign languages
* define audio descriptions as descriptions to adequately get the visual information needed to understand the content
* define captions as text versions of the speech and non-speech audio information needed to understand the content
* define text transcripts as text that provides an alternative to visual and audio information
* define sign language as the native language of some deaf people
* design mechanisms for controling the volume ofaudio that plays automatically for more than 3 seconds
* design mechanisms for pausing, stopping, or hiding any content that blinks, moves, or auto-updates, for example audio descriptions, captions, transcripts, sign language
* design mechanisms to provide alternatives for multimedia content, including audio descriptions, captions, transcripts, and sign language
* design mechanisms to turn on and off audio descriptions, captions, and sign language
* design player controls that:
  * have descriptive names
  * are operable by keyboard
  * are easy to find
  * are always reachable for users

#### Teaching Ideas for Topic

Optional ideas to teach the learning outcomes:

* Show examples of text transcripts. Explain that transcripts are alternatives for people who cannot hear the audio information and for people who cannot see the visual information. Explain that allocating the necessary space for the transcripts is a designers' responsibility, whereas providing such transcripts is a responsibility shared with the content author.
* Show examples of captions. Explain that captions are alternatives for people who cannot hear the audio, and that they are useful in other situations. Explain that determining where to place captions is a designers' responsibility, whereas providing such captions is a responsibility shared with the content author.
* Show examples of audio described content. Explain that audio descriptions are alternatives for people who cannot see the video. Explain that defining the mechanisms to enable and disable  audio described content is a designers' responsibility, whereas providing the audio description is a responsibility shared with the content author.
* Show examples of sign language. Explain that sign language is essential for people who are deaf and who do not understand written language well. Explain that defining the mechanisms to enable and disable sign language is a designers' responsibility, whereas providing the sign language interpretation is a responsibility shared with the content author.
* Show examples of accessible and inaccessible media players. Explain how accessible media player  controls have appropriate contrast ratios, are operable by keyboard, and are easy to find. Emphasize that the controls need to remain available even when the media is playing.

#### Ideas to Assess Knowledge for Topic

Optional ideas to assess knowledge:

* Short Answer Questions &mdash; Give students pieces of multimedia content and ask them where they would place their corresponding alternatives. Assess students' understanding of the requirements for alternatives to multimedia content.

{% include excol.html type="end" %}

{% include excol.html type="start" %}

### Topic: Movement and Animations

{% include excol.html type="middle" %}

Show moving content, such as carousels and animations. Present mechanisms to avoid distractions, seizures and physical reactions, and unpredictable keyboard focus management caused by moving content. For example, support for pausing, stopping, or hiding moving content, as well as using flashing that is below the general flash and red flash ratios where possible.

#### Learning Outcomes for Topic

Students should be able to:

* design mechanisms for pausing, stopping, or hiding any content that blinks, moves, or auto-updates, for example animations, carousels, and decorative gimmicks
* create designs that avoid flashing entirely or only flash below the acceptable thresholds
* create designs with enough time for users to read parts of moving content, for example different slides in a carousel
* define visual and non-visual identification of animated content and its different parts, for example identifying a carousel region and its different slides
* define focus order within animated contents, including how to move to different parts of the carousel and how to get to the carousel controls
* design mechanisms that support disabling motion animation triggered by interaction, such as additional animations when scrolling
* design mechanisms for stopping or controlling the volume of any audio that plays automatically for more than 3 seconds

#### Teaching Ideas for Topic

Optional ideas to teach the learning outcomes:

* Show examples of contents that move or blink, such as animations and carousels. Explain that these can cause problems for some users that cannot keep up with the pace of the auto-updating content. Emphasize that, in addition, these animations can cause seizures and physical reactions. For references on how to design user interfaces that allow to pause, stop, and hide moving, blinking, or auto-updating content, see the following techniques:
  * [G4: Allowing the content to be paused and restarted from where it was paused](https://www.w3.org/WAI/WCAG21/Techniques/general/G4),
  * [G11: Creating content that blinks for less than 5 seconds](https://www.w3.org/WAI/WCAG21/Techniques/general/G11),
  * [G152: Setting animated gif images to stop blinking after n cycles (within 5 seconds)](https://www.w3.org/WAI/WCAG21/Techniques/general/G152),
  * [G186: Using a control in the Web page that stops moving, blinking, or auto-updating content](https://www.w3.org/WAI/WCAG21/Techniques/general/G186), and
  * [G187: Using a technology to include blinking content that can be turned off via the user agent](https://www.w3.org/WAI/WCAG21/Techniques/general/G187).
* Show examples of flashing content and explain that they can cause seizures and physical reactions for some people. Emphasize that all components of the content need to be below the general flash and red flash thresholds, as any flashing interferes with the ability to use the whole web page or application. For references on how to design interfaces that support flashing below the general flash and red flash thresholds or that support flashing below 3 seconds, see techniques [G19: Ensuring that no component of the content flashes more than three times in any 1-second period](https://www.w3.org/WAI/WCAG21/Techniques/general/G19.html) and [G15: Using a tool to ensure that content does not violate the general flash threshold or red flash threshold](https://www.w3.org/WAI/WCAG21/Techniques/general/G15.html).
* Show examples of interactions triggered by animations, such as additional movements when scrolling and decorative gimmics. Explain that these animations can cause distraction and vestibular disorders (such as dizziness, nausea, and headaches) for some people. Discuss the use of preferences as well as technology specific properties to reduce or disable such animations.
* Demonstrate the use of a screen reader to navigate an application that plays audio automatically for more than 3 seconds. Explain that the playing audio interferes with the ability to hear the screen reader output. Emphasize that there should be a mechanism to pause or control the volume of that audio. Explain that the operating system often provides such mechanism. For references on how to design interfaces that support mechanisms to pause or control the volume of any audio that plays automatically, see the following techniques:
  * [G60: Playing a sound that turns off automatically within three seconds](https://www.w3.org/WAI/WCAG21/Techniques/general/G60.html),
  * [G170: Providing a control near the beginning of the Web page that turns off sounds that play automatically](https://www.w3.org/WAI/WCAG21/Techniques/general/G170.html), and
  * [G171: Playing sounds only on user request](https://www.w3.org/WAI/WCAG21/Techniques/general/G171.html).

#### Ideas to Assess Knowledge for Topic

Optional ideas to assess knowledge:

* Practical &mdash; Present students with instances of flashing content and ask them to determine if they are below the general flash and red flash thresholds. Assess how students understand accessibility requirements for flashing content.
* Practical &mdash; Present students with a user interface containing animations and ask them to make them accessible. Assess how students define mechanisms to reduce or disable the animations.

{% include excol.html type="end" %}

{% include excol.html type="all" %}

## Ideas to Assess Knowledge for Module

Optional ideas to assess knowledge:

* Portfolio &mdash; Students include accessible video and audio contents on a website. Assess how students understand the accessibility requirements of video and audio content, including transcripts for audio, audio descriptions, and sign language.

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
