<html>
  <head>
    <meta http-equiv="content-type" content="text/html; charset=windows-1252">
    <link rel="alternate stylesheet" type="text/css" href="resource://gre-resources/plaintext.css"
      title="Ajustar líneas largas">
  </head>
  <body>
    <pre>---
title: "Introduction to Web Accessibility"
permalink: /curricula/
ref: /curricula/
lang: en
github:
  repository: w3c/wai-curricula
  path: intro.md
footer: &lt;p&gt; work in progress &lt;/p&gt;
---

{::nomarkdown}
{% include box.html type="start" title="Module Description" class="" %}
{:/}

&lt;p&gt;This WAI Curriculum module provides a general introduction to web accessibility. It is designed for any learner with basic understanding of computers and the Web. The suggested duration for courses following this module is 12-14 hours, depending on interaction with learners, activities and exercises, and knowledge assessments. This module addresses the following learning objectives:&lt;/p&gt;
&lt;ul&gt;
  &lt;li&gt;Understanding the scope and relevance of web accessibility&lt;/li&gt;
  &lt;li&gt;Appreciation for how people with disabilities use the Web&lt;/li&gt;
  &lt;li&gt;Understanding of accessibility features and design barriers&lt;/li&gt;
  &lt;li&gt;Awareness about business case benefits of web accessibility&lt;/li&gt;
  &lt;li&gt;Knowledge about web accessibility standards and guidelines&lt;/li&gt;
  &lt;li&gt;Ability to carry out preliminary accessibility evaluation&lt;/li&gt;
  &lt;li&gt;Understanding of how to plan for and manage implementation&lt;/li&gt;
&lt;/ul&gt;
&lt;p&gt;&lt;strong&gt;Note:&lt;/strong&gt; This module addresses many different audiences, including people with different technical skills and knowledge about the topic. It is recommended to tailor examples, activities, and assessments to your particular audience.&lt;/p&gt;

{::nomarkdown}
{% include box.html type="end" %}
{:/}

{::nomarkdown}
{% include toc.html type="start" title="Teaching Units in this Module" %}
{:/}

- This will be replaced by an automatically generated TOC when using Markdown formatting.
{:toc}

{::nomarkdown}
{% include toc.html type="end" %}
{:/}

## Overview and Terminology ##

