# AGENTS.md

## Purpose

This file provides instructions for AI coding agents and developers working on this repository.

The goal is to rebuild the Cambridge Family website as a production-grade codebase while preserving the current UX, design direction, copy, and navigation logic.

## Source of truth

The current Lovable-built website and repository are reference materials only.

They may be used for:
- understanding layout and visual direction
- extracting copy and content
- identifying sections and pages
- extracting assets and structure
- understanding current behavior

They must **not** be used as the architectural foundation of this project.

## Main instruction

Do not refactor the old implementation into production.

Instead:
1. analyze the old website and repo
2. identify what should be preserved at the UX/UI/content level
3. rebuild the project as a clean, maintainable, modern codebase

## Product intent

This website must feel premium, trustworthy, modern, and calm.

It is a lead-generation marketing website for a kindergarten and school in one educational space.

The homepage should:
- explain the product clearly
- preserve a unified brand experience
- offer soft routing into kindergarten or school paths
- still work well for users who are not ready to choose immediately

This is important:
- do not turn the homepage into a forced choice screen
- do not over-optimize into a spammy landing page
- do not overload pages with excessive content

## Engineering expectations

- use clean architecture
- keep components reusable and modular
- use TypeScript
- keep content manageable
- avoid monolithic page files
- keep styles consistent and scalable
- write code that is understandable for future developers
- add comments only where they help explain intent or architectural reasoning
- prefer clarity over cleverness

## Performance expectations

- optimize images properly
- avoid unnecessary JS bloat
- keep rendering efficient
- maintain good Core Web Vitals
- use accessible and semantic markup

## SEO expectations

- proper metadata
- semantic structure
- heading hierarchy
- Open Graph support
- sitemap and robots support
- localized SEO readiness if multilingual

## Forms and integrations

Architecture should support:
- lead forms
- validation
- spam protection
- analytics events
- future Supabase integration
- future email automation
- future CRM integration

## Testing expectations

Protect critical flows:
- homepage loads correctly
- navigation works
- route pages render correctly
- forms validate properly
- successful form submission flow works
- important CTAs remain functional

## Documentation expectations

If architecture or conventions are introduced, document them.

Important decisions should be easy to understand for:
- future developers
- AI agents
- product owners

## Avoid

- copying messy code from the old repo
- overengineering
- unnecessary dependencies
- unclear abstractions
- undocumented hacks
- breaking current UX intent in the name of technical purity
