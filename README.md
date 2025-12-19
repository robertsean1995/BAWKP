![BAWK Programming Logo](/images/BAWK_Logo.png)

<div align="center">
  <a href="https://www.linkedin.com/in/robertsean1995/"><img align="middle" src="https://img.shields.io/badge/LinkedIn-%230A66C2.svg?style=for-the-badge&logo=linkedin&logoColor=white"></a>
&nbsp;
  <a href="mailto:robertsean1995@gmail.com"><img align="middle" src="https://img.shields.io/badge/Email-%23EA4335.svg?style=for-the-badge&logo=gmail&logoColor=white"></a>
</div>

<hr>

**BAWK Programming ("b/awk/p" or "BAWKP") is an unconventional programming methodology that's based on compositional language-oriented programming. It treats Bash as a general-purpose programming language with object-oriented elements, while composing AWK as a dedicated data-processing language responsible for pattern matching, transformation, field processing, aggregation, and domain-specific logic. The name "BAWK" is derived from a combination of Bash and AWK. The logo is made to resemble a regular expression in the same style as GREP ("g/re/p"), and the chickens are a lighthearted reference to the onomatopoeia of the same name.**
- Formalizes Bash and AWK as a unified programming environment.
- Enforces strict separation of duties between control flow and computation.
- Replaces fragile shell pipelines with structured, responsibility-driven design.
- Scales Bash scripts through discipline, readability, and predictable data flow.
- Minimizes unnecessary language and runtime dependencies while embracing Unix tools.
- Prioritizes predictable behavior, operational safety, and survivability.
- Designed explicitly for practical automation and offensive security.

<hr>

# Table of Contents
- [Introduction and Methodology](#introduction-and-methodology)
  - [Mental Model](#mental-model)
- [General-Purpose Programming with BAWK](#general-purpose-programming-with-bawk)
- [Object Orientation with BAWK](#object-orientation-with-bawk)
- [Separation of Duties](#separation-of-duties)
- [Readability and Survival](#readability-and-survival)
- [Structure, Syntax, and Semantics](#structure-syntax-and-semantics)
  - [Discipline as a Consequence](#discipline-as-a-consequence)
  - [Structure and Formatting](#structure-and-formatting)
  - [Efficiency as a Design Constraint](#efficiency-as-a-design-constraint)
  - [Antipatterns and Hard Rules](#antipatterns-and-hard-rules)
- [Conclusion](#conclusion)

<hr>

# Introduction and Methodology

BAWK Programming (“b/awk/p” or “BAWKP”) is a deliberate methodology for writing shell automation that treats Bash and AWK as a single, unified programming environment rather than two loosely connected tools in an ad-hoc pipeline. It is not a new language, a framework, or a “better Bash,” but a set of explicit boundaries and constraints designed to turn common shell scripting practices into something closer to an engineered system. Although most people already use Bash and AWK together, they typically do so informally—chaining commands until the output “looks right,” growing one-liners into fragile pipelines, and letting logic drift into whichever tool happens to be most convenient. BAWK makes this implicit practice explicit by enforcing a clear separation of duties: Bash owns orchestration, state, and control flow, while AWK owns pattern matching, transformation, field semantics, and aggregation. This division is not aesthetic but protective; Bash becomes fragile and error-prone when burdened with heavy text computation, and AWK becomes opaque when pressed into acting like a shell. By formalizing what each tool is responsible for, BAWK produces scripts that remain readable under pressure, predictable in behavior, and resilient as they grow—qualities that are especially critical in the messy, hostile environments common to offensive security and incident response.

BAWK can be understood as a pragmatic, compositional form of language-oriented programming, not because it invents new syntax, but because it treats Bash and AWK as distinct languages with clearly defined roles and composes them intentionally rather than opportunistically. Bash is not being stretched into other languages, and AWK is not being pressed into service as a general parser; each is used where it is strongest, and the programming model emerges from the contract between them. However, this methodology reserves the opportunity of incorporating other languages (i.e. Python) when specific contexts extend beyond BAWK's natural limits. This perspective naturally leads to the “BAWK first, Python second” rule, which is not an anti-Python stance but a forcing function for clarity. Many tasks that are routinely escalated to Python—line-oriented parsing, field extraction, text transformation, and aggregation—are precisely what AWK already does efficiently and transparently. When BAWK hands off to another language, that decision should be driven by a genuine mismatch in problem shape, such as structured parsing, complex stateful logic, nontrivial protocols, or rich user interfaces, and that handoff should remain minimal and explicit. The result is an approach that scales from quick automation to substantial tooling without collapsing into a brittle tangle of pipes and one-liners.

## Mental Model

<br>

# General-Purpose Programming with BAWK

<br>

# Object Orientation with BAWK

<br>

# Separation of Duties

<br>

# Readability and Survival

<br>

# Structure, Syntax, and Semantics

<br>

## Discipline as a Consequence

<br>

## Structure and Formatting

<br>

## Efficiency as a Design Constraint

<br>

## Antipatterns and Hard Rules

<br>

# Conclusion

<br>