&lt;dl&gt;
  &lt;dt&gt;&lt;strong&gt;Description&lt;/strong&gt;&lt;/dt&gt;
  &lt;dd&gt;Overview on the topic web accessibility, its scope, and key terminology used in this context.&lt;/dd&gt;
  &lt;dt&gt;&lt;strong&gt;Learning Outcomes&lt;/strong&gt;&lt;/dt&gt;
  &lt;dd&gt;&lt;ul&gt;
    &lt;li&gt;Understanding the definition of web accessibility for people with disabilities&lt;/li&gt;
    &lt;li&gt;Understanding the scope of "the Web", including on desktop and mobile devices&lt;/li&gt;
    &lt;li&gt;Awareness of some types of design barriers that exclude people with disabilities&lt;/li&gt;
    &lt;li&gt;Knowledge of inter-relationship between different components of web accessibility&lt;/li&gt;
    &lt;li&gt;Understanding key terms and the role of accessibility standards and guidelines&lt;/li&gt;
  &lt;/ul&gt;&lt;/dd&gt;
  &lt;dt&gt;&lt;strong&gt;Prerequisites for Learners&lt;/strong&gt;&lt;/dt&gt;
  &lt;dd&gt;[Basic] Basic understanding of computers and the Web.&lt;/dd&gt;
  &lt;dt&gt;&lt;strong&gt;Prerequisites for instructors&lt;/strong&gt;&lt;/dt&gt;
  &lt;dd&gt;[Basic] Basic understanding of web accessibility.&lt;/dd&gt;
  &lt;dt&gt;&lt;strong&gt;Approximate Duration&lt;/strong&gt;&lt;/dt&gt;
  &lt;dd&gt;1-2 hours depending on activities.&lt;/dd&gt;
  &lt;dt&gt;&lt;strong&gt;Teaching Outline&lt;/strong&gt;&lt;/dt&gt;
  &lt;dd&gt;&lt;ul&gt;
    &lt;li&gt;&lt;strong&gt;Meaning of web accessibility&lt;/strong&gt; &amp;mdash; Define web accessibility as ability for people with disabilities to use web content, tools, and technology equally. Explain the relevance of web accessibility, given the widespread use of web content and applications across different types of devices (desktop, mobile, television, etc.) for social participation (for education, employment, commerce, healthcare, entertainment, etc.). Emphasize the unique opportunity for inclusion.&lt;/li&gt;
    &lt;li&gt;&lt;strong&gt;Examples of web accessibility&lt;/strong&gt; &amp;mdash; Provide some basic examples of accessibility barriers and how they impact people with diverse types of disabilities. Emphasize that accessibility barriers impact many people, including people with auditory, cognitive and learning, physical, speech, and visual disabilities. Explain how accessibility barriers are created through inadequate design and implementation, and provide examples of accessibility features and repairs.&lt;/li&gt;
    &lt;li&gt;&lt;strong&gt;Components of web accessibility&lt;/strong&gt; &amp;mdash; Explain the inter-relationship between accessibility features in web technologies such as HTML, in web content, web authoring tools, web browsers, and assistive tools. Provide examples of accessibility features and accessibility barriers in these components, and explain the role of accessibility standards and guidelines for these components. Emphasize that accessibility encompasses many types of roles and responsibilities.&lt;/li&gt;
  &lt;/ul&gt;&lt;/dd&gt;
  &lt;dt&gt;&lt;strong&gt;Suggested Teaching Methods&lt;/strong&gt;&lt;/dt&gt;
  &lt;dd&gt;&lt;strong&gt;Presentational&lt;/strong&gt; &amp;mdash; Provide an engaging presentation that will set the tone for further discussion. Provide an outlook on how later teaching untils will provide more in-depth exploration of certain areas.&lt;/dd&gt;
  &lt;dt&gt;&lt;strong&gt;Suggested Teaching Materials&lt;/strong&gt;&lt;/dt&gt;
  &lt;dd&gt;&lt;ul&gt;
    &lt;li&gt;&lt;a href="https://www.w3.org/WAI/fundamentals/accessibility-intro/"&gt;Introduction to Web Accessibility&lt;/a&gt; &amp;mdash; provides and overview on web accessibility, including a 4 minute video with examples of accessibility features and barriers.&lt;/li&gt;
    &lt;li&gt;&lt;a href="https://www.w3.org/WAI/fundamentals/components/"&gt;Essential Components of Web Accessibility&lt;/a&gt; &amp;mdash; explains key terms, and the inter-relation between different components of web accessibility (eg. web technologies, authoring tools, browsers, etc.).&lt;/li&gt;
    &lt;li&gt;&lt;a href="https://www.w3.org/WAI/people-use-web/"&gt;How People with Disabilities Use the Web&lt;/a&gt; &amp;mdash; provides stories of people with diverse disabilities using the Web; enumerates different types of disabilities and some of the barriers that people encounter using the Web; and introduces different types of assistive tools and adaptive strategies that some people use.&lt;/li&gt;
    &lt;li&gt;&lt;a href="https://www.w3.org/WAI/perspective-videos/"&gt;Web Accessibility Perspectives (videos)&lt;/a&gt; &amp;mdash; series of 10 videos, each of around 1 minute duration, that highlight different types of accessibility features and how they impact people with disabilites and other users. For example, one video introduces colors with good contrast and how it benefits many people.&lt;/li&gt;
    &lt;li&gt;&lt;a href="https://www.w3.org/WAI/fundamentals/accessibility-usability-inclusion/"&gt;Accessibility, Usability, and Inclusion&lt;/a&gt; &amp;mdash; Explains the distinctions and overlaps between the terms accessibility, usability, and inclusion, and how these are best addressed together using a user-centered design process.&lt;/li&gt;
    &lt;li&gt;&lt;a href="https://www.un.org/development/desa/disabilities/convention-on-the-rights-of-persons-with-disabilities.html"&gt;Convention on the Rights of Persons with Disabilities (CRPD)&lt;/a&gt; &amp;mdash; Lists the countries that signed and ratified the convention and optional protocol, and provides news and information on implementation of the convention.&lt;/li&gt;
  &lt;/ul&gt;&lt;/dd&gt;
  &lt;dt&gt;&lt;strong&gt;Ideas for Assessment&lt;/strong&gt;&lt;/dt&gt;
  &lt;dd&gt;&lt;ul&gt;
    &lt;li&gt;&lt;strong&gt;Knowledge Questions&lt;/strong&gt; &amp;mdash; Learners should be able to recite the definition of web accessibility, explain different terms, and enumerate different components of web accessibility and how they inter-relate.&lt;/li&gt;
  &lt;/ul&gt;&lt;/dd&gt;
  &lt;dt&gt;&lt;strong&gt;Notes&lt;/strong&gt;&lt;/dt&gt;
  &lt;dd&gt;&lt;ul&gt;
    &lt;li&gt;&lt;strong&gt;Initial awareness&lt;/strong&gt; &amp;mdash; The initial level of awareness for accessibility and disability will often vary for each learner. Asking learners to share examples from their own experiences can encourage thought-exchange.&lt;/li&gt;
    &lt;li&gt;&lt;strong&gt;Laying foundations&lt;/strong&gt; &amp;mdash; Much of the content in this teachning unit is intended to lay foundations for further exploration and discussion in later teaching units. The corresponding courses need to be well-aligned.&lt;/li&gt;
  &lt;/ul&gt;&lt;/dd&gt;
&lt;/dl&gt;

## People and Access Technology ##

