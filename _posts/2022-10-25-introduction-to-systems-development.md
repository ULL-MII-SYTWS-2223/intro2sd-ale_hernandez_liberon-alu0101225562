---
title: "System Development"
excerpt_separator: "<!--more-->"
categories:
  - Post Formats
tags:
  - Post Formats
  - readability
  - standard
---

## What is System Development?

Systems development is the process of taking a set of business requirements and, through a series of structured stages, translating these into an operational IT system.

- a feasibility study, to see if the project is worthwhile
- requirements engineering to analyse the business need and specify the user requirements
- design of the system to meet the users’ needs
- development of the software needed to meet the requirements
- testing of the software
- implementation of the solution

## System development and other disciplines

<ul>
{% for discipline in site.data.disciplines %}
  <li>
    <h3>{{ discipline.title }}</h3>
    <p>{{ discipline.content }}</p>
  </li>
{% endfor %}
</ul>

## Offshoring and outsourcing of system development

| Type | Description | Downsides |
|------|-------------|-----------|
|Offshoring||Offshoring involves using development resources in other countries, usually because high-quality resources can be secured for considerably less cost than in the organisation’s home country|There can be delays and communication difficulties associated with working with developers who are a long way away|
|Outsourcing||Outsourcing means handing over the development work to specialist IT services firms and consultancies|One of the chief dangers here is that the customer organisation loses direct control of systems that are critical to its business objectives.|