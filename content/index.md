---
title: "Pronunciation Overview"
permalink: /pronunciation/
ref: /pronunciation/
lang: en
# translators: # Uncomment (remove #) for translations, one - name line per translator.
# - name: Translator 1
# contributors:
# - name: Contributor 1
github:
  repository: wai-pronunciation
  path: 'content/index.md'
footer: >
  <p><strong>Date:</strong> Updated 14 April 2020.</p>
  <p><strong>Editors:</strong> <a href="http://www.w3.org/People/Shawn/">Shawn Lawton Henry</a> and <a href="http://www.w3.org/People/roy/">Ruoxi Ran</a>.</p>
  <p>Developed with input from the <a href="https://www.w3.org/WAI/APA/task-forces/pronunciation/">Pronunciation Task Force</a>.<p>
---

{::nomarkdown}
{% include box.html type="start" title="Summary" class="" %}
{:/}

This page introduces work on pronunciation. The goal is to provide normative specifications and best practices guidance so that text-to-speech (TTS) synthesis can provide proper pronunciation of HTML content.

Quick links to initial analysis documents:
* [Explainer: Improving Spoken Presentation on the Web _(Working Draft Note)_](https://www.w3.org/TR/pronunciation-explainer/)
* [Pronunciation User Scenarios _(Working Draft Note)_](https://www.w3.org/TR/pronunciation-user-scenarios/)
* [Pronunciation Gap Analysis and Use Cases _(Working Draft Note)_](https://www.w3.org/TR/pronunciation-gap-analysis-and-use-cases/)

{::nomarkdown}
{% include box.html type="end" %}
{:/}

{% include toc.html %}

## Introduction

Most people who are blind rely on specialized text-to-speech (TTS) software called screen readers. Some people with cognitive disabilities who have difficulty processing written text also use screen readers.

Text-to-speech is essential for people with disabilities and useful for all. Accurate pronunciation is essential in many situations, such as education and assessment (testing students). Many computers and mobile devices today have built in text-to-speech functionality that is used by people without disabilities in different situations, such as when they lose their glasses or their eyes are tired.

Currently text-to-speech pronunciation is often inaccurate and inconsistent because of technology limitations. For example, incorrect pronunciation based on context, regional variation, or emphasis.

W3C is working toward developing normative specifications and best practices guidance so that text-to-speech (TTS) synthesis can provide proper pronunciation of HTML content. The documents below provide the foundation for this work.

## Basics

**[Explainer: Improving Spoken Presentation on the Web](https://www.w3.org/TR/pronunciation-explainer/)** provides an overview of the work. It:

- Briefly introduces the context for W3C work on pronunciation
- Describes the advantages and disadvantages of two approaches
- Poses questions for additional input

## User Scenarios and User Requirements

**[Pronunciation User Scenarios](https://www.w3.org/TR/pronunciation-user-scenarios/)** provides examples of:
- End-users, including screen reader users
- Content providers, including educators
- Software developers, including content managements systems

The **[Core Features for Pronunciation and Spoken Presentation section](https://www.w3.org/TR/pronunciation-gap-analysis-and-use-cases/#core-features-for-pronunciation-and-spoken-presentation)** of the Pronunciation Gap Analysis and Use Cases document describes requirements for pronunciation -- such as language, emphasis, and pausing.

## Exploring Technical Solutions

The Pronunciation Task Force has been exploring technical options for content authors to provide pronunciation information. A challenge is developing a solution that will be used by screen readers. One aspect of that work is analyzing how required features for accurate pronunciation are covered in existing technical specifications, including HTML5. 

**[Pronunciation Gap Analysis and Use Cases](https://www.w3.org/TR/pronunciation-gap-analysis-and-use-cases/)** provides details on the analysis. It:
- Provides more detailed context
- Describes specific implementation approaches for introducing presentation authoring markup into HTML5 (called “use cases”)
- Provides a gap analysis
- Describes how the core/required features may be met by existing approaches

## Who Develops the Pronunciation Documents

Pronunciation documents are developed by the [Pronunciation Task Force](https://www.w3.org/WAI/APA/task-forces/pronunciation/) of the [Accessible Platform Working Group (APA WG)](https://www.w3.org/WAI/APA/), which is part of the World Wide Web Consortium ([W3C](http://www.w3.org)) Web Accessibility Initiative ([WAI](http://www.w3.org/WAI/)). For more information about the Task Force, see the [Pronunciation Task Force page](https://www.w3.org/WAI/APA/task-forces/pronunciation/).

## Contributing to the Work

Opportunities for contributing to Pronunciation and other WAI work are introduced in [Participating in WAI](https://www.w3.org/WAI/about/participating/).

To get notifications of drafts for review, see [Get WAI News](https://www.w3.org/WAI/news/subscribe/) for links to WAI tweets, RSS feed, and WAI Interest Group (WAI IG) emails. An email address for sending comments on the pronunciation documents is included in the "Status of this Document" sections.

If you are interested in becoming a participant of the Pronunciation Task Force or have questions regarding its work, contact the task force facilitator [Irfan Ali](href="mailto:iali@ets.org").
