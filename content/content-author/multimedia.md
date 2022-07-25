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
  * integrate description in video scripts to minimize the need for separate description at a later phase
  * provide redundancy for different sensory characteristics to help different groups of users understand the content
* ensure multimedia content has alternatives to audio and video based on content type and format, including:
  * transcripts &mdash; a text version of the speech and non-speech audio information needed to understand the content
  * captions &mdash; a synchronized text version of the speech and non-speech audio information needed to understand the content
  * description of visual information &mdash; including video text
  * sign languages &mdash; hand and arm movements, facial expressions, and body positions to convey meaning
* ensure video content avoids flashing entirely or only flashes below the acceptable thresholds
* identify requirements for authoring tools to support inclusion of and interaction with alternatives to audio and video content
* identify related requirements for designers and developers to make accessible:
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
  * [WCAG 2 Successs Criterion 1.4.7 Low or No Background Audio](https://www.w3.org/WAI/WCAG21/quickref/#low-or-no-background-audio)
  * [WCAG Success Criterion 2.2.2 Pause, Stop, Hide](https://www.w3.org/WAI/WCAG21/Understanding/pause-stop-hide)
  * [WCAG Success Criterion 2.3.1 Three Flashes or Below Threshold](https://www.w3.org/WAI/WCAG21/quickref/#three-flashes-or-below-threshold)
* In-depth knowledge of:
  * [Foundation Prerequisites](/curricula/designer-modules/#foundation-prerequisites)
  * Prior [Content Author Modules](/curricula/content-author-modules/)
  * Audio and video content creation
  * [Accessible authoring tools](https://www.w3.org/WAI/standards-guidelines/atag/)

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
  * consider speaker visibility, including for lip reading and sign language interpretation
* ensure video content does not flash more than three times in any one second
* explain why non-substantive audio and video content does not need alternatives

#### Teaching Ideas for Topic

Optional ideas to teach the learning outcomes:

* Emphasize that some government regulations and policies do not cover all user needs. Explain that government regulations and policies differ based on region.
* Show examples of how people with disabilities use audio and video content. Discuss different types of accessibility requirements based on audio      and video content. These include transcripts, captions, description of visual information, and sign languages. Explain that these requirements vary depending on whether the content is live or pre-recorded. For references on the accessibility requirements for different types of audio and video content, see [Checklists for Audio and Video](https://www.w3.org/WAI/media/av/planning/#checklist).
* Demonstrate accessibility best practices for creating audio and video content. These include clear speech, language, and audio, sufficient contrast ratio for videos, and speakers visibility. For details, see [Audio Content and Video Content](https://www.w3.org/WAI/media/av/av-content/).
* Warn students that flashing and blinking content can create seizures and physical reactions for people. Content authors must ensure that there is no flashing content that can create seizures and physical reactions. For information on the accessibility requirements for flashing content, see [Understanding Success Criterion 2.3.1: Three Flashes or Below Threshold](https://www.w3.org/WAI/WCAG21/Understanding/three-flashes-or-below-threshold).
* Present examples of inaccessible audio and video content. Discuss with students which alternatives they would include to make them accessible. Explain that it is best practice to explain why non-substantive audio and video content does not need alternatives. This helps users save time and avoid frustrations. For details, see [Inform users when not needed](https://www.w3.org/WAI/media/av/planning/#none).
* Show examples of existing audio and video projects. Explain how to identify potential accessibility barriers to address. Discuss which accessibility best practices to include in the planning phase to minimize such barriers.

#### Ideas to Assess Knowledge for Topic

Optional ideas to assess knowledge:

* Practical &mdash; Give students a piece of audio and video content. Ask them to determine which alternatives to include and which not to include, as well as to explain why they decided not to include a specific alternative. Assess how students determine the required alternatives to audio and video content as well as how they explain why they decided not to include a specific alternative.
* Research &mdash; Ask students to research government regulations that may apply in their region for audio and video content. Then ask students to explain which user needs for audio and video content are covered and which are not covered in a specific government regulation or policy. Assess how students specify the user needs that specific government regulations and other policy requirements may not cover.
* Short Answer Questions &mdash; Ask students to describe best practices for creating audio and video content. Assess how students describe best practices for creating audio and video content.

{% include excol.html type="end" %}

{% include excol.html type="start" %}

### Topic: Transcripts

{% include excol.html type="middle" %}

Basic transcripts are a text version of the speech and non-speech audio information needed to understand the content. Descriptive transcripts also include text description of the visual information needed to understand the content.

People who are both Deaf and blind require descriptive transcripts to understand the information in video content. Emphasize that creating descriptive transcripts is easier when starting with existing captions and description. For details, see [Transcripts](https://www.w3.org/WAI/media/av/transcripts/).

#### Learning Outcomes for Topic

Students should be able to:

* identify audio and video content that requires transcripts
* identify different approaches for providing transcripts, including:
  * basic &mdash; convey the speech and non-speech information needed to understand the content
  * descriptive &mdash; convey the speech,  non-speech, and visual information needed to understand the content
  * interactive &mdash; highlight text phrases as they are spoken
* create descriptive transcripts when possible to cover all user needs
* collaborate with designers and developers to ensure transcripts are easy to find on the page

#### Teaching Ideas for Topic

Optional ideas to teach the learning outcomes:

* Define basic transcripts as a text version of the speech and non-speech audio information needed to understand the content. Explain that basic transcripts are for people who cannot hear the content well or at all but do not cover the user needs of those who are both Deaf and blind.
* Define descriptive transcripts as those that include text description of the visual information needed to understand the content. People who are both Deaf and blind need them to understand the information contained in video content. Explain that creating descriptive transcripts is easier if they are based on existing captions and description of visual information.
* Describe characteristics of quality transcripts for video and audio content. For example, identifying the speaker and providing all the relevant speech, non-speech, and visual information needed to understand the content.
* Give students a piece of audio and video content and ask them to reflect on what type of information they would include in the transcript.
* Show examples of interactive transcripts. Explain how users can select text in the transcript and go to that point in the video. Emphasize that, for this to work, the media player must support that functionality.
* Discuss approaches for making transcripts easy to find on the page. These include adding the transcript in an expandable section, adding a link to a separate page that contains the transcript, and providing interactive transcripts if the media player supports that functionality. Emphasize that making transcripts easy to find on the page requires collaboration between different team members, including designers, developers, and content authors.

#### Ideas to Assess Knowledge for Topic

Optional ideas to assess knowledge:

* Short Answer Questions &mdash; Ask students what the difference between basic and descriptive transcripts is. Assess how students explain the difference between basic and descriptive transcripts.
* Practical &mdash; Give students a piece of video content with audio and ask them to create its descriptive transcript. Assess how students create descriptive transcripts for audio and video content that include the speech, non-speech, and visual information needed to understand the content.

{% include excol.html type="end" %}

{% include excol.html type="start" %}

### Topic: Captions/Subtitles

{% include excol.html type="middle" %}

Captions, also known as subtitles, are a text version of the speech and non-speech audio information needed to understand the content.

Demonstrate different approaches and tools for providing captions. For details, see [Captions/Subtitles](https://www.w3.org/WAI/media/av/captions/).

#### Learning Outcomes for Topic

Students should be able to:

* define captions as a text version of the speech and non-speech audio information needed to understand the content
* ensure availability of accurate captions
* explain why automatically generated captions are not sufficient to meet accessibility requirements
* enumerate characteristics of quality captions, including relevant non-speech information and timestamps
* recognize different types of file formats for captions, including WebVTT (Web Video Text Tracks Format), SRT (SubRip Subtitle), and TTML (Timed Text Markup Language)

#### Teaching Ideas for Topic

Optional ideas to teach the learning outcomes:

* Define captions as a text version of the speech and non-speech audio information needed to understand the content. Explain that the terms "captions” and "subtitles” are used for the same thing in different regions of the world. See [Captions and Subtitles](https://www.w3.org/WAI/media/av/captions/#captions-and-subtitles)
* Show examples of automatically-generated captions. Emphasize that automatically generated captions alone are not sufficient to meet the accessibility requirements. If starting with automatically-generated captions, content authors must carefully edit them to be accurate with appropriate punctuation, spelling, etc. For details, see [Automatically-generated captions are not sufficient](https://www.w3.org/WAI/media/av/captions/#automatic-captions-are-not-sufficient).
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

people who cannot see the video need description of visual information to understand the content.

Demonstrate approaches for providing description of visual information. These include integrating description in the main audio of the video, providing description in the main audio of an alternative video, and including the description in a synchronized audio or text file when supported by the media player. For details, see [Description of visual information](https://www.w3.org/WAI/media/av/description/).

#### Learning Outcomes for Topic

Students should be able to:

* define description of visual information as information, including text in the video, for people who cannot see the video to understand the content
* identify different approaches for providing description, including:
  * integrated &mdash; authors include descriptions in the script for the main speaker(s) and provide them in the main video
  * two videos &mdash; authors include description in the audio track of an alternative video
  * separate file &mdash; a text or audio file that syncs with the main audio of the video, if supported by the media player
* identify video content that requires description of visual information

#### Teaching Ideas for Topic

Optional ideas to teach the learning outcomes:

* Define description of visual information as information, including text in the video, for people who cannot see the video to understand the content. Explain that different regions have different names for description, including audio descriptions, video descriptions, and described videos.
* Discuss with students how the main speaker(s) can provide the description integrated in their speaking. Explain that integrated description works best for most training videos, though not for most stories. Emphasize that it is best practice to plan for integrated description early on in the creation process to minimize the need for separate description. For details on how to create integrate description, see [Integrated](https://www.w3.org/WAI/media/av/description/#integrated--creating-integrated-description).
* Demonstrate examples of description provided in an alternative version of the video, where the main audio includes the description. Explain that this requires recording and editing abilities. For details on how to create descriptions provided in an alternative version of the video, see [Video with space](https://www.w3.org/WAI/media/av/description/#video-with-space--creating-a-separate-described-video---if-descriptions-fit-in-audio-spaces).
* Show examples of description provided in a text or audio file that syncs with the main audio of the video. Explain that this only works when the media player supports that functionality. For details on how to create descriptions provided in a text or audio file that syncs with the main audio of the video, see [Text](https://www.w3.org/WAI/media/av/description/#text--creating-description-in-a-text-file) and [Audio Only](https://www.w3.org/WAI/media/av/description/#audio-only--creating-description-in-a-separate-audio-file-only).
* Show a video that has important visual information needed to understand the content. Discuss with students what parts of the video they would describe and what type of information they would include in the description.

#### Ideas to Assess Knowledge for Topic

Optional ideas to assess knowledge:

* Short Answer Questions &mdash; Ask students to describe approaches for providing description of visual information. Assess how students describe approaches for providing description of visual information.
* Practical &mdash; Give students a script for a training video. Ask them to integrate the required description of visual information in the script. Assess how students integrate description of visual information in the script of the video.
* Practical &mdash; Give students a video and its corresponding description. Ask them to check if all relevant information is included. Assess how students check separate description for quality and accuracy.

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
* [How People with Disabilities Use the Web](https://www.w3.org/WAI/people-use-web/) &mdash; Provides stories of people with disabilities using the Web; describes types of disabilities and some of the barriers that people encounter using the Web; and introduces types of assistive technologies and adaptive strategies that some people use.
* [Video Captions (Web Accessibility Perspectives)](https://www.w3.org/WAI/perspective-videos/captions/) &mdash; Is one of the Web accessibility perspectives videos that show accessibility features and how they impact people with disabilities.
* [WCAG](https://www.w3.org/WAI/standards-guidelines/wcag/) &mdash; Address accessibility of web content on desktops, laptops, tablets, and mobile devices.
