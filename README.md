# or-checklist

OR Room Setup Prompt Generator

This repository contains a lightweight browser-based tool to generate structured anesthesia room setup prompts for large language models.

The tool standardizes scenario inputs (procedure type, ASA physical status, anesthetic type) and assembles them into a formatted prompt that can be launched directly in Google Gemini.

It was developed to support a research study evaluating AI-generated operating room setup checklists.

Live Tool

The prompt generator is available here:

https://alfredocr05.github.io/or-checklist/

What This Does

Collects abstracted case attributes (no patient identifiers)

Builds a structured prompt for anesthesia room preparation

Allows one-click launch into Google Gemini (v3.0 Pro)

Produces checklist-style outputs for research evaluation

This is a prototype research interface and is not integrated with any electronic health record.

Privacy

No protected health information (PHI) is used or stored.
All inputs are hypothetical or abstracted scenario variables.

Technology

Single-page HTML interface with embedded JavaScript

Runs entirely client-side in the browser

No server backend

No data persistence

AI Attribution

The interface and prompt scaffolding were developed with assistance from generative AI (Claude Opus 4.6).
Prompts in the associated manuscript were executed using Google Gemini v3.0 Pro.

Intended Use

Research and educational purposes only.
