# SIMATIC AX - APAX and Project Creation

## Description
A focused learning path for automation engineers who want to understand APAX fundamentals and practical SIMATIC AX project creation workflows.

## Overview

This repository contains a complete training module that introduces APAX concepts, package and dependency handling, and core project lifecycle steps in SIMATIC AX. The content is delivered as an interactive slide deck for self-learning and team enablement.

## Getting Started

You can view the interactive training presentation here:

Latest:
[Open Presentation](https://simatic-ax.github.io/axlp_apax_and_project_creation/latest/#/)

Select older versions:
[Select Version](https://simatic-ax.github.io/axlp_apax_and_project_creation/#/)

## Learning Objectives

After completing this training, participants will be able to:

- **Understand:** Explain the role of APAX in the SIMATIC AX ecosystem
- **Create:** Initialize and structure SIMATIC AX projects with APAX
- **Manage:** Handle package references and dependency versions
- **Build:** Execute build and validation workflows for AX projects
- **Apply:** Use practical project setup patterns in daily engineering work

## Prerequisites

### Essential Requirements
- Basic SIMATIC AX development environment knowledge
- Industrial automation and PLC programming background
- Installed Node.js and npm for local presentation rendering

### Recommended Preparation
- Complete SIMATIC AX Getting Started tutorials
- Familiarize yourself with command-line based project workflows

## Repository Structure

```text
axlp_apax_and_project_creation/
├── slides.md                  # Main training presentation
├── theme/
│   └── simatic-ax.css         # Custom presentation theme
├── img/                       # Images and visual assets
├── apax.yml                   # APAX project metadata
├── CODEOWNERS                 # Ownership and review rules
├── LICENSE.md                 # License and legal information
└── renovate.json              # Dependency update configuration
```

## Training Modules

### Chapter 1: APAX Fundamentals
- Why APAX matters in SIMATIC AX projects
- Package-based development principles
- Typical project lifecycle overview

### Chapter 2: Project Creation Workflow
- Creating a new AX project
- Understanding project file structure
- Initial configuration best practices

### Chapter 3: Package and Dependency Management
- Adding and maintaining dependencies
- Versioning basics and update strategies
- Working with package metadata

### Chapter 4: Build and Validation
- Local build workflow
- Common validation steps
- Troubleshooting typical setup issues

## Local Presentation Usage

To view the training locally, install `reveal-md` first:

```sh
npm install -g reveal-md
```

Run the presentation in watch mode:

```sh
reveal-md slides.md --watch --theme theme/simatic-ax.css -css theme/simatic-ax.css
```

Generate a static version for GitHub Pages:

```sh
reveal-md slides.md --static docs --theme theme/simatic-ax.css -css theme/simatic-ax.css --assets-dir dist --staticDirs img
```

## Additional Resources

- [SIMATIC AX Documentation](https://console.simatic-ax.siemens.io/docs)
- [APAX Reference](https://console.simatic-ax.siemens.io/docs/apax)
- [SIMATIC AX Getting Started](https://console.simatic-ax.siemens.io/docs/getting-started)

## Contribution

Thanks for your interest in contributing. Anybody is free to report bugs, unclear documentation, and other problems regarding this repository in the Issues section or, even better, is free to propose any changes to this repository using Merge Requests.

## License

See [LICENSE.md](./LICENSE.md) for license and legal information.