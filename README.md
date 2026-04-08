# Cambridge Family Web

Production-grade marketing website for Cambridge Family — a kindergarten and school in one educational space.

## Project goal

This repository is for rebuilding the current Cambridge Family website as a clean, scalable, production-ready web product.

The current Lovable-built website is used only as a **reference for design, content, structure, and navigation**.

This new repository is intended to become the main codebase for long-term development, deployment, integrations, analytics, SEO, and future scaling.

## Core objective

Preserve the current strengths of the website:
- visual direction
- page structure
- storytelling logic
- navigation
- copywriting
- lead generation flow

But rebuild everything on a professional engineering foundation:
- clean architecture
- maintainable code
- scalable frontend
- high performance
- SEO readiness
- analytics readiness
- testing
- documentation
- safe future integrations

## Important rule

The old Lovable repository must **not** be treated as the production foundation.

It may be used only as:
- a visual reference
- a content source
- a structure reference
- an asset source
- a behavior reference

The new codebase should be built as a fresh implementation.

## Product type

This is not just a static brochure website.

This project should function as a **production-ready lead generation platform** with:
- strong UX
- clear user journeys
- maintainable content structure
- integration-ready forms
- analytics event tracking
- SEO optimization
- future backend support via Supabase and other services

## Key principles

- Keep the existing strong UX and visual direction
- Do not overcomplicate the interface
- Preserve a clean and elegant premium feel
- Optimize for conversion without turning the website into an aggressive landing page
- Support both user types:
  - parents who already know they need kindergarten or school
  - parents who want to understand the product first
- Keep the homepage as a soft-routing experience, not a forced-choice flow

## Planned stack

Preferred stack:
- Next.js
- TypeScript
- Tailwind CSS
- component-based architecture
- Supabase
- analytics integrations
- SEO-first implementation
- production deployment workflow

The final stack may be refined, but maintainability, performance, and long-term scalability are mandatory.

## Main requirements

### Engineering
- clean project structure
- reusable components
- type safety
- documented codebase
- safe environment configuration
- clear separation of UI, content, forms, integrations, and utilities

### Performance
- optimized image loading
- responsive images
- proper lazy loading
- efficient bundle size
- good Core Web Vitals
- fast page rendering

### SEO
- semantic HTML
- clean heading structure
- metadata
- Open Graph
- sitemap
- robots.txt
- schema markup where appropriate
- localized SEO support if multilingual

### Forms and lead generation
- robust lead forms
- validation
- spam protection
- clear success/error states
- integration-ready architecture
- future support for Supabase, email flows, CRM, and automation

### Analytics
- event tracking for:
  - CTA clicks
  - navigation interactions
  - route selection
  - form starts
  - form submissions
  - contact interactions

### Testing
- basic automated testing for critical flows
- stable deployment process
- safe future refactors

## Documentation files

This repository includes several markdown files that define product, technical, content, SEO, and QA expectations.

Read these first before making architectural or product decisions:
- `PROJECT_BRIEF.md`
- `TECH_REQUIREMENTS.md`
- `SEO_REQUIREMENTS.md`
- `CONTENT_STRUCTURE.md`
- `TESTING_CHECKLIST.md`
- `AGENTS.md`

## Current status

Status: planning / project initialization

Next steps:
1. define architecture expectations
2. define content and page structure
3. define technical requirements
4. rebuild the website as a new implementation
5. connect integrations and production workflows

## Notes for developers and AI coding agents

When working on this project:
- do not blindly copy old Lovable code
- preserve the current UX logic and content intent
- prioritize maintainability over quick hacks
- document non-obvious architectural decisions
- avoid unnecessary complexity
- treat this as a real production project, not a prototype
