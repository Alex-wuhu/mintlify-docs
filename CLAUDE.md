# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a Mintlify documentation site for "Alex personal docs". The documentation is written in MDX format with YAML frontmatter and is configured using a `docs.json` file.

## Development Commands

- Install the Mintlify CLI globally: `npm i -g mint`
- Run the development server: `mint dev` (run at the root where `docs.json` is located)
- Preview the documentation locally at: `http://localhost:3000`
- Update the Mintlify CLI to the latest version: `mint update`

## Codebase Structure

- `docs.json`: Main configuration file for the documentation site, including navigation, theme, colors, and other settings
- `*.mdx`: Documentation pages written in MDX format with YAML frontmatter
- `rules/`: Directory containing guidelines for documentation, including specific instructions for AI tools
- `api-reference/`: API documentation pages
- `Languages/`: Language-specific documentation (e.g., Solidity)
- `images/`: Image assets used in the documentation
- `logo/`: Logo assets for light and dark modes

## Architecture Notes

- The site uses Mintlify's documentation platform with a tab-based navigation structure
- Two main tabs: "Guides" and "API reference"
- The `docs.json` file controls the navigation structure, theme colors, logos, and other site-wide settings
- Pages are written in MDX format, allowing for both Markdown content and React components
- The site supports both light and dark themes with corresponding logo assets

## AI Tool Rules

According to `rules/ai-tools/claude-code.mdx`, when working with this documentation:

- Document just enough for user success
- Prioritize accuracy and usability of information
- Make content evergreen when possible
- Check existing patterns for consistency
- Use second-person voice ("you")
- Include prerequisites at the start of procedural content
- Test all code examples before publishing
- Use language tags on all code blocks
- Use relative paths for internal links
- Never use absolute URLs for internal links
- Never include untested code examples