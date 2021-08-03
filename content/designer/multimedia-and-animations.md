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
navigation:
  previous: /curricula/designer-modules/images-and-graphics/
  next: /curricula/designer-modules/interaction-and-feedback/
---

## Introduction
{:.no-display}

Courses based on this module should:

* explain strategies that people with disabilities use to access multimedia contents, such as audio and video
* explain accessibility requirements for multimedia content, such as transcripts for audio and visual information, captions (also known as subtitles), audio descriptions, and sign language

## Learning Outcomes for Module

Students should be able to:

* identify accessibility requirements for different types of audio and video content
* design user interfaces that consider  placement and spacing for alternatives to multimedia content, such as transcripts, audio descriptions, captions, and sign language
* design user interfaces that support enabling and disabling transcripts, audio descriptions, captions, and sign language
* design user interfaces with multimedia player controls that have clear and descriptive names, that are easy to find, and that do not disappear when the media starts playing
* design user interfaces with mechanisms to pause, stop, and hide any moving, blinking, and auto-updating content, including animations and carousels
* design user interfaces with mechanisms to stop or control the volume of auto-playing audio
* identify related requirements for developers to programmatically associate alternatives and descriptions to their corresponding media content and to include accessibility support for multimedia players
* identify related requirements for content authors to provide appropriate text transcripts, captions, audio descriptions, and sign language

{% include excol.html type="all" %}

## Competencies

Skills required for this module:

{% include excol.html type="start" %}

### Students

{% include excol.html type="middle" %}

* [Foundation Prerequisites](/curricula/designer-modules#foundation-prerequisites)
* [Module 1: Flexible and Responsive Design](/curricula/designer-modules/flexible-and-responsive-design/)
* [Module 2: Navigation](/curricula/designer-modules/navigation/)
* [Module 3: Information Design](/curricula/designer-modules/information-design/)
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

Text transcripts provide an alternative to visual and audio information. Audio descriptions are essential for people who cannot see the visuals. Captions are essential for people who cannot hear the audio.

Discuss the need for mechanisms to enable or disable alternatives to multimedia content depending on user needs. Explain that these mechanisms need to be always reachable for users, that they need to have clear names, and that they should not disappear when the media starts playing. Explain that defining such mechanisms is a designer's responsibility, whereas providing the alternatives is a responsibility shared with the content author.

#### Learning Outcomes for Topic

Students should be able to

* identify accessibility requirements for the different types of multimedia content, such as text transcripts for audio and visual information, audio descriptions, captions, and sign language
* design user interfaces with mechanisms to enable audio descriptions, captions, and sign language
* design user interfaces with player controls that:
  * have descriptive names
  * can be operable by keyboard
  * are easy to find
  * are always reachable
  * do not disappear when the media starts playing

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

Show examples of moving content, such as animations. Explain that moving content can cause seizures and physical reactions to some people. Designers need to support pausing, stopping, or hiding any moving content, as well as to use flashing that is below the general flash and red flash ratios where possible.

#### Learning Outcomes for Topic

Students should be able to:

* design user interfaces that support pausing, stopping, or hiding any content that blinks, moves, or auto-updates, for example animations, carousels, and decorative gimmicks
* design user interfaces that support flashing below the general flash and red flash thresholds or with content that does not flash more than three times in any one second
* design user interfaces that support disabling motion animation triggered by interaction, such as additional animations when scrolling
* design user interfaces that support stopping or controlling the volume of any audio that plays automatically for more than 3 seconds

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
* [Video Captions (Web Accessibility Perspectives)](https://www.w3.org/WAI/perspective-videos/captions/) &mdash; Is one of the Web accessibility perspectives videos that show accessibility features and how they impact people with disabilities.
* [How People with Disabilities Use the Web](/people-use-web/) &mdash; Provides stories of people with disabilities using the Web; describes types of disabilities and some of the barriers that people encounter using the Web; and introduces types of assistive technologies and adaptive strategies that some people use.
* [WCAG](https://www.w3.org/WAI/standards-guidelines/wcag/) &mdash; Address accessibility of web content on desktops, laptops, tablets, and mobile devices.
