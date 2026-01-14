# CLAUDE.MD

## Project Overview

This is a **GitHub Skills** course repository for learning how to code with **GitHub Copilot**. The repository provides hands-on exercises and tutorials to help developers leverage AI-powered code suggestions using GitHub Copilot with VS Code and GitHub Codespaces.

## Repository Purpose

This repository serves as an interactive learning course that teaches users how to:
- Set up and use GitHub Copilot in VS Code and Codespaces
- Leverage AI pair programming capabilities
- Work with development containers (`.devcontainer`)
- Understand Copilot's autocomplete and code suggestion features

## Key Components

### Documentation
- **README.md**: Main course instructions and step-by-step activities
- **LICENSE**: MIT License for the project

### GitHub Configuration
- **`.github/workflows/`**: Automated GitHub Actions workflows for course progression
  - `0-welcome.yml`: Initial welcome workflow
  - `1-copilot-extension.yml`: Copilot extension setup workflow
  - `2-skills-javascript.yml`: JavaScript skills workflow
  - `3-copilot-hub.yml`: Copilot Hub workflow
  - `4-copilot-comment.yml`: Copilot comment workflow

- **`.github/steps/`**: Step-by-step course content markdown files
  - `-step.txt`: Current step tracker
  - Individual step files (0-4 plus X-finish.md)

- **`.github/dependabot.yml`**: Dependabot configuration for dependency updates

### Development Environment
- **`.devcontainer/`**: Development container configuration (to be created during exercises)
- **`.gitignore`**: Git ignore patterns

## Course Structure

The course is organized into sequential steps:
1. **Step 0**: Welcome and introduction
2. **Step 1**: Leverage Codespaces with VS Code for Copilot
3. **Step 2**: JavaScript skills practice
4. **Step 3**: Copilot Hub integration
5. **Step 4**: Using Copilot with comments
6. **Step X**: Completion

## Technology Stack

- **AI Tool**: GitHub Copilot (powered by OpenAI Codex)
- **Editor**: VS Code / Visual Studio / JetBrains IDE / Neovim
- **Platform**: GitHub Codespaces
- **Languages**: Multi-language support (focus on languages in public repositories)

## Current Status

- Repository is set up as a GitHub Skills course
- Step 1 is currently active (as indicated by the step tracker)
- Users should follow the README.md instructions sequentially

## Notes for Claude

When working with this repository:
- This is an educational/tutorial repository, not production code
- Changes should preserve the instructional nature of the content
- The `.github/steps/` directory contains course progression logic
- Workflows automatically progress users through the course
- The repository demonstrates Copilot setup rather than being a typical software project
