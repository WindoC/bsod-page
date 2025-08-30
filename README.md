# BSOD AI Comparison Project

A demonstration project comparing different AI models' ability to recreate a Windows Blue Screen of Death (BSOD) webpage from an image.

## Overview

This project showcases how various AI models interpret and implement a web recreation of the classic Windows BSOD error screen. Each AI model was given the same source image and asked to create an HTML representation.

## Live Demo

Open `index.html` in your browser to view:
- The original BSOD image
- Interactive comparison of different AI implementations
- Hidden menu in bottom-right corner for easy switching between versions

## AI Models Compared

- **Claude Sonnet 4** - Anthropic's latest model
- **Claude Code** - Anthropic's coding-specialized model  
- **Gemini 2.5 Flash** - Google's fast model
- **Gemini 2.5 Pro** - Google's advanced model
- **OpenAI GPT-5** - OpenAI's latest model

## Key Features

- **Responsive Design** - All implementations adapt to different screen sizes
- **Authentic Styling** - Each AI's interpretation of Windows BSOD aesthetics
- **Interactive Navigation** - Easy switching between different versions
- **Persistent Selection** - Remembers your last viewed page

## Results Summary

Based on this simple web generation task, OpenAI demonstrates the strongest performance in accurately recreating the BSOD appearance and functionality.

## Usage

1. Open `index.html` in any modern web browser
2. Hover over the small square in the bottom-right corner to reveal the menu
3. Select different AI implementations to compare their approaches
4. Your selection will be remembered for future visits

## Technical Notes

- Pure HTML/CSS/JavaScript implementation
- No external dependencies or build process required
- Uses localStorage for preference persistence
- Iframe-based content switching for seamless navigation