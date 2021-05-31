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
navigation:
  previous: /curricula/designer-modules/images-and-graphics/
  next: /curricula/designer-modules/interaction-and-feedback/
---

## Introduction
{:.no-display}

Courses based on this module should:

* explain strategies that people with disabilities use to access multimedia contents, such as audio and video
* explain accessibility requirements for multimedia content, such as captions, sign language, and audio descriptions

## Learning Outcomes for Module

Students should be able to:

* identify accessibility requirements for different types of audio or video content
* design user interfaces that consider placement of alternatives to multimedia content, such as transcripts for audio and audio described content,
* design user interfaces that support switching transcripts and audio described content on or off
* design user interfaces with mechanisms to pause, stop, and hide any moving, blinking, and auto-updating content, including animations and carousels
* design user interfaces with mechanisms to stop or control the volume of auto-playing audio
* identify related requirements for developers to programmatically associate alternatives and descriptions to their corresponding media content
* identify related requirements for content authors to provide appropriate text alternatives and audio descriptions for different types of media content, including video and audio

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
  * [WCAG Success Criterion 1.2.1	Audio-only and Video-only (Prerecorded)](https://www.w3.org/WAI/WCAG21/quickref/#captions-prerecorded0
  * [WCAG Success Criterion 1.2.2	Captions (Prerecorded)](https://www.w3.org/WAI/WCAG21/quickref/#captions-prerecorded)
  * [WCAG Success Criterion 1.2.3	Audio Description or Media Alternative (Prerecorded)](https://www.w3.org/WAI/WCAG21/quickref/#audio-description-or-media-alternative-prerecorded)
  * [WCAG Success Criterion 1.4.4 Captions (Live)](https://www.w3.org/WAI/WCAG21/quickref/#captions-live)
  * [WCAG Success Criterion 1.2.5 Audio Descriptions (Prerecorded)](https://www.w3.org/WAI/WCAG21/quickref/#audio-description-prerecorded)
  * [WCAG Success Criterion 2.2.2 Pause, Stop, Hide](https://www.w3.org/WAI/WCAG21/Understanding/pause-stop-hide)
  * [WCAG Success Criterion 2.3.1 Three Flashes or Below Threshold](https://www.w3.org/WAI/WCAG21/quickref/#three-flashes-or-below-threshold)
  * [WCAG Success Criterion 3.2.1 On Focus](https://www.w3.org/WAI/WCAG21/quickref/#on-focus)
  * @@@

{% include excol.html type="end" %}

## Topics to Teach

Topics to achieve the learning outcomes:

{% include excol.html type="start" %}

### Topic: Captions and Audio Descriptions

{% include excol.html type="middle" %}

Audio descriptions are essential for people who cannot see the video. Captions and text alternatives are essential for people who cannot hear the audio.

#### Learning Outcomes for Topic

Students should be able to

* identify and distinguish the different types of multimedia content, such as pre-recorded versus live, synchronous versus asynchronous audio and video
* create designs that support equivalent text alternatives for prerecorded audio-only content
* create designs that support text alternatives and audio track for a prerecorded video-only content that presents equivalent information
* create designs that allow to provide captions and audio descriptions for any prerecorded and live audio content in synchronized media
* create designs that allow to provide sign language interpretation for all prerecorded audio content in synchronized media

#### Teaching Ideas for Topic

Optional ideas to teach the learning outcomes:

* Show examples of captions. Explain that these are needed for people who cannot hear the audio, and that they  are useful in other situations. Explain that identifying the situations where captions are needed is a designer's responsibility, whereas providing such captions is a responsibility shared with  the content author. For reference on how to provide captions, see
* Show examples of audio described content. Explain that it is needed for people who cannot see the video. Explain that identifying the situations where audio described content is needed is a designer's responsibility, whereas providing the audio description is a responsibility shared with the content author. For references on how to provide audio descriptions, see

#### Ideas to Assess Knowledge for Topic

Optional ideas to support assessment:

* Short Answer Questions &mdash; Give students some pieces of multimedia content and ask them whether or not they should contain captions and audio descriptions. Assess students' understanding of the requirements for alternatives to multimedia content.

{% include excol.html type="end" %}

{% include excol.html type="start" %}

### Topic: Movement and Animations

{% include excol.html type="middle" %}

Show examples of different types of animations. Explain that they can cause seizures or physical reactions for some people, so additional requirements when designing animations should be considered.

#### Learning Outcomes for Topic

Students should be able to:

* design user interfaces that support pausing, stopping, or hiding any content that blinks, moves, or auto-updates
* design user interfaces that support flashing below the general flash and red flash thresholds or with content that does not flash more than three times in any one second
* design user interfaces that support disabling motion animation triggered by interaction, such as additional animations when scrolling
* design user interfaces that support stopping or controlling the volume of any audio that plays automatically for more than 3 seconds

#### Teaching Ideas for Topic

Optional ideas to teach the learning outcomes:

* Show examples of contents that move or blink, such as animations and carousels. Explain that these can cause problems for some users that cannot keep up with the pace of the auto-updating content or that these animations can cause seizure and physical reactions. For references on how to design suer interfaces that allow to pause, stop, and hide moving, blinking, or auto-updating content, see the following techniques:
  * [G4: Allowing the content to be paused and restarted from where it was paused](https://www.w3.org/WAI/WCAG21/Techniques/general/G4)
  * [G11: Creating content that blinks for less than 5 seconds](https://www.w3.org/WAI/WCAG21/Techniques/general/G11)
  * [G152: Setting animated gif images to stop blinking after n cycles (within 5 seconds)](https://www.w3.org/WAI/WCAG21/Techniques/general/G152)
  * [G186: Using a control in the Web page that stops moving, blinking, or auto-updating content](https://www.w3.org/WAI/WCAG21/Techniques/general/G186)
  * [G187: Using a technology to include blinking content that can be turned off via the user agent](https://www.w3.org/WAI/WCAG21/Techniques/general/G187)
* Show examples of flashing content and explain that they can cause seizures or physical reactions for some people. Emphasize that all components of the content need to be below the general flash and red flash thresholds, as any flashing interferes with the ability to use the whole web page or application. For references on how to design interfaces that support flashing below the general flash and red flash thresholds or that support flashing below 3 seconds, see techniques [G19: Ensuring that no component of the content flashes more than three times in any 1-second period](https://www.w3.org/WAI/WCAG21/Techniques/general/G19.html) and [G15: Using a tool to ensure that content does not violate the general flash threshold or red flash threshold](https://www.w3.org/WAI/WCAG21/Techniques/general/G15.html).
* Show examples of itneractions triggered  by animations, such as additional movements when scrolling. Explain that these animations can cause distraction and vestibular disorders such as dizziness, nausea, and headaches for some people. Discuss different ways to resolve these issues, such as including a preference to disable animations or using technology specific properties to reduce such animations.
* Use a screen reader to navigate an application that plays audio automatically for more than 3 seconds, such as a video player with audio that is longer than 3 seconds. Explain that the playing audio interferes with the ability to hear the screen reader output. Emphasize that there should be a mechanism to pause or control the volume of that audio. Explain that the operating system often provides such mechanism. For references on how to design interfaces that support mechanisms to pause or control the volume of any audio that plays automatically, see the following techniques:
  * [G60: Playing a sound that turns off automatically within three seconds](https://www.w3.org/WAI/WCAG21/Techniques/general/G60.html)
  * [G170: Providing a control near the beginning of the Web page that turns off sounds that play automatically](https://www.w3.org/WAI/WCAG21/Techniques/general/G170.html)
  * [G171: Playing sounds only on user request](https://www.w3.org/WAI/WCAG21/Techniques/general/G171.html).

#### Ideas to Assess Knowledge for Topic

Optional ideas to support assessment:

[To be developed].

{% include excol.html type="end" %}

{% include excol.html type="all" %}

## Ideas to Assess Knowledge for Module

Optional ideas to support assessment:

[To be developed.]

## Teaching Resources

Suggested resources to support your teaching:

[To be developed.]
