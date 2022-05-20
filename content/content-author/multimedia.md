---
title: "[Draft] Module 6: Multimedia"
nav_title: "Multimedia"
permalink: /curricula/content-author-modules/multimedia/
ref: /curricula/content-author-modules/multimedia/
lang: en
github:
  repository: w3c/wai-curricula
  path: content/content-author-modules/multimedia.md
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
  previous: /curricula/content-author-modules/data-tables/
---

## Introduction
{:.no-display}

Courses based on this module should:

* demonstrate how people with disabilities rely on alternatives to multimedia content, including transcripts, description of visual information (also known as audio description, video description, or described video), captions (also known as subtitles), and sign language(s), to understand information contained in audio and video content
* explain accessibility requirements for planning and including alternatives to audio and video content

## Learning Outcomes for Module
  
Students should be able to:

* explain how people with disabilities rely on alternatives to multimedia content to understand information contained in audio and video
* explain the following best practices for accessible audio and video content:
  * use clear and easy to understand speech
  * ensure sufficient contrast ratios for video text
  * minimize background audio and overall distractions where possible
  * integrate descriptions in video scripts to minimize the need for additional descriptions at a later phase
  * match the video and audio information when possible to help different groups of users understand the content
* ensure multimedia content has alternatives to audio and video based on content type and format, including:
  * transcripts (a text version of the speech and non-speech audio information needed to understand the content)
  * captions (a synchronized text version of the speech and non-speech audio information needed to understand the content)
  * description of visual information (including video text)
  * sign languages (hand and arm movements, facial expressions, and body positions to convey meaning)
* ensure video content that avoids flashing entirely or only flashes below the acceptable thresholds
* explain requirements for authoring tools to support inclusion of and interaction with alternatives to audio and video content
* identify related requirements for designers and developers to support visual and non-visual perception and operation of:
  * alternatives to multimedia content 
  * media player controls

{% include excol.html type="all" %}

## Competencies

Skills required for this module:

{% include excol.html type="start" %}

### Students

{% include excol.html type="middle" %}

