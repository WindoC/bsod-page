# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a static HTML demonstration project showcasing different AI models' attempts at recreating a Windows Blue Screen of Death (BSOD) webpage from an image. The project serves as a comparison study of AI web generation capabilities.

## File Structure

- `index.html` - Main page with navigation menu and iframe display system
- `10-error-windows-10-windows-blue-humor.jpg` - Original BSOD image reference
- `BSOD_*.html` - Individual AI-generated BSOD recreations:
  - `BSOD_claudesonnet4.html` - Claude Sonnet 4's implementation
  - `BSOD_claudecodesonnet4.html` - Claude Code's implementation  
  - `BSOD_gemini25flash.html` - Gemini 2.5 Flash's implementation
  - `BSOD_gemini25pro.html` - Gemini 2.5 Pro's implementation
  - `BSOD_openaigpt5.html` - OpenAI GPT-5's implementation

## Architecture

The main `index.html` uses a simple architecture:
- Container system that switches between image display and iframe content
- Hidden menu system in bottom right corner with hover expansion
- localStorage for persistence of user's last selected page
- CSS-only responsive design with no external dependencies

## Development Notes

- This is a static HTML project with no build system, package manager, or testing framework
- All styling is embedded CSS within individual HTML files
- JavaScript functionality is vanilla JS with no external libraries
- Files should maintain their original implementations as comparison artifacts
- The `index.html` serves as the navigation hub and should not modify the individual BSOD pages

## File Modification Guidelines

- Individual `BSOD_*.html` files should generally not be modified as they represent specific AI model outputs for comparison
- The `index.html` can be enhanced for navigation, styling, or additional functionality
- When adding new AI model results, follow the naming pattern `BSOD_[modelname].html` and update the menu in `index.html`