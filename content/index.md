---
title: "Curricula on Web Accessibility: A Framework to Build Your Own Courses"
title_html: "Curricula on Web Accessibility: <br /><small>A Framework to Build Your Own Courses</small>"
permalink: /curricula/
ref: /curricula/
lang: en
github:
  repository: w3c/wai-curricula
  path: content/index.md
license: creative-commons
acknowledgements: /curricula/acknowledgements/
footer: >
  <p><strong>Date:</strong> $Date</p>
  <p><strong>Editors:</strong> Daniel Montalvo and <a href="http://www.w3.org/People/shadi/">Shadi Abou-Zahra</a>. Contributors: <a href="https://www.w3.org/WAI/EO/EOWG-members">EOWG Participants</a>. ACKNOWLEDGEMENTS lists contributors and credits.</p>
  <p>Developed by the Education and Outreach Working Group (<a href="http://www.w3.org/WAI/EO/">EOWG</a>). Developed with support from the <a href="https://www.w3.org/WAI/about/projects/wai-guide/">WAI-Guide Project</a> funded by the European Commission (EC) under the Horizon 2020 program (Grant Agreement 822245).</p>
navigation:
  next: /curricula/foundation-modules/
---

{::nomarkdown}
{% include box.html type="start" title="Summary" class="" %}
{:/}

This resource provides a variety of teaching modules that you can combine to create different courses on web accessibility. For example, you can use these modules to include accessibility aspects in courses on digital technology more broadly as well as to create training specifically on digital accessibility.

You can also use these modules to write procurement requirements and to compare courses, training, and certification programs.

This resource includes the following parts:

* [Foundation Modules](/curricula/foundation-modules) suitable for everybody in <abbr title="Information Technology">IT</abbr>
* [Developer Modules](/curricula/developer-modules/) primarily related to front-end development
* Designer Modules (in progress) primarily related to visual and user-experience (UX) design
* Author Modules (in progress) primarily related to content publishing

{::nomarkdown}
{% include box.html type="end" title="Summary" class="" %}
{:/}

{::options toc_levels="2,3" /}
{::nomarkdown}
{% include toc.html type="start" title="Page Contents" %}
{:/}

- This will be replaced by an automatically generated TOC when using Markdown formatting.
{:toc}

{::nomarkdown}
{% include toc.html type="end" %}
{:/}

## Accessibility Curricula Overview

You can use this resource in a variety of situations. Some examples include:

* **faculty lecturer** wants to teach computer science students about accessibility
* **accessibility professional** wants to create training specifically on accessibility
* **product owner** wants to compare course content offered by different providers
* **procurer** wants to include specific requirements in a Request for Proposals (RFP)
* **hiring manager** wants to compare competencies assessed for different certificates

You can combine different modules from the entire resource to create and compare courses, training, and certification programs. For example, teaching accessibility to computer science students likely involves a combination of foundation, developer, and designer modules. On the other hand, assessing the accessibility knowledge of front-end developers likely involves a combination of foundation and developer modules. This resource does not prescribe specific combinations and order of modules for different programs. It also does not prescribe the duration, effort, or accreditation associated with each. It provides a reference for the learning outcomes on a modular level.

<table class="dense">
 <caption>Overview on Curricula Modules</caption>
    <tr>
      <th colspan="3"> <a href="{{ '/curricula/foundation-modules/' | relative_url }}">Foundation Modules</a> </th>
    </tr>
    <tr>
      <td colspan="3">
        <ul>
          <li><a href="{{ '/curricula/foundation-modules/what-is-web-accessibility/' | relative_url }}">Module 1: What is Web accessibility</a></li>
          <li><a href="{{ '/curricula/foundation-modules/people-and-digital-technology/' | relative_url }}">Module 2: People and Digital Technology</a></li>
          <li><a href="{{ '/curricula/foundation-modules/business-case-and-benefits/' | relative_url }}">Module 3: Business Case and Benefits</a></li>
          <li><a href="{{ '/curricula/foundation-modules/principles-standards-and-checks/' | relative_url }}">Module 4: Principles, Standards, and Checks</a></li>
          <li><a href="{{ '/curricula/foundation-modules/getting-started-with-accessibility/' | relative_url }}">Module 5: Getting Started with accessibility</a></li>
        </ul>
      </td>
    </tr>
    <tr>
      <th> <a href="{{ '/curricula/developer-modules/' | relative_url }}">Developer Modules</a> </th>
      <th> Designer Modules (<abbr title="To be Developed">TBD</abbr>) </th>
      <th> Author Modules (<abbr title="To be Developed">TBD</abbr>) </th>
    </tr>
    <tr>
      <td>
        <ul>
         <li> <a href="{{ '/curricula/developer-modules/page-structure/' | relative_url }}">Module 1: Page Structure</a></li>
          <li> <a href="{{ '/curricula/developer-modulespage-structure/menus/' | relative_url }}">Module 2: Menus</a></li>
          <li> <a href="{{ '/curricula/developer-modules/images/' | relative_url }}">Module 3: Images</a></li>
          <li> <a href="{{ '/curricula/developer-modules/tables/' | relative_url }}">Module 4: Tables</a></li>
          <li> <a href="{{ '/curricula/developer-modules/forms/' | relative_url }}">Module 5: Forms</a></li>
          <li> <a href="{{ '/curricula/developer-modules/custom-widgets/' | relative_url }}">Module 6: Custom Widgets</a></li>
          <li> <a href="{{ '/curricula/developer-modules/rich-applications/' | relative_url }}">Module 7: Rich Applications</a></li>
        </ul>
      </td>
      <td>
        <ul>
          <li> Navigation and Orientation </li>
          <li> Layout and Structure </li>
          <li>Colors, Fonts, and Graphics </li>
          <li> Information Architecture </li>
          <li> Forms, Instructions, and Feedback </li>
          <li> Custom Widgets and Interaction</li>
          <li> &hellip; </li>
        </ul>
      </td>
      <td>
        <ul>
          <li> Headings and Structure</li>
          <li> Navigational Cues </li>
          <li> Alternatives for Images, Graphics, and Multimedia </li>
          <li> Document accessibility </li>
          <li> Tables and Data Representation</li>
          <li> Form Instructions and Feedback </li>
          <li> &hellip; </li>
        </ul>
      </td>
    </tr>