&lt;dl&gt;
  &lt;dt&gt;&lt;strong&gt;Description&lt;/strong&gt;&lt;/dt&gt;
  &lt;dd&gt;Introduction to how people with disabilities use the Web, different types of assistive technologies and adaptive strategies that some people use, and some of the barriers that people encounter on the Web.&lt;/dd&gt;
  &lt;dt&gt;&lt;strong&gt;Learning Outcomes&lt;/strong&gt;&lt;/dt&gt;
  &lt;dd&gt;&lt;ul&gt;
    &lt;li&gt;Awareness of diverse types of disabilities and related accessibility needs&lt;/li&gt;
    &lt;li&gt;Understanding of different types of design barriers preventing accessibility&lt;/li&gt;
    &lt;li&gt;Knowledge about different types of assistive tools and adaptive strategies&lt;/li&gt;
    &lt;li&gt;Appreciation for overlapping user needs and the principles of universal design&lt;/li&gt;
  &lt;/ul&gt;&lt;/dd&gt;
  &lt;dt&gt;&lt;strong&gt;Prerequisites for Learners&lt;/strong&gt;&lt;/dt&gt;
  &lt;dd&gt;[Basic] Basic understanding of computers and the Web.&lt;/dd&gt;
  &lt;dt&gt;&lt;strong&gt;Prerequisites for instructors&lt;/strong&gt;&lt;/dt&gt;
  &lt;dd&gt;[Advanced] In-depth knowledge of accessibility principles and universal design, and expertise in working with people with different types of disabilities.&lt;/dd&gt;
  &lt;dt&gt;&lt;strong&gt;Approximate Duration&lt;/strong&gt;&lt;/dt&gt;
  &lt;dd&gt;3-5 hours depending on activities.&lt;/dd&gt;
  &lt;dt&gt;&lt;strong&gt;Teaching Outline&lt;/strong&gt;&lt;/dt&gt;
  &lt;dd&gt;&lt;ul&gt;
    &lt;li&gt;&lt;strong&gt;Stories of people with disabilities&lt;/strong&gt; &amp;mdash; Provide tangible examples of people with disabilities using the Web. If possible, invite real users to demonstrate how they use the Web. Highlight the diversity of people with disabilities, trying to avoid as much as possible the medical model approach as well as some frequently encountered cliches, . Instead, concentrate  on how they use the Web. Emphasize how design and implementation cause barriers as opposed to barriers being inherent to the user (social model of disability).&lt;/li&gt;
    &lt;li&gt;&lt;strong&gt;Diverse abilities, tools, and barriers&lt;/strong&gt; &amp;mdash; Introduce examples of specific types of disabilities, including people with auditory, cognitive and learning, physical, speech, and visual disabilities. Introduce some of the design and implementation barriers that people encounter. Relate some of these barriers to personal experiences in using the Web, such as being overwhelmed by the content or confused by the navigation etc. Emphasize how every individual is unique.&lt;/li&gt;
    &lt;li&gt;&lt;strong&gt;Assistive tools and adaptive strategies&lt;/strong&gt; &amp;mdash; Provide an opportunity for learners to experience some types of assistive tools, such as a screen reader, and adaptive strategies, such as changing fonts and colors. Demonstrate use by experienced users of access technology, to avoid misunderstanding of the tools (assistive tools can be very complex and not intended for casual use). Exncourage learners to explore different settings in web browsers and operating systems.&lt;/li&gt;
    &lt;li&gt;&lt;strong&gt;Principles of universal design&lt;/strong&gt; &amp;mdash; Explain the overlapping accessibility needs of different users, such as "reading aloud" functionality benefiting people not seeing the screen and people with some forms of dyslexia. Explain that people could have combinations of disabilities, such as auditory and visual disabilities, especially with growing age. In particular, emphasize the people have very individual combinations of accessibility needs and preferences.&lt;/li&gt;
  &lt;/ul&gt;&lt;/dd&gt;
  &lt;dt&gt;&lt;strong&gt;Suggested Teaching Methods&lt;/strong&gt;&lt;/dt&gt;
  &lt;dd&gt;&lt;strong&gt;Experiential&lt;/strong&gt; &amp;mdash; Provide opportunity for learners to experience real people and tools. If possible, invite people with disabilities or show videos. Accompanying explanation and guidance is still required.&lt;/dd&gt;
  &lt;dt&gt;&lt;strong&gt;Suggested Teaching Materials&lt;/strong&gt;&lt;/dt&gt;
  &lt;dd&gt;&lt;ul&gt;
    &lt;li&gt;&lt;a href="https://www.w3.org/WAI/people-use-web/"&gt;How People with Disabilities Use the Web&lt;/a&gt; &amp;mdash; provides stories of people with diverse disabilities using the Web; enumerates different types of disabilities and some of the barriers that people encounter using the Web; and introduces different types of assistive tools and adaptive strategies that some people use.&lt;/li&gt;
    &lt;li&gt;&lt;a href="https://www.w3.org/WAI/perspective-videos/"&gt;Web Accessibility Perspectives (videos)&lt;/a&gt; &amp;mdash; series of 10 videos, each of around 1 minute duration, that highlight different types of accessibility features and how they impact people with disabilites and other users. For example, one video introduces colors with good contrast and how it benefits many people.&lt;/li&gt;
    &lt;li&gt;&lt;a href="https://www.w3.org/WAI/users/browsing"&gt;(outdated) Better Web Browsing: Tips for Customizing Your Computer&lt;/a&gt; &amp;mdash; provides references to resources to help users customize their particular web browser and computer setup, to improve their accessibility experience. It lists different types of settings and assistive tools that are available on different systems.&lt;/li&gt;
  &lt;/ul&gt;&lt;/dd&gt;
  &lt;dt&gt;&lt;strong&gt;Ideas for Assessment&lt;/strong&gt;&lt;/dt&gt;
  &lt;dd&gt;&lt;ul&gt;
    &lt;li&gt;&lt;strong&gt;Knowledge Questions&lt;/strong&gt; &amp;mdash; Learners should be able to explain different types of accessibility features, such as colors with good contrast, types of barriers, and types of assistive tools and adaptive strategies. &lt;br /&gt;&lt;em&gt;(Note: focus questions on functional aspects of accessibility rather than on medical conditions of people)&lt;/em&gt;&lt;/li&gt;
    &lt;li&gt;&lt;strong&gt;Demonstrations&lt;/strong&gt; &amp;mdash; Learners should be able to demonstrate what they have learned from exploring assistive tools and adaptive strategies, such as explaining different settings they found in their web browser.&lt;/li&gt;
  &lt;/ul&gt;&lt;/dd&gt;
  &lt;dt&gt;&lt;strong&gt;Notes&lt;/strong&gt;&lt;/dt&gt;
  &lt;dd&gt;&lt;ul&gt;
    &lt;li&gt;&lt;strong&gt;Ethical considerations&lt;/strong&gt; &amp;mdash; Consider the appropriate ethical aspects when working with people (also when showing videos of people); for example, ensure consent, provide compensation, and avoid patronizing behavior.&lt;/li&gt;
    &lt;li&gt;&lt;strong&gt;Cliches and myths&lt;/strong&gt; &amp;mdash; Unfortunately there are cliches, myths, and even stigmatization of people with disabilities, which could be unintentionally reinforced with caution. Experienced instructors are recommended.&lt;/li&gt;
    &lt;li&gt;&lt;strong&gt;Cultural apsects&lt;/strong&gt; &amp;mdash; The definition of disability and the approach to accessibility varies between different cultures. This can impact the initial level of awareness and acceptance for the topic by learners.&lt;/li&gt;
  &lt;/ul&gt;&lt;/dd&gt;
&lt;/dl&gt;

## Business Case and Benefits ##