* [Foundation Prerequisites](/curricula/designer-modules/#foundation-prerequisites)
* Prior [Content Author Modules](/curricula/content-author-modules/)
* Basic knowledge of:
  * Writing
  * Copy-editing
  * Proofreading

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
  * [WCAG Success Criterion 1.2.6 Sign Language (prerecorded](https://www.w3.org/WAI/WCAG21/quickref/#sign-language-prerecorded)
  * [WCAG Success Criterion 1.4.2 Audio Control](https://www.w3.org/WAI/WCAG21/quickref/#audio-control)
  * [WCAG Success Criterion 2.2.2 Pause, Stop, Hide](https://www.w3.org/WAI/WCAG21/Understanding/pause-stop-hide)
  * [WCAG Success Criterion 2.3.1 Three Flashes or Below Threshold](https://www.w3.org/WAI/WCAG21/quickref/#three-flashes-or-below-threshold)
* In-depth knowledge of:
  * [Foundation Prerequisites](/curricula/designer-modules/#foundation-prerequisites)
  * Prior [Content Author Modules](/curricula/content-author-modules/)
  * Accessible Content Creation

{% include excol.html type="end" %}

## Topics to Teach

Topics to achieve the learning outcomes:

{% include excol.html type="start" %}

### Topic: Planning Audio and Video

{% include excol.html type="middle" %}

Introduce different user needs for audio and video content. For example, for people who don't see the video and for people who don't hear the audio. Explain that different types of audio and video content have different accessibility requirements based on governmental regulations and other policy requirements.

Discuss best practices for audio an  video content, including clear audio and speech, sufficient contrast ratios, and speaker visibility.

#### Learning Outcomes for Topic

Students should be able to:

* determine the required alternatives to multimedia content, including transcripts, description, captions, and sign language, based on:
  * multimedia formats (such as audio and video)
  * multimedia types (such as recorded and prerecorded)
  * user needs (including with and without disabilities)
  * governmental regulations and other policy requirements
* explain the following best practices for audio and video content:
  * use clear audio, language, and speech to help users understand the content
  * ensure sufficient contrast ratio for video text to enhance text readability
  * provide audio with as low background as possible to help distinguish foreground from background sounds
  * consider speaker visibility (including for lip reading and sign language interpretation)
* ensure video content does not flash more than three times in any one second
* provide rationale for not including one or more alternatives to multimedia content

#### Teaching Ideas for Topic

Optional ideas to teach the learning outcomes:

* Discuss different types of accessibility requirements based on audio and video content. These include transcripts, captions, description of visual information, and sign languages. Explain that these requirements vary depending on whether the content is live or pre-recorded. For references on the accessibility requirements of different types of audio and video content, see [Checklists for Audio and Video](/media/av/planning/#checklist).
* Demonstrate best practices when creating audio and video content for accessibility. These include clear speech, language, and audio, sufficient contrast ratio for videos, and ensuring visibility of the speakers.
* Warn students that any flashing and blinking content can create seizures and physical reactions for people. Authors must ensure that there is no flashing content that can create seizures or physical reactions. Explain the requirements for this content to flash only up to three times in one second or to be below the general flash and red flash thresholds. For information on the accessibility requirements for flashing content, see [Understanding Success Criterion 2.3.1: Three Flashes or Below Threshold](https://www.w3.org/WAI/WCAG21/Understanding/three-flashes-or-below-threshold).

#### Ideas to Assess Knowledge for Topic

Optional ideas to assess knowledge:

* Short Answer Questions &mdash; Ask students to describe alternatives to audio and video content. Assess how students describe the accessibility requirements for audio and video content.
* Research &mdash; Ask students to research governmental regulations that may apply in their region for audio and video content. Then ask students to specify the accessibility requirements for different types of audio and video content. Assess how students determine the accessibility requirements for different types of audio and video content based on governmental regulations and other policy requirements.

{% include excol.html type="end" %}

{% include excol.html type="start" %}

### Topic: Transcripts

{% include excol.html type="middle" %}

Basic transcripts are a text version of the speech and non-speech audio information needed to understand the content. Descriptive transcripts also include text description of the visual information needed to understand the content.

Demonstrate approaches for providing basic and descriptive transcripts. For details, see [Transcripts](/media/av/transcripts/).

#### Learning Outcomes for Topic

Students should be able to:

* ensure inclusion of transcripts for audio and video content when required
* create basic transcripts that:
  * convey the speech and non-speech information needed to understand the content
  * identify the speaker
* provide descriptive transcripts when required based on existing captions and description
* collaborate with designers to ensure transcripts are easy to find on the page

#### Teaching Ideas for Topic

Optional ideas to teach the learning outcomes:

* Define basic transcripts as a text version of the speech and non-speech audio information needed to understand the content. Explain that transcripts are for people who cannot see or cannot hear the content.
* Describe characteristics of quality transcripts for video and audio content. For example, identifying the speaker and providing all the relevant information needed to understand the content.
* Define descriptive transcripts as those that include text descriptions of the visual information that is needed to understand the content. Explain that these descriptions are often based on existing captions and description of visual information.
* Discuss approaches for making transcripts easy to find on the page. This may include adding the transcript in an expandable section or adding a link to a separate page that contains the transcript. Emphasize that making transcripts easy to find on the page requires collaboration between different team members, including designers, developers, and content authors.

#### Ideas to Assess Knowledge for Topic

Optional ideas to assess knowledge:

* Short Answer Questions &mdash; Ask students what is the difference between basic and descriptive transcripts. Assess how students explain the difference between basic and descriptive transcripts.
* Practical &mdash; Give students a video content containing audio and ask them to create its transcript. Assess how students create transcripts for audio and video content  that include the relevant information needed to understand the content.
* Practical &mdash; Give students a video with a basic transcript and ask them to create a descriptive transcript. Assess how students create descriptive transcripts.

{% include excol.html type="end" %}

{% include excol.html type="start" %}

### Topic: Captions/Subtitles

{% include excol.html type="middle" %}

Captions (also known as subtitles) are a text version of the speech and non-speech audio information needed to understand the content.

Demonstrate different approaches and tools for provide captions. For details, see [Captions/Subtitles](/media/av/captions/).

#### Learning Outcomes for Topic

Students should be able to:

* ensure availability of accurate captions for audio content by:
  * including a caption file
  * amending automatically generated captions for quality and accuracy
* enumerate characteristics of quality captions, including timestamps and non-speech information
* identify different types of file formats for captions, including WebVTT (Web Video Text Tracks Format), SRT (SubRip Subtitle), and TTML (Timed Text Markup Language)

#### Teaching Ideas for Topic

Optional ideas to teach the learning outcomes:

* Define captions as a text version of the speech and non-speech audio information needed to understand the content. Explain that different regions have different names for captions, including subtitles.
* Show examples of automatically-generated captions. Emphasize that they are not sufficient to meet the accessibility requirements. If relying on automatically-generated captions, content authors must ensure these captions are accurate and convey all the relevant information.
* Describe characteristics of quality captions, including timestamps to identify when a person speaks. Explain that timestamps are often generated using specific software.
* Introduce different types of file formats for captions, including WebVTT (Web Video Text Tracks Format), SRT (SubRip Subtitle), and TTML (Timed Text Markup Language). Explain that there are different tools to produce captions. Emphasize that it is easier to start with an existing transcript and then use the tools to generate the timestamps. Remind students that sometimes content authors require help from specialized roles to produce accurate and quality captions.
* Show examples of how different media players and user agents display captions. Explain that some enable users to determine how and where captions appear. Emphasize that specifying the position and appearance of captions requires collaboration between different team members, including designers and developers.

#### Ideas to Assess Knowledge for Topic

Optional ideas to assess knowledge:

* Short Answer Questions &mdash; Ask students what type of information captions should contain. Assess how students explain the type of information that captions should contain.
* Practical &mdash; Give students a video with automatically-generated captions and ask them to amend these captions for accuracy and quality. Assess how students edit automatically-generated captions for accuracy and quality.

{% include excol.html type="end" %}

{% include excol.html type="start" %}

### Topic: Description of Visual Information

{% include excol.html type="middle" %}

Descriptions explain visual information needed to understand the content for people who don't see the video.

Show examples of videos containing such descriptions and demonstrate different approaches for providing description of visual information. For details. see [Description of visual information](/media/av/description/).

#### Learning Outcomes for Topic

Students should be able to:

* define description of visual information as information (including text in the video) for people who don't see the video to understand the content
* identify different approaches for providing descriptions of visual information, including:
  * integrated (speakers describe the relevant information)
  * narrative
    * included in the main audio track of an alternative version of the video
    * provided in a separate audio track or text file (if supported by the media player)
* ensure description of visual information is available when required

#### Teaching Ideas for Topic

Optional ideas to teach the learning outcomes:

* Define description of visual information as information (including text in the video) for people who cannot see the video to understand the content. Explain that different regions have different names for description, including audio descriptions, video descriptions, and described videos.
* Discuss different approaches for integrating descriptions as part of the audio content of the video. This includes having the speakers verbalize the relevant information needed to understand the video without seeing it. Emphasize that it is best practice to plan for integrated descriptions early on in the creation process to minimizes the need for additional descriptions.
* Define narrative descriptions as those included in the audio of the video. These can be provided in the main audio file of an alternative version of the video or in a separate audio file (if supported by the media player).

#### Ideas to Assess Knowledge for Topic

Optional ideas to assess knowledge:

* Short Answer Questions &mdash; Ask students about different approaches for providing description of visual information. Assess how students understand approaches to providing description of visual information.
* Practical &mdash; Give students a video and ask them to integrate the required description of visual information in the script. Assess how students integrate description of visual information in the script of the video.

{% include excol.html type="end" %}

{% include excol.html type="all" %}

## Ideas to Assess Knowledge for Module

Optional ideas to assess knowledge:

* Short Answer Questions &mdash; Ask students about the different  information that alternatives to multimedia content should contain, and what user needs each of the alternatives meet. Assess how students understand the different information for alternatives to multimedia content and what user needs they meet.
* Portfolio &mdash; Have students supervise the inclusion of alternatives to audio and video content on the website they are creating. Assess how students supervise the inclusion of alternatives to multimedia content based on content type, format, and user needs.

## Teaching Resources

Suggested resources to support your teaching:

* [Making Audio and Video Media Accessible](https://www.w3.org/WAI/media/av/) &mdash; Covers captions/subtitles, audio description of visual information, descriptive transcripts, and sign languages. Includes guidance for creating new videos, and on media player accessibility. Introduces user experiences and benefits to organizations.
* [Writing for Web Accessibility](https://www.w3.org/WAI/tips/writing/) -- Introduces some basic considerations to help you get started writing web content that is more accessible to people with disabilities.
* [How People with Disabilities Use the Web](/people-use-web/) &mdash; Provides stories of people with disabilities using the Web; describes types of disabilities and some of the barriers that people encounter using the Web; and introduces types of assistive technologies and adaptive strategies that some people use.
* [Video Captions (Web Accessibility Perspectives)](https://www.w3.org/WAI/perspective-videos/captions/) &mdash; Is one of the Web accessibility perspectives videos that show accessibility features and how they impact people with disabilities.
* [WCAG](https://www.w3.org/WAI/standards-guidelines/wcag/) &mdash; Address accessibility of web content on desktops, laptops, tablets, and mobile devices.
