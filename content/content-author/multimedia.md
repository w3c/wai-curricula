---
title: "[Draft] 6: Multimedia in Content Author Modules | Curricula"
title_html: "Module 6: Multimedia"
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

* demonstrate how people with disabilities rely on alternatives to multimedia content to understand information contained in audio and video content
* cover transcripts, description of visual information (also called audio description, video description, or described video), captions (also known as subtitles), and sign languages

## Learning Outcomes for Module
  
Students should be able to:

* explain how people with disabilities rely on alternatives to information contained in audio and video content
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
* ensure video content avoids flashing entirely or only flashes below the acceptable thresholds
* identify requirements for authoring tools to support inclusion of and interaction with alternatives to audio and video content
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
  * [WCAG Success Criterion 1.2.6 Sign Language (Prerecorded)](https://www.w3.org/WAI/WCAG21/quickref/#sign-language-prerecorded)
  * [WCAG Success Criterion 1.4.2 Audio Control](https://www.w3.org/WAI/WCAG21/quickref/#audio-control)
  * [WCAG Success Criterion 2.2.2 Pause, Stop, Hide](https://www.w3.org/WAI/WCAG21/Understanding/pause-stop-hide)
  * [WCAG Success Criterion 2.3.1 Three Flashes or Below Threshold](https://www.w3.org/WAI/WCAG21/quickref/#three-flashes-or-below-threshold)
* In-depth knowledge of:
  * [Foundation Prerequisites](/curricula/designer-modules/#foundation-prerequisites)
  * Prior [Content Author Modules](/curricula/content-author-modules/)
  * Audio and video content creation
  * Accessible authoring tools

{% include excol.html type="end" %}

## Topics to Teach

Topics to achieve the learning outcomes:

{% include excol.html type="start" %}

### Topic: Planning Audio and Video

{% include excol.html type="middle" %}

Introduce different user needs for audio and video content. For example, for people who don't see the video and for people who don't hear the audio. For details, see [Understand the User Needs and Experiences of People with Disabilities ](https://www.w3.org/WAI/media/av/users-orgs/#understand-the-user-needs-and-experiences-of-people-with-disabilities).

Discuss best practices for audio and  video content, including clear audio and speech, sufficient contrast ratios, and speaker visibility. For details, see [Audio Content and Video Content](https://www.w3.org/WAI/media/av/av-content/).

#### Learning Outcomes for Topic

Students should be able to:

* determine the required alternatives to multimedia content, including transcripts, description, captions, and sign language, based on:
  * audio and/or video
  * live or prerecorded
  * user needs
  * government regulations and other policy requirements
* explain the following accessibility best practices for audio and video content:
  * use clear audio, language, and speech to help users understand the content
  * ensure sufficient contrast ratio for video text to enhance text readability
  * provide audio with as low background as possible to help distinguish foreground from background sounds
  * consider speaker visibility (including for lip reading and sign language interpretation)
* ensure video content does not flash more than three times in any one second
* provide rationale for not including one or more alternatives to multimedia content

#### Teaching Ideas for Topic

Optional ideas to teach the learning outcomes:

* Explain that different government regulations and other policy requirements cover different user needs for audio and video content. Emphasize that some government regulations and policies may not cover all user needs depending on audience and context.
* Show examples of how people with disabilities use audio and video content. Discuss different types of accessibility requirements based on audio      and video content. These include transcripts, captions, description of visual information, and sign languages. Explain that these requirements vary depending on whether the content is live or pre-recorded. For references on the accessibility requirements for different types of audio and video content, see [Checklists for Audio and Video](/media/av/planning/#checklist).
* Demonstrate accessibility best practices for creating audio and video content. These include clear speech, language, and audio, sufficient contrast ratio for videos, and speakers visibility. For details, see [Audio Content and Video Content](https://www.w3.org/WAI/media/av/av-content/).
* Warn students that flashing and blinking content can create seizures and physical reactions for people. Content authors must ensure that there is no flashing content that can create seizures and physical reactions. For information on the accessibility requirements for flashing content, see [Understanding Success Criterion 2.3.1: Three Flashes or Below Threshold](https://www.w3.org/WAI/WCAG21/Understanding/three-flashes-or-below-threshold).
* Present examples of inaccessible audio and video content. Discuss with students which alternatives they would include to make them accessible. Explain that it is best practice to provide rationale for when not including a specific alternative. This helps users save time and avoid frustrations.
* Show examples of existing audio and video projects. Explain how to identify potential accessibility barriers to address. Discuss which accessibility best practices to include in the planning phase to minimize such barriers.

#### Ideas to Assess Knowledge for Topic

Optional ideas to assess knowledge:

* Practical &mdash; Give students a piece of audio and video content. Ask them to determine which alternatives to include and which not to include, as well as to provide rationale when not including a specific alternative. Assess how students determine the required alternatives to audio and video content and how they provide rationale when not including a specific alternative.
* Research &mdash; Ask students to research government regulations that may apply in their region for audio and video content. Then ask students to explain which user needs for audio and video content are covered and which are not covered in a specific government regulation or policy. Assess how students specify the user needs that specific government regulations and other policy requirements may not cover.
* Short Answer Questions &mdash; Ask students to describe best practices for creating audio and video content. Assess how students describe best practices for creating audio and video content.

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
* collaborate with designers and developers to ensure transcripts are easy to find on the page

#### Teaching Ideas for Topic

Optional ideas to teach the learning outcomes:

* Define basic transcripts as a text version of the speech and non-speech audio information needed to understand the content. Explain that transcripts are for people who cannot hear the content well or at all.
* Describe characteristics of quality transcripts for video and audio content. For example, identifying the speaker and providing all the relevant information needed to understand the content.
* Define descriptive transcripts as those that include text descriptions of the visual information that is needed to understand the content. Explain that these descriptions are often based on existing captions and description of visual information.
* Give students a piece of audio and video content and ask them to reflect on what type of information they would include in basic and descriptive transcripts.
* Discuss approaches for making transcripts easy to find on the page. This may include adding the transcript in an expandable section and adding a link to a separate page that contains the transcript. Emphasize that making transcripts easy to find on the page requires collaboration between different team members, including designers, developers, and content authors.

#### Ideas to Assess Knowledge for Topic

Optional ideas to assess knowledge:

* Short Answer Questions &mdash; Ask students what the difference between basic and descriptive transcripts is. Assess how students explain the difference between basic and descriptive transcripts.
* Practical &mdash; Give students a piece of video content with audio and ask them to create its transcript. Assess how students create transcripts for audio and video content  that include the relevant information needed to understand the content.
* Practical &mdash; Give students a piece of video and audio content with a basic transcript and ask them to create a descriptive transcript. Assess how students create descriptive transcripts.

{% include excol.html type="end" %}

{% include excol.html type="start" %}

### Topic: Captions/Subtitles

{% include excol.html type="middle" %}

Captions (also known as subtitles) are a text version of the speech and non-speech audio information needed to understand the content.

Demonstrate different approaches and tools for providing captions. For details, see [Captions/Subtitles](/media/av/captions/).

#### Learning Outcomes for Topic

Students should be able to:

* define captions as a text version of the speech and non-speech audio information needed to understand the content
* ensure availability of accurate captions by using one of the following:
  * a caption file
  * automatically generated captions that have been checked for quality and accuracy
* enumerate characteristics of quality captions, including relevant non-speech information and timestamps
* recognize different types of file formats for captions, including WebVTT (Web Video Text Tracks Format), SRT (SubRip Subtitle), and TTML (Timed Text Markup Language)

#### Teaching Ideas for Topic

Optional ideas to teach the learning outcomes:

* Define captions as a text version of the speech and non-speech audio information needed to understand the content. Explain that the terms "captions” and "subtitles” are used for the same thing in different regions of the world. See [Captions and Subtitles](https://www.w3.org/WAI/media/av/captions/#captions-and-subtitles)
* Show examples of automatically-generated captions. Emphasize that automatically generated captions alone are not sufficient to meet the accessibility requirements. If relying on automatically-generated captions, content authors must ensure these captions are accurate and convey all the relevant information.
* Reflect with students on characteristics of quality captions, including relevant non-speech information as well as timestamps to identify when a person speaks.
* Show a piece of audio and video content. Discuss with students which information they would include in the captions.
* Introduce different types of file formats for captions, including WebVTT (Web Video Text Tracks Format), SRT (SubRip Subtitle), and TTML (Timed Text Markup Language). Explain that it is more efficient to use specific software for creating captions, as the software can add the relevant timestamps. Sometimes content authors require help from specialized roles to produce accurate and quality captions.
* Show examples of how different media players and browsers display captions. Explain that some players let users determine how and where captions appear. Emphasize that specifying the position and appearance of captions requires collaboration between different team members, including designers, developers, and content authors.

#### Ideas to Assess Knowledge for Topic

Optional ideas to assess knowledge:

* Short Answer Questions &mdash; Ask students what type of information captions should contain. Assess how students explain the type of information that captions should contain.
* Practical &mdash; Give students a piece of audio and video content with automatically-generated captions. Ask them to check these captions for accuracy and quality and to amend them when appropriate. Assess how students check automatically-generated captions for accuracy and quality.
* Practical &mdash; Ask students to collaborate with other team members to specify position and appearance for captions. Assess how students collaborate with other team members to specify position and appearance for captions.

{% include excol.html type="end" %}

{% include excol.html type="start" %}

### Topic: Description of Visual Information

{% include excol.html type="middle" %}

Description explains visual information needed to understand the content for people who cannot see the video.

Show examples of videos containing such description and demonstrate different approaches for providing description of visual information. For details, see [Description of visual information](/media/av/description/).

#### Learning Outcomes for Topic

Students should be able to:

* define description of visual information as information (including text in the video) for people who cannot see the video to understand the content
* identify different approaches for providing descriptions of visual information, including:
  * integrated (speakers describe the relevant information)
  * narrative
    * included in the main audio track of an alternative version of the video
    * provided in a separate audio track or text file (if supported by the media player)
* ensure description of visual information is available when required

#### Teaching Ideas for Topic

Optional ideas to teach the learning outcomes:

* Define description of visual information as information (including text in the video) for people who cannot see the video to understand the content. Explain that different regions have different names for description, including audio descriptions, video descriptions, and described videos.
* Discuss different approaches for integrating descriptions as part of the audio content of the video. This includes having the speakers verbalize the relevant information needed to understand the video without seeing it. Emphasize that it is best practice to plan for integrated descriptions early on in the creation process to minimize the need for additional descriptions.
* Define narrative descriptions as those included in the audio of the video. These can be provided in the main audio file of an alternative version of the video or in a separate audio file (if supported by the media player).
* Show a video that has important visual information needed to understand the content. Discuss with students what parts of the video they would describe and what type of information they would include in the description.

#### Ideas to Assess Knowledge for Topic

Optional ideas to assess knowledge:

* Short Answer Questions &mdash; Ask students to describe approaches for providing description of visual information. Assess how students describe approaches for providing description of visual information.
* Practical &mdash; Give students a video script and ask them to integrate the required description of visual information in the script. Assess how students integrate description of visual information on the script of the video.
* Practical &mdash; Give students a video description with a narrative description and ask them to check if all relevant information is included. Assess how students check narrative descriptions for quality and accuracy.

{% include excol.html type="end" %}

{% include excol.html type="all" %}

## Ideas to Assess Knowledge for Module

Optional ideas to assess knowledge:

* Short Answer Questions &mdash; Ask students what type of information each alternative to multimedia content should convey, as well as what user needs each alternative meets. Assess how students understand the type of information that each alternative to multimedia content should convey and what user needs each alternative meets.
* Portfolio &mdash; Have students supervise the inclusion of alternatives to audio and video content on the website they are creating. Assess how students supervise the inclusion of alternatives to multimedia content based on content type, format, and user needs.

## Teaching Resources

Suggested resources to support your teaching:

* [Making Audio and Video Media Accessible](https://www.w3.org/WAI/media/av/) &mdash; Covers captions/subtitles, audio description of visual information, descriptive transcripts, and sign languages. Includes guidance for creating new videos, and on media player accessibility. Introduces user experiences and benefits to organizations.
* [Writing for Web Accessibility](https://www.w3.org/WAI/tips/writing/) -- Introduces some basic considerations to help you get started writing web content that is more accessible to people with disabilities.
* [How People with Disabilities Use the Web](/people-use-web/) &mdash; Provides stories of people with disabilities using the Web; describes types of disabilities and some of the barriers that people encounter using the Web; and introduces types of assistive technologies and adaptive strategies that some people use.
* [Video Captions (Web Accessibility Perspectives)](https://www.w3.org/WAI/perspective-videos/captions/) &mdash; Is one of the Web accessibility perspectives videos that show accessibility features and how they impact people with disabilities.
* [WCAG](https://www.w3.org/WAI/standards-guidelines/wcag/) &mdash; Address accessibility of web content on desktops, laptops, tablets, and mobile devices.