&lt;dl&gt;
  &lt;dt&gt;&lt;strong&gt;Description&lt;/strong&gt;&lt;/dt&gt;
  &lt;dd&gt;Introduction to the business case for web accessibility, including social, technical, finanicial, and legal aspects, as well as the broader benefits of accessibility for most users of the Web.&lt;/dd&gt;
  &lt;dt&gt;&lt;strong&gt;Learning Outcomes&lt;/strong&gt;&lt;/dt&gt;
  &lt;dd&gt;&lt;ul&gt;
    &lt;li&gt;Awareness of access to information, including on the Web, as a human right&lt;/li&gt;
    &lt;li&gt;Understanding the imperative of accessibility for people with disabilities&lt;/li&gt;
    &lt;li&gt;Knowledge about applicable local and regional polices on web accessibility&lt;/li&gt;
    &lt;li&gt;Understanding specific examples of broader benefits of web accessibility&lt;/li&gt;
    &lt;li&gt;Understanding the relationship between accessibility, usability, and inclusion&lt;/li&gt;
    &lt;li&gt;Appreciation of accessibility and disability as part of diversity and inclusion&lt;/li&gt;
  &lt;/ul&gt;&lt;/dd&gt;
  &lt;dt&gt;&lt;strong&gt;Prerequisites for Learners&lt;/strong&gt;&lt;/dt&gt;
  &lt;dd&gt;[Basic] Basic understanding of computers and the Web.&lt;/dd&gt;
  &lt;dt&gt;&lt;strong&gt;Prerequisites for instructors&lt;/strong&gt;&lt;/dt&gt;
  &lt;dd&gt;[Medium] Good understanding of accessibility and inclusion, and experience in the types of business benefits resulting from accessibility.&lt;/dd&gt;
  &lt;dt&gt;&lt;strong&gt;Approximate Duration&lt;/strong&gt;&lt;/dt&gt;
  &lt;dd&gt;1-2 hours depending on demonstrated examples.&lt;/dd&gt;
  &lt;dt&gt;&lt;strong&gt;Teaching Outline&lt;/strong&gt;&lt;/dt&gt;
  &lt;dd&gt;&lt;ul&gt;
    &lt;li&gt;&lt;strong&gt;Social dimension of accessibility&lt;/strong&gt; &amp;mdash; Explain that access to information, including on the Web, is a human right under the UN Convention on the Rights of Persons with disabilities (CRPD). Highlight some of the international policies relating to web accessibility, and emphasize any applicable local policies. Explain the relevance of accessibility in today's increasingly digital world, and how the inclusion of people with disabilities is a social imperative.&lt;/li&gt;
    &lt;li&gt;&lt;strong&gt;Broader benefits of accessibility&lt;/strong&gt; &amp;mdash; Demonstrate how many of the accessibility features benefit most users of the Web. For example, demonstrate how accessibility benefits older people, people using mobile devices, people with lower digital skills, people who are not fluent in a language, etc. in additiong to ensuring access for people with disabilities. Emphasize the innovative aspects of accessibility, such as text-to-speech and speech-recognition.&lt;/li&gt;
    &lt;li&gt;&lt;strong&gt;Mainstreaming accessible design&lt;/strong&gt; &amp;mdash; Explain the relationships between accessibility, usability, and inclusion, and how these are best addressed together using a user-centered design process. Explain that accessibility and disability is part of the broader umbrella of diversity and inclusion, which is increasingly recognized as a business factor by many organizations internationally. Emphasize the need for an inclusive mindset and for leadership in management.&lt;/li&gt;
  &lt;/ul&gt;&lt;/dd&gt;
  &lt;dt&gt;&lt;strong&gt;Suggested Teaching Methods&lt;/strong&gt;&lt;/dt&gt;
  &lt;dd&gt;&lt;strong&gt;Presentational&lt;/strong&gt; &amp;mdash; Provide specific examples, studies, and references that speak to the particular audience. Where possible, relate examples to personal experiences of learners; for example using mobile devices.&lt;/dd&gt;
  &lt;dt&gt;&lt;strong&gt;Suggested Teaching Materials&lt;/strong&gt;&lt;/dt&gt;
  &lt;dd&gt;&lt;ul&gt;
    &lt;li&gt;&lt;a href="https://www.w3.org/WAI/business-case/"&gt;The Business Case for Digital Accessibility&lt;/a&gt; &amp;mdash; Explains the rational for organizations to pursue digital accessibility for people with disabilities. This includes driving innovation, enhancing brand, extending market reach, and minimizing legal risk. It includes cases studies from different organizations.&lt;/li&gt;
    &lt;li&gt;&lt;a href="https://www.w3.org/WAI/perspective-videos/"&gt;Web Accessibility Perspectives (videos)&lt;/a&gt; &amp;mdash; series of 10 videos, each of around 1 minute duration, that highlight different types of accessibility features and how they impact people with disabilites and other users. For example, one video introduces colors with good contrast and how it benefits many people.&lt;/li&gt;
    &lt;li&gt;&lt;a href="https://www.w3.org/WAI/older-users/"&gt;Older Users and Web Accessibility: Meeting the Needs of Ageing Web Users&lt;/a&gt; &amp;mdash; Explains the overlapping needs of ageing web users and web users with disabilities, and how accessibility addresses both situations. This resource refers to further background materials, including statistics on older people.&lt;/li&gt;
    &lt;li&gt;&lt;a href="https://www.w3.org/WAI/standards-guidelines/wcag-mobile-overlap/"&gt;[Archived] Web Content Accessibility and Mobile Web: Making a Website Accessible Both for People with Disabilities and for Mobile Devices&lt;/a&gt; &amp;mdash; Explains some of the shared experiences using the Web for people using mobile devices and people with disabilities (archived content).&lt;/li&gt;
    &lt;li&gt;&lt;a href="https://www.w3.org/WAI/fundamentals/accessibility-usability-inclusion/"&gt;Accessibility, Usability, and Inclusion&lt;/a&gt; &amp;mdash; Explains the distinctions and overlaps between the terms accessibility, usability, and inclusion, and how these are best addressed together using a user-centered design process.&lt;/li&gt;
    &lt;li&gt;&lt;a href="https://www.w3.org/WAI/policies/"&gt;Web Accessibility Laws &amp;amp; Policies&lt;/a&gt; &amp;mdash; Lists some of the laws and policies relating to web and digital accessibility internationally.&lt;/li&gt;
    &lt;li&gt;&lt;a href="https://www.un.org/development/desa/disabilities/convention-on-the-rights-of-persons-with-disabilities.html"&gt;Convention on the Rights of Persons with Disabilities (CRPD)&lt;/a&gt; &amp;mdash; Lists the countries that signed and ratified the convention and optional protocol, and provides news and information on implementation of the convention.&lt;/li&gt;
  &lt;/ul&gt;&lt;/dd&gt;
  &lt;dt&gt;&lt;strong&gt;Ideas for Assessment&lt;/strong&gt;&lt;/dt&gt;
  &lt;dd&gt;&lt;ul&gt;
    &lt;li&gt;&lt;strong&gt;Knowledge Questions&lt;/strong&gt; &amp;mdash; Learners should be able to explain different business case arguments for digital accessibility, and broader benefits of accessibility for people in different situations and contexts.&lt;/li&gt;
    &lt;li&gt;&lt;strong&gt;Presentations&lt;/strong&gt; &amp;mdash; Learners should be able to develop potential business case arguments for their own organization, and present this to other learners as examples of how they can apply what they have learned.&lt;/li&gt;
  &lt;/ul&gt;&lt;/dd&gt;
  &lt;dt&gt;&lt;strong&gt;Notes&lt;/strong&gt;&lt;/dt&gt;
  &lt;dd&gt;&lt;ul&gt;
    &lt;li&gt;&lt;strong&gt;Cultural apsects&lt;/strong&gt; &amp;mdash; The cultural acceptance and approach to accessibility and disability varies between countries and even individual organizations. The business case arguments may need to be adjusted accordingly.&lt;/li&gt;
    &lt;li&gt;&lt;strong&gt;Business context&lt;/strong&gt; &amp;mdash; The business context that learners are used to may also require adjustment of the business case arguments. For example, to better relate to their industry sector and organizational culture.&lt;/li&gt;
  &lt;/ul&gt;&lt;/dd&gt;