</table>

## Structure and Terminology

This resource consists of the four curricula described in the previous section. Each curriculum consists of:

* Prerequisites &mdash; Competencies expected for students to have previously acquired
* Modules &mdash; Designed to be taught and assessed in their entirety. Each module consists of:
  * Learning Outcomes for Module &mdash; What students will learn and should be able to demonstrate.
  * Competencies &mdash; Skills required for students and instructors to teach the curriculum.
  * Topics to Teach &mdash; Recommended themes to be taught in any order. Each topic consists of:
    * Learning Outcomes for Topic &mdash; Detailed description of what students will learn and should be able to demonstrate.
    * Teaching Ideas for Topic &mdash; Suggested ideas to help instructors teach the learning outcomes based on topic contents.
    * Ideas to assess knowledge for Topic &mdash; Suggested ideas to assess the acquired skills or knowledge based on topic contents.
  * Ideas to Assess Knowledge for Module &mdash; Suggested ideas to assess the acquired skills or knowledge based on module contents.
  * Teaching Resources &mdash; Resources to help teach the learning outcomes. Some resources are integral part of the teaching while others are optional further reading.

Terminology specifically related to people with disabilities, assistive technologies, and adaptive strategies is provided in [How people with disabilities use the Web](/people-use-web).

## Tips on Teaching Accessibility

The following tips will help you ensure effective courses, training, and certification programs on accessibility.

### Involve People with Disabilities

One of the most effective ways to learn and teach accessibility is by involving people with disabilities. This includes inviting people with disabilities to show how they use assistive technologies and adaptive strategies to interact on the Web, the accessibility features they rely on, and challenges they sometimes encounter. If you cannot invite people with disabilities, maybe you can find suitable videos instead. Yet make sure to guide your students through the process to avoid perpetuating existing misunderstandings. For guidance on working with people with disabilities, ethical considerations, and cautions, refer to [Involving Users in Web Projects for Better, Easier Accessibility](/planning/involving-users/).

### Communicate the Impact

Often teachings focus too much on the *how* and insufficiently on the *why*. Yet understanding the motivations for accessibility is essential to ensuring solutions that are usable in practice. Good practice for courses, training, and certification programs is to ensure that students understand the impact of accessibility barriers and features on people with disabilities. This includes how the learning outcomes, the teaching methods, and knowledge assessments are designed. For example, students should not only know the different ways to provide text alternatives for images. They should also know in which situations each method is more appropriate from the perspective of the user.

### Embrace Universal Design

Avoid inadvertent prioritizing of one perceived group of people over another. Accessibility requirements for people with different disabilities overlap without clear boundaries. For example, captions support people who are deaf and hard of hearing as well as people with some forms of cognitive and learning disabilities. Good practice for courses, training, and certification programs is ensure that students understand the concepts of universal design to create accessible and inclusive experiences for everyone. For guidance on cross-disability aspects, refer to [How people with disabilities use the Web](/people-use-web).

### Explain Roles and Responsibilities

Accessibility is the responsibility of everyone involved throughout the inception, planning, design, development, and on-going maintenance of websites and applications. Make sure that students understand the relationships between different roles involved, and the implications of this on different tasks. For example, creating an accessible form requires collaboration between the content author, designer, and developer, as well as resource allocation from the project manager. Even if you are teaching only one of these roles, make sure that students understand the scope of their responsibility in relation to others.

### Make it Accessible

Good practice is to ensure that courses, training, and certification programs are accessible. This includes all presentations, teaching materials, exercises, assessments, and other student interactions. For example, ensure that the online learning platform, the classroom, computer lab, or training venue are accessible. Ensure that, for example, captioning, sign-language interpretation, and large-print formats are provided when needed. Also ensure that instructors read aloud what is on the screen and describe any visual information through audio. For more guidance, refer to [How to Make Your Presentations Accessible to All](/teach-advocate/accessible-presentations/).
