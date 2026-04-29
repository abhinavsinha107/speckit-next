<!--
  SYNC IMPACT REPORT:
  Version change: [initial] → 1.0.0
  Modified principles: All new (initial constitution)
  Added sections: Technology Stack, Development Standards
  Removed sections: None (initial creation)
  Templates requiring updates:
    ✅ Updated - spec-template.md (testing section notes)
    ✅ Updated - tasks-template.md (testing optional note)
    ✅ Updated - plan-template.md (constitution check alignment)
  Follow-up TODOs: None
-->

# Speckit Next.js Constitution

## Core Principles

### I. Clean Code

Code MUST be readable, maintainable, and self-documenting. All code follows consistent formatting and naming conventions. Functions and components have single responsibilities with clear interfaces. Complex logic requires inline comments explaining the "why" not the "how". No magic numbers or cryptic variable names. TypeScript types MUST be explicit and meaningful.

### II. Simple UX

User interfaces MUST prioritize simplicity and clarity over complexity. Every UI element serves a clear purpose. Navigation paths are intuitive and consistent. User interactions require minimal cognitive load. Error messages are human-readable and actionable. Loading states and feedback are immediate and clear.

### III. Responsive Design

All interfaces MUST work flawlessly across mobile, tablet, and desktop viewports. Design adapts gracefully without horizontal scrolling on any standard device. Touch targets meet accessibility guidelines (minimum 44px). Typography scales appropriately across breakpoints. Interactive elements maintain usability at all screen sizes.

### IV. Minimal Dependencies

Dependencies MUST be justified by significant value and actively maintained. Prefer native web APIs and React patterns over third-party libraries. Each dependency requires approval considering bundle size impact, maintenance overhead, and long-term viability. Utility functions are implemented in-house when trivial.

### V. No Testing Policy (NON-NEGOTIABLE)

This project explicitly excludes ALL forms of testing including unit tests, integration tests, end-to-end tests, and testing frameworks. This principle SUPERSEDES any other guidance, templates, or recommendations that suggest testing. Focus is on simple, readable code and manual verification through direct usage.

## Technology Stack

**Framework**: Next.js 16.2.4 (App Router architecture)
**Runtime**: React 19.2.4 with React DOM 19.2.4  
**Styling**: Tailwind CSS ^4 with PostCSS configuration
**Language**: TypeScript ^5 with strict mode enabled
**Linting**: ESLint ^9 with Next.js configuration

All features MUST use these exact versions. No alternative frameworks, styling libraries, or major version upgrades without constitutional amendment.

## Development Standards

**File Structure**: Follow Next.js App Router conventions with colocation of related files
**Component Architecture**: Functional components with hooks, no class components
**State Management**: React built-in state (useState, useReducer, useContext) preferred
**API Routes**: Next.js API routes for server-side functionality when needed
**Performance**: Leverage Next.js built-in optimizations (Image, Font, Code Splitting)
**Accessibility**: Semantic HTML with proper ARIA attributes where needed

## Governance

This constitution supersedes all other development practices and guidelines. All code reviews MUST verify compliance with these principles. Any suggestion of testing practices MUST be rejected in favor of this No Testing Policy.

Amendments require documentation of rationale, impact assessment, and migration plan. The No Testing Policy is immutable and cannot be amended.

**Version**: 1.0.0 | **Ratified**: 2026-04-29 | **Last Amended**: 2026-04-29