&lt;/dl&gt;

## Standards and Guidelines ##

&lt;dl&gt;
  &lt;dt&gt;&lt;strong&gt;Description&lt;/strong&gt;&lt;/dt&gt;
  &lt;dd&gt;Overview on the international accessibility standards and guidelines from the W3C Web Accessibility Initiative (WAI), including the W3C Web Content Accessibility Guidelines (WCAG), and how these are developed.&lt;/dd&gt;
  &lt;dt&gt;&lt;strong&gt;Learning Outcomes&lt;/strong&gt;&lt;/dt&gt;
  &lt;dd&gt;&lt;ul&gt;
    &lt;li&gt;Knowledge of WCAG, ATAG, UAAG, and WAI-ARIA and their relevance for accessibility&lt;/li&gt;
    &lt;li&gt;Knowledge of how they are developed and their adoption by businesses internationally&lt;/li&gt;
    &lt;li&gt;Understanding the terms Perceivable, Operable, Understandable, and Robust (POUR)&lt;/li&gt;
    &lt;li&gt;Awareness of different design and development guidelines, and examples for each&lt;/li&gt;
    &lt;li&gt;Ability to carry out preliminary evaluation of simple web pages for accessibility&lt;/li&gt;
  &lt;/ul&gt;&lt;/dd&gt;
  &lt;dt&gt;&lt;strong&gt;Prerequisites for Learners&lt;/strong&gt;&lt;/dt&gt;
  &lt;dd&gt;[Basic] Basic understanding of computers and the Web.&lt;/dd&gt;
  &lt;dt&gt;&lt;strong&gt;Prerequisites for instructors&lt;/strong&gt;&lt;/dt&gt;
  &lt;dd&gt;[Medium] Good understanding of the W3C accessibility standards and guidelines, and knowledge of how to check potential accessibility barriers.&lt;/dd&gt;
  &lt;dt&gt;&lt;strong&gt;Approximate Duration&lt;/strong&gt;&lt;/dt&gt;
  &lt;dd&gt;2-4 hours depending on activities.&lt;/dd&gt;
  &lt;dt&gt;&lt;strong&gt;Teaching Outline&lt;/strong&gt;&lt;/dt&gt;
  &lt;dd&gt;&lt;ul&gt;
    &lt;li&gt;&lt;strong&gt;Components of web accessibility&lt;/strong&gt; &amp;mdash; Revise the inter-relationship between accessibility features in web technologies such as HTML, in web content, web authoring tools, web browsers, and assistive tools, which were introduced in the first teaching unit of this module. Relate this back to more specific examples for the second teaching module and highlight the broader benefits of these examples. Reiterate that accessibility encompasses many types of roles and responsibilities.&lt;/li&gt;
    &lt;li&gt;&lt;strong&gt;Web Content Accessibility Guidelines (WCAG)&lt;/strong&gt; &amp;mdash; Introduce the scope of "web content" in WCAG, which includes desktop and mobile websites and applications. Highlight that there are currently two operational versions, 2.0 and 2.1, with 2.0 being a subset of 2.1 that provides improvements for people with cognitive and learning disabilities, people with low vision, and people with disabilities using mobile devices. Refer to the uptake of WCAG in different policies and standards.&lt;/li&gt;
    &lt;li&gt;&lt;strong&gt;Authoring Tool Accessibility Guidelines (ATAG)&lt;/strong&gt; &amp;mdash; Introduce the scope of "authoring tools" in ATAG, which include diverse content production tools including text and graphic based code editing tools, content management systems (CMS), conversion tools, and social media platforms. Emphasize the relevance of authoring tools given the volume of content being generated very day, usually created by non-technical content authors without accessibility expertise.&lt;/li&gt;
    &lt;li&gt;&lt;strong&gt;User Agent Accessibility Guidelines (UAAG)&lt;/strong&gt; &amp;mdash; Introduce the scope of "user agents" in UAAG, which include diverse applications including web browsers, web-based media players, and some types of assistive tools and mobile applications that allow users to access and interact with web content. Emphasize the relevance of user agents, which are key to supporting accessibility features in web technologies and content; lack of accessibility support is a primary barrier.&lt;/li&gt;
    &lt;li&gt;&lt;strong&gt;Accessible Rich Internet Applications (WAI-ARIA)&lt;/strong&gt; &amp;mdash; Explain that this accessibility standard does not define accessibility requirements but rather provides a mechanism for authors to embed semantics in web content, to facolitate interoperability with assistive tools. Emphasize that many of these semantics are meanwhile integrated directly in HTML5, which should be used natively whenever possible. WAI-ARIA can also be used with other technologies, such as SVG.&lt;/li&gt;
    &lt;li&gt;&lt;strong&gt;Open standards development&lt;/strong&gt; &amp;mdash; Explain that these W3C accessibility standards and guidelines are developed following an open consensus process, with involvement of representation of people with disabilities, industry, public bodies, research, and individual experts. W3C Working Groups publish working drafts periodically for comments from the public. Everyone is encouraged to comments, to help include many perspectives thus ensure broad consensus around these standards.&lt;/li&gt;
    &lt;li&gt;&lt;strong&gt;Web accessibility principles&lt;/strong&gt; &amp;mdash; Explain the terms Perceivable, Operable, Understandable, and Robust (POUR) based on how they are defined in WCAG. Introduce the Guidelines defined by WCAG for each of these terms, and provide specific examples to help explain the meaning and relevance of each. For example, provide a specific example of the Guideline 1.4 Distinguishable. Emphasize how such requirements are essential for people with disabilities and benefit all.&lt;/li&gt;
    &lt;li&gt;&lt;strong&gt;First checks for web accessibility principles&lt;/strong&gt; &amp;mdash; Guide learners through preliminary checks for web accessibility on simple web pages; for example, to identify page headings and their relative order, use by keyboard and other indicative checks (not full conformance evaluation, which requires technical skills and further accessibility knowledge). Ask learners to explore different types of websites and relate their finds to the accessibility principles and guidelines.&lt;/li&gt;
  &lt;/ul&gt;&lt;/dd&gt;
  &lt;dt&gt;&lt;strong&gt;Suggested Teaching Methods&lt;/strong&gt;&lt;/dt&gt;
  &lt;dd&gt;&lt;strong&gt;Interactive&lt;/strong&gt; &amp;mdash; To make many terms and definitions more tangible, ask learners to provide examples of web content, authoring tools, user agents, and of situations relating to the accessibility guidelines defined by WCAG.&lt;/dd&gt;
  &lt;dt&gt;&lt;strong&gt;Suggested Teaching Materials&lt;/strong&gt;&lt;/dt&gt;
  &lt;dd&gt;&lt;ul&gt;
    &lt;li&gt;&lt;a href="https://www.w3.org/WAI/fundamentals/components/"&gt;Essential Components of Web Accessibility&lt;/a&gt; &amp;mdash; explains key terms, and the inter-relation between different components of web accessibility (eg. web technologies, authoring tools, browsers, etc.).&lt;/li&gt;
    &lt;li&gt;&lt;a href="https://www.w3.org/WAI/standards-guidelines/"&gt;W3C Accessibility Standards Overview&lt;/a&gt; &amp;mdash; Provides an overview on the W3C accessibility standards and guidelines developed and maintained by the W3C Web Accessibility Initiative (WAI). These include the following standards and guidelines:
      &lt;ul&gt;
        &lt;li&gt;&lt;a href="https://www.w3.org/WAI/standards-guidelines/wcag/"&gt;Web Content Accessibility Guidelines (WCAG) Overview&lt;/a&gt; &amp;mdash; Provides an overview on WCAG, including "WCAG At a Glance" summary (and handout), and other supporting materials.&lt;/li&gt;
        &lt;li&gt;&lt;a href="https://www.w3.org/WAI/standards-guidelines/atag/"&gt;Authoring Tool Accessibility Guidelines (ATAG) Overview&lt;/a&gt; &amp;mdash; Provides an overview on ATAG, including "ATAG At a Glance" summary (and handout), and other supporting materials.&lt;/li&gt;
        &lt;li&gt;&lt;a href="https://www.w3.org/WAI/standards-guidelines/uaag/"&gt;User Agent Accessibility Guidelines (UAAG) Overview&lt;/a&gt; &amp;mdash; Provides an overview on UAAG, including "UAAG At a Glance" summary (and handout), and other supporting materials.&lt;/li&gt;
        &lt;li&gt;&lt;a href="https://www.w3.org/WAI/standards-guidelines/aria/"&gt;WAI-ARIA Overview&lt;/a&gt; &amp;mdash; Provides an overview on WAI-ARIA, including its accompaying standards and application programming interfaces (APIs).&lt;/li&gt;
      &lt;/ul&gt;
    &lt;/li&gt;
    &lt;li&gt;&lt;a href="https://www.w3.org/WAI/standards-guidelines/w3c-process/"&gt;How WAI Develops Accessibility Standards through the W3C Process: Milestones and Opportunities to Contribute&lt;/a&gt; &amp;mdash; Provides a simplified overview on the W3C standards development process, and the opportunities that it provides for members of the public to provide feedback into the process.&lt;/li&gt;
    &lt;li&gt;&lt;a href="https://www.w3.org/WAI/fundamentals/accessibility-principles/"&gt;Accessibility Principles&lt;/a&gt; &amp;mdash; Introduces the principles and guidelines defined by WCAG in less technical terms, and relates these requirements to ATAG and UAAG.&lt;/li&gt;
    &lt;li&gt;&lt;a href="https://www.w3.org/WAI/test-evaluate/preliminary/"&gt;Easy Checks - A First Review of Web Accessibility&lt;/a&gt; &amp;mdash; Provides instructions to check few accessibility issues relating to different accessibility guidelines. These checks are designed to be quick and easy for many audiences, rather than definitive conformance assessments for accessibility.&lt;/li&gt;
    &lt;li&gt;&lt;a href="https://www.w3.org/WAI/demos/bad/"&gt;Before and After Demonstration (BAD)&lt;/a&gt; &amp;mdash; Is a miniture website in an accessible and inaccessible version, provided with evaluation reports and annotations of the barriers and accessibility repairs. It is designed for more technical audiences who want to explore different types of accessibility barriers and their repair.&lt;/li&gt;
    &lt;li&gt;&lt;a href="https://www.w3.org/WAI/standards-guidelines/harmonization/"&gt;Why Standards Harmonization is Essential to Web Accessibility&lt;/a&gt; &amp;mdash; Explains the need for a common understanding of web accessibility internationally, to facilitate the exachange of practices, tools, and skills, thereby accelerating the adoption and implementation of web accessibility.&lt;/li&gt;
  &lt;/ul&gt;&lt;/dd&gt;
  &lt;dt&gt;&lt;strong&gt;Ideas for Assessment&lt;/strong&gt;&lt;/dt&gt;
  &lt;dd&gt;&lt;ul&gt;
    &lt;li&gt;&lt;strong&gt;Knowledge Questions&lt;/strong&gt; &amp;mdash; Learners should be able to explain the principles of web accessibility and enumerate different guidelines. Learners should be able to provide examples web content, authoring tools, and user agents.&lt;/li&gt;
    &lt;li&gt;&lt;strong&gt;Presentations&lt;/strong&gt; &amp;mdash; Learners should be able to carry out first checks of accessibility principles on simple web pages. Learners can compare the accessibility of different websites or different pages on the same website.&lt;/li&gt;
  &lt;/ul&gt;&lt;/dd&gt;
  &lt;dt&gt;&lt;strong&gt;Notes&lt;/strong&gt;&lt;/dt&gt;
  &lt;dd&gt;&lt;ul&gt;
    &lt;li&gt;&lt;strong&gt;Technical jargon&lt;/strong&gt; &amp;mdash; This teaching unit explores teachnical standards and resources, which include technical jargon. It will be important to explain terms and phrases in a more understandable way to most learners.&lt;/li&gt;
  &lt;/ul&gt;&lt;/dd&gt;
