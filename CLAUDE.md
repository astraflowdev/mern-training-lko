# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a MERN Stack training repository organized by days, currently through Day 5. The repository follows a progressive learning structure where each day builds upon fundamental web development concepts.

## Repository Structure

The codebase is organized into day-by-day folders:
- `Day1-HTML/` - HTML fundamentals (elements, lists, forms)
- `Day4-CSS/` - CSS basics (selectors, inline/internal/external styles, specificity)
- `Day5-CSS2/` - Advanced CSS (display properties, floats, backgrounds, gradients)
- `Day6-CSS-LAYOUTS-POSITIONS/` - CSS layouts and positioning (in progress)

Each day folder typically contains:
- `index.html` - Main HTML file for that day's lesson
- `style.css` - External stylesheet (when applicable)
- Additional assets (e.g., images like `bg.jpeg`)

## Development Workflow

Since this is a static HTML/CSS training project with no build system:

**Viewing files:**
- Open HTML files directly in a browser
- No server or build process required

**File structure:**
- Each day is self-contained
- External stylesheets are linked using `<link rel="stylesheet" href="style.css">`
- Some examples demonstrate inline styles and `<style>` tags for teaching purposes

## Key Concepts Covered

**Day 1 - HTML:**
- Basic HTML structure
- Headings (h1-h6), paragraphs, horizontal rules
- Lists (ordered and unordered)
- Forms with various input types (text, textarea, radio, datetime-local)

**Day 4 - CSS:**
- CSS specificity: inline styles > internal styles > external styles
- Selector types: element selectors, class selectors (`.class`), ID selectors (`#id`)
- CSS cascade demonstration (multiple style definitions for same elements)

**Day 5 - CSS Advanced:**
- Display properties (`inline`, `block`)
- Float-based layouts (`float: left`, `float: right`)
- Background properties (colors, images, gradients)
- Linear gradients with multiple color stops

## CSS Specificity Order

When working with styles in this codebase, remember the cascade:
1. Inline styles (highest priority)
2. Internal styles (`<style>` tag)
3. External styles (`style.css`)
4. ID selectors override class selectors
5. Class selectors override element selectors

## Notes for Future Development

- This is a training repository, so code may intentionally show multiple approaches (inline, internal, external CSS) for educational purposes
- When adding new days, follow the existing naming convention: `DayX-TOPIC/`
- Keep each day's examples simple and focused on the specific concepts being taught
- Avoid introducing build tools or frameworks unless the training progresses to those topics
