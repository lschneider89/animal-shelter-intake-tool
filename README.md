# Shelter Long-Stay Screening vPrototype - Animal Shelter Intake Screening Tool 2026

> **Shelter Long-Stay Screening is a browser-based intake application that uses dedicated dog and cat classification models to flag animals expected to stay in shelter care for more than 30 days.**

[![Platform](https://img.shields.io/badge/Platform-Web%20browser-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-Prototype-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/lschneider89/animal-shelter-intake-tool?style=flat-square)](https://github.com/lschneider89/animal-shelter-intake-tool)

---

<p align="center">
  <a href="https://lschneider89.github.io/animal-shelter-intake-tool/">
    <img src="https://img.shields.io/badge/Download-Shelter%20Long--Stay%20Screening%20Latest-brightgreen?style=for-the-badge" alt="Download Shelter Long-Stay Screening">
  </a>
</p>

> **[Download Shelter Long-Stay Screening Prototype](https://lschneider89.github.io/animal-shelter-intake-tool/)**

---

[Download Latest Build](https://lschneider89.github.io/animal-shelter-intake-tool/)

---

## Overview

Shelter Long-Stay Screening is an interactive HTML prototype built for animal shelter intake review. It combines an intake queue, an individual animal detail view, and in-browser scoring to estimate whether a dog or cat is likely to stay in care beyond 30 days.

The application is intended to help shelter teams examine incoming records and spot cases that could warrant earlier follow-up. Because the trained classification model is packaged inside the page, the prototype runs without a server, installed dependencies, or a separate compilation workflow.

---

## What It Includes

- Estimates which animals may remain in shelter care longer than 30 days
- Applies separate prediction models to dogs and cats
- Offers a browsable queue of intake records
- Displays detailed information for a selected animal
- Evaluates newly entered intake data within the browser
- Presents the seven intake features used by the screening process
- Packages a gradient-boosted tree model directly in the application
- Helps staff prioritize earlier review and intervention planning

---

## Getting Started

### Download the Prototype

Get the current prototype from the hosted project build:

[Download Shelter Long-Stay Screening](https://lschneider89.github.io/animal-shelter-intake-tool/)

### Get the Source

```bash
git clone https://github.com/lschneider89/animal-shelter-intake-tool.git
cd REPO
```

### Open the Application

Load the HTML prototype entry file in a modern web browser. The application does not need a server, package installation, or build step.

---

## Using the Tool

1. Load the prototype in a web browser.
2. Browse the available animals in the intake queue.
3. Choose an animal to display its detail panel.
4. Examine the seven intake features shown for that record.
5. Read the selected animal's long-stay prediction.
6. Create or modify an intake record when the interface provides that option.
7. Use the classification as an input for earlier staff review.

Dog records and cat records are scored with their respective embedded models.

---

## Configuration and Model Data

No backend service or standalone configuration file is needed. The HTML application contains the trained classification models, while all scoring is performed locally in the browser.

To change the interface or model behavior, edit the applicable embedded data and application logic in the HTML prototype. Reopen the file in a browser after making those changes.

---

## Requirements

- A modern web browser with JavaScript enabled
- Either a local HTML prototype or access to the hosted build
- No server runtime
- No external database
- No build toolchain
- Enough browser storage for normal page operation

---

## Frequently Asked Questions

### Is a server needed to run the prototype?

No. Scoring is handled in the browser, so the prototype does not depend on a server or application runtime.

### Does the same model score dogs and cats?

No. The prototype includes one classification model for dogs and another for cats.

### What does a long-stay prediction mean?

It indicates that the animal is predicted to remain in shelter care for more than 30 days using the intake information supplied to the model.

### Where does the prototype save its settings?

It has no separate settings store. The application behavior and model are contained in the HTML application itself.

### How can I get a newer version?

Follow the latest build link near the beginning of this README, or review the repository for subsequent revisions.

### What should I do if a record is not scored?

First ensure that JavaScript is enabled, then reload the HTML file and confirm that the full prototype was downloaded. If the problem remains, compare the local file with the latest repository build.

### Is this intended to replace staff decisions?

No. The results are designed to assist intake review and prioritization. Shelter staff should evaluate the output alongside their operational context and policies.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