&lt;/dl&gt;

## Get Started with Accessibility ##

&lt;dl&gt;
  &lt;dt&gt;&lt;strong&gt;Description&lt;/strong&gt;&lt;/dt&gt;
  &lt;dd&gt;Overview on different accessibility roles and responsibilities involved throughout the design and development process, and on organizational planning and managing considerations to ensure accessibility as part of the process.&lt;/dd&gt;
  &lt;dt&gt;&lt;strong&gt;Learning Outcomes&lt;/strong&gt;&lt;/dt&gt;
  &lt;dd&gt;&lt;ul&gt;
    &lt;li&gt;Understanding different roles and scope of their accessibility responsibilities&lt;/li&gt;
    &lt;li&gt;Understanding different organizational considerations to plan and manage accessibility&lt;/li&gt;
    &lt;li&gt;Understanding the importance of involving people with disabilities throughout&lt;/li&gt;
    &lt;li&gt;Ability to reflect on the accessibility capability and maturity of organizations&lt;/li&gt;
  &lt;/ul&gt;&lt;/dd&gt;
  &lt;dt&gt;&lt;strong&gt;Prerequisites for Learners&lt;/strong&gt;&lt;/dt&gt;
  &lt;dd&gt;[Basic] Basic understanding of computers and the Web.&lt;/dd&gt;
  &lt;dt&gt;&lt;strong&gt;Prerequisites for instructors&lt;/strong&gt;&lt;/dt&gt;
  &lt;dd&gt;[Medium] Good understanding of how to introduce and integrate accessibility considerations throughout organizational processes.&lt;/dd&gt;
  &lt;dt&gt;&lt;strong&gt;Approximate Duration&lt;/strong&gt;&lt;/dt&gt;
  &lt;dd&gt;2-3 hours depending on activities.&lt;/dd&gt;
  &lt;dt&gt;&lt;strong&gt;Teaching Outline&lt;/strong&gt;&lt;/dt&gt;
  &lt;dd&gt;&lt;ul&gt;
    &lt;li&gt;&lt;strong&gt;Accessibility roles and responsibilities&lt;/strong&gt; &amp;mdash; Explain the different types of roles involved in implementing web accessibility, and introduce the scope of their responsibilities throughout the design and development process. Emphasize that accessibility is not primarily a technical aspect but actually an organizational aspect. Explain the need for everyone involved throughout the design and development process to have an adequate level of awareness and skills.&lt;/li&gt;
    &lt;li&gt;&lt;strong&gt;Planning and managing web accessibility&lt;/strong&gt; &amp;mdash; Introduce specific considerations to integrate accessibility throughout the design process. This includes ensuring management commitment to accessibilit, assigning appropriate roles and responsibilities, providing technical and financial resources, and ensuring quality management. Explain how the capability and maturity of an organization with regard to web accessibility can be assessed based on these considerations.&lt;/li&gt;
    &lt;li&gt;&lt;strong&gt;Involving people with disabilities throughout&lt;/strong&gt; &amp;mdash; Explain the importance of involving real users with disabilities early on in the design process, and throughout the development and maintenances stages of websites. Emphasize how usability testing with people with disabilities also addresses mainstream audiences as well as people with situational limitiations. Explain the ethical considerations required when working with people, including people with disabilities.&lt;/li&gt;
    &lt;li&gt;&lt;strong&gt;Developing policies on web accessibility&lt;/strong&gt; &amp;mdash; Explain the importance of putting accessibility policies in place, to document organizational commitments and to encourage implementation of web accessibility. If possible, publicly available accessibility statements help increase the commitment to accessibility and communicate the efforts undertaken by organizations towards accessibility. Ask learners to reflect on general use of policies at their organization.&lt;/li&gt;
    &lt;li&gt;&lt;strong&gt;Responding to accessibility questions&lt;/strong&gt; &amp;mdash; Explain the importance of responding to accessibility queries and complaints. Often issues can be addressed more easily than anticipated, and responsiveness demonstrates cutomer care. Introduce some of the strategies that can be used to prioritize issues and pursue interim repairs, which can become necessary when accessibility is not considered from the start of the design and development process.&lt;/li&gt;
  &lt;/ul&gt;&lt;/dd&gt;
  &lt;dt&gt;&lt;strong&gt;Suggested Teaching Methods&lt;/strong&gt;&lt;/dt&gt;
  &lt;dd&gt;&lt;strong&gt;Presentational&lt;/strong&gt; &amp;mdash; Introduce the different types of roles and responsibilities, and considerations for integrating accessibility throughout the design and development process. Encoruage learners to reflect on these.&lt;/dd&gt;
  &lt;dt&gt;&lt;strong&gt;Suggested Teaching Materials&lt;/strong&gt;&lt;/dt&gt;
  &lt;dd&gt;&lt;ul&gt;
    &lt;li&gt;&lt;a href="https://www.w3.org/WAI/EO/wiki/Role_definition_document"&gt;(Work in progress) Accessibility Roles and Responsibilities Mapping (ARRM): Role Definition&lt;/a&gt; &amp;mdash; Defines a variety of roles relevant for accessibility throughout the design and development process. It includes examples tasks in accessibility for each of the roles defined.&lt;/li&gt;
    &lt;li&gt;&lt;a href="https://www.w3.org/WAI/planning-and-managing/"&gt;Planning and Managing Web Accessibility&lt;/a&gt; &amp;mdash; Enumerates and explains a broad selection of organizational considerations relating to web accessibility. These are organized according to web project management stages of "Initiate", "Plan", "Implement", and "Sustain", to help fit into organizational processes.&lt;/li&gt;
    &lt;li&gt;&lt;a href="https://www.w3.org/WAI/planning/involving-users/"&gt;Involving Users in Web Projects for Better, Easier Accessibility&lt;/a&gt; &amp;mdash; Explains the benefits of involving real users with disabilities from the inception of web projects throguhtout their design and development stages, and provides advice on working with people with disabilities effectively.&lt;/li&gt;
    &lt;li&gt;&lt;a href="https://www.w3.org/WAI/planning/org-policies/"&gt;Developing Organizational Policies on Web Accessibility&lt;/a&gt; &amp;mdash; Provides step-by-step guidance on developing organizational policies relating to web accessibility. It is part of the broader "Planning and Managing Web Accessibility" resource, to help guide through this particular organizational step.&lt;/li&gt;
    &lt;li&gt;&lt;a href="https://www.w3.org/WAI/planning/statements/"&gt;Developing an Accessibility Statement&lt;/a&gt; &amp;mdash; Provides guidance and a free generator tool to help website and application owners to create accessibility statements. It encourages organizations to communicate their commitment to accessibility and to provide feedback channels for user with disabilities.&lt;/li&gt;
    &lt;li&gt;&lt;a href="https://www.w3.org/WAI/planning/interim-repairs/"&gt;Web Accessibility First Aid: Approaches for Interim Repairs&lt;/a&gt; &amp;mdash; Introduces approaches to help organizations prioritize and address pressing issues, while building towards more comprehensive approaches to implement accessibility. It is part of the broader "Planning and Managing Web Accessibility" resource.&lt;/li&gt;
    &lt;li&gt;&lt;a href="https://www.w3.org/WAI/teach-advocate/contact-inaccessible-websites/"&gt;Contacting Organizations about Inaccessible Websites&lt;/a&gt; &amp;mdash; Provides guidance for users with disabilities on how to contact organizations when they observe accessibility barriers. It encourages communication and exchange between organizations and their website users.&lt;/li&gt;
  &lt;/ul&gt;&lt;/dd&gt;
  &lt;dt&gt;&lt;strong&gt;Ideas for Assessment&lt;/strong&gt;&lt;/dt&gt;
  &lt;dd&gt;&lt;ul&gt;
    &lt;li&gt;&lt;strong&gt;Knowledge Questions&lt;/strong&gt; &amp;mdash; Learners should be able to enumerate different roles and responsibilities involved in web accessibility, and different organizational considerations to plan for and manage implementation.&lt;/li&gt;
    &lt;li&gt;&lt;strong&gt;Reflections&lt;/strong&gt; &amp;mdash; Learners should be able to reflect on the capacity and maturity of their own organizations regarding web accessibility with respect to (lack of) accessibility processes and practices put in place.&lt;/li&gt;
  &lt;/ul&gt;&lt;/dd&gt;
  &lt;dt&gt;&lt;strong&gt;Notes&lt;/strong&gt;&lt;/dt&gt;
  &lt;dd&gt;&lt;ul&gt;
    &lt;li&gt;&lt;strong&gt;Business context&lt;/strong&gt; &amp;mdash; The business context that learners are used to may also require adjustment of the suggested considerations. For example, policies often apply differently to public and private bodies.&lt;/li&gt;
  &lt;/ul&gt;&lt;/dd&gt;
&lt;/dl&gt;
</pre>
  </body>
</html>
