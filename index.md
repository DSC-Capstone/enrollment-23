---
layout: minimal
title: Domain Descriptions
nav_exclude: true
nav_order: 1
---

{: .important }
> **This page will no longer be updated. See the [course homepage](https://dsc-capstone.org) and [Ed](https://edstem.org/us/courses/48541/discussion/) for future announcements.**

# {{ page.title }}
{: .mb-2 }
{{ site.description }}
{: .fs-6 .fw-300 }

## Overview

Welcome to the capstone program! The capstone program is a two-quarter sequence (Fall 2023 and Winter 2024) in which you will be mentored by a faculty or industry expert in their domain of expertise. By the end of Quarter 2, you will design and execute a project from that domain in teams of 2-4. You can see the projects from last year at [**dsc-capstone.org/showcase-23**](https://dsc-capstone.org/showcase-23).

At a high level, here’s how the capstone program is organized:
- In Quarter 1 (DSC 180A), you gain background information in your mentor’s domain, by means of replicating a known result. By the end of Quarter 1, you will have completed a replication project (known as the “Quarter 1 Project”) and will have a proposal for a more independent project (known as the “Quarter 2 Project”, or the capstone project).
- In Quarter 2 (DSC 180B), you execute the Quarter 2 Project you proposed at the end of Quarter 1.

You can see the syllabus for last year's capstone offering [**here**](https://dsc-capstone.org/2022-23/syllabus).

## Enrollment

The Schedule of Classes for Fall 2023 will be released on May 23rd, and first pass will begin on May 26th. The available domains are **not** listed on the Schedule of Classes; instead, they are detailed [**below**](#toc). Most domains are run by UCSD faculty, but some are run by industry partners (denoted with an <span class="badge-industry">Industry Partner</span> badge).

Use the information here to choose the domain you'd like to enroll in. Once you've chosen a domain, all you need to do is enroll in the corresponding discussion section for DSC 180A once first pass comes, space permitting. (Nothing is stopping you from waiting until second pass, but it's less likely you'll get a domain of your choice.) Note that you cannot change domains between DSC 180A and DSC 180B.

All of the information here – domain offerings, section times, descriptions, summer tasks, etc. – is subject to change as mentors provide us with more information.

### How should I choose a domain?

You should aim to choose a domain that suits your interests and preparation. By clicking the <a><b>Read more</b></a> button underneath a domain, you'll get to learn more about the mentor, their mentoring style, the prerequisites that they'd like their students to have, tasks that they'd like their students to work on over the summer, and their students' capstone projects in previous years (if any).

✅ <span style="color:#00bb00"><b>Good</b></span> reasons to choose a domain:
- You are sufficiently prepared.
- You find the topic interesting and would be motivated to study it.
- You are likely to work well with the mentor given their mentoring style and research background.

❌ <span style="color:#ff0000"><b>Bad</b></span> reasons to choose a domain:
- The mentor has good CAPE ratings.
- The industry partner is a big company.
- The section has space for you and your friends at a time that you like.

Everything you produce for the capstone will have to be public on the internet for the rest of eternity with you and your mentor's names attached to it – you want your capstone work to be something that you're proud of and can talk about on job and graduate school applications. Who do you want writing you a recommendation letter?

### What happens in DSC 180A?

In addition to meeting with your mentor each week, there will also be methodology instruction delivered by Suraj and the methodology course staff. However, the majority of this instruction will occur asynchronously, in the form of readings (like [this one](https://dsc-capstone.github.io/2022-23/lessons/q1/04/)). **This means that you can ignore the lecture and lab times that appear for DSC 180A on the Schedule of Classes.** The Monday lecture slots (3-3:50PM and 4-4:50PM) will be used for Suraj's office hours, but we don't plan to use the rest of the times.

All prerequisites for DSC 180A will be strictly enforced. The prerequisites for DSC 180A can be found [**here**](https://datascience.ucsd.edu/current-students/course-descriptions-and-prerequisites/#dsc-180a-data-science-project-1). If you took either DSC 140A, DSC 140B, or DSC 148 to satisfy the machine learning prerequisite, you will need to submit an [Enrollment Authorization System](https://academicaffairs.ucsd.edu/Modules/Students/PreAuth/) request in order to enroll in DSC 180A in fall quarter.

Note that since DSC 180A and DSC 180B are both 4-unit courses, you should expect to spend 12 hours a week on capstone-related work each quarter. Plan your class schedule accordingly – try not to take several time-consuming classes alongside the capstone.

{: .note }
**With any questions about the content of a particular domain, contact the mentor. With any questions about the capstone sequence itself, feel free to email Suraj Rampure (rampure@ucsd.edu). With any questions about enrollment, please contact Student Affairs in the VAC.**

---

Filter by subject area:

<a name='toc'>

[**💊 Medicine and Bioinformatics**](#biology)<br>
[**🤝 Causal Inference and Fairness**](#causal)<br>
[**⚙️ Distributed Systems and Other Applications**](#systems)<br>
[**🧠 Graphs and Deep Learning**](#graphs)<br>
[**🗣️ Language Models**](#language)<br>

---

<a name='biology'></a>

## 💊 Medicine and Bioinformatics

<small>(<a href="#toc">back to the outline</a>)</small>

{% assign instructors = site.staffers | where: 'tag', 'Bio' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

---

<a name='causal'></a>

## 🤝 Causal Inference and Fairness

<small>(<a href="#toc">back to the outline</a>)</small>

{% assign instructors = site.staffers | where: 'tag', 'Causal Inference and Fairness' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

---

<a name='systems'></a>

## ⚙️ Distributed Systems and Other Applications

<small>(<a href="#toc">back to the outline</a>)</small>

{% assign instructors = site.staffers | where: 'tag', 'Distributed Systems and Other Applications' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

---

<a name='graphs'></a>

## 🧠 Graphs and Deep Learning

<small>(<a href="#toc">back to the outline</a>)</small>

{% assign instructors = site.staffers | where: 'tag', 'Graphs and Deep Learning' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

---

<a name='language'></a>

## 🗣️ Language Models

<small>(<a href="#toc">back to the outline</a>)</small>

{% assign instructors = site.staffers | where: 'tag', 'Language Models' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

