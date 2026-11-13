🚀 Ultimate Web App QA & AI Coding Guide

Welcome to the master blueprint for building authentic, high-performance, and utility-driven web applications. This repository serves as a strict standard to prevent "AI slop" and ensure that AI-assisted development produces scalable, user-centric, and highly optimized code.

🤖 Part 1: The AI Coding Guide

When leveraging AI (like GitHub Copilot, ChatGPT, Claude, or Gemini) to write code, follow these principles to maintain high software quality and avoid generic, bloated outputs.

1. Context is King

Provide Architecture Upfront: Always start your prompt by defining the tech stack, database schema, and design patterns (e.g., "Use functional React components, Tailwind CSS, and strict TypeScript").

Establish the Vibe: Explicitly state what to avoid. (e.g., "Do not use purple gradients, pill buttons, or vague marketing copy. Optimize for a clean, utilitarian UI.")

2. Iterative Generation

Component-Driven Prompting: Do not ask the AI to "build an entire website." Ask it to build the Navbar, then the Hero, then the Form.

Single Responsibility: Ensure the AI keeps functions and files small. If a component grows beyond 150 lines, ask the AI to refactor and modularize it.

3. Strict Guardrails

Enforce Typing: Always mandate strict type definitions (TypeScript) or schemas (Zod/Joi) to prevent hallucinated variables and runtime errors.

Mandate Tests: Ask the AI to generate unit tests (Jest/Vitest) alongside the component code.

No Placeholder Slop: Tell the AI to use realistic, domain-specific placeholder data instead of generic "Lorem Ipsum" or robotic "Welcome to the future of AI" copy.

4. Human-in-the-Loop Review (The "Trust, but Verify" Rule)

Never Blind Copy-Paste: Review every line for business logic accuracy and potential security flaws (like exposed API keys or unescaped inputs).

Check Accessibility: AI often forgets ARIA labels, focus states, and semantic HTML. Verify these against the QA checklist below.

✅ Part 2: The Ultimate QA Checklist

Use this interactive checklist for every pull request or deployment.

🚫 Strict Exclusions (The Anti-Slop List)

[ ] No purple gradients or pill-shaped buttons

[ ] No fake reviews, customer counters, or fake metrics

[ ] No AI slop copy, AI photos, or vague hero text

[ ] No emoji icons, em dashes, or "made with AI" tags

[ ] No crazy scroll or custom cursor animations

🏗️ Core Architecture & SEO

[ ] Custom domain connected

[ ] Meta Title and Meta Description unique per page

[ ] Open Graph tags and images configured for link previews

[ ] Favicon set uploaded (SVG + ICO fallbacks)

[ ] robots.txt and XML Sitemap generated and accessible

[ ] Google Search Console and Bing Webmaster Tools setup

[ ] llms.txt file added for clean AI crawler compatibility

[ ] Schema Markup (JSON-LD) implemented (e.g., Organization, FAQ)

[ ] UTM tracking configured for external campaigns

[ ] Analytics tracking installed and firing correctly

🧭 UI/UX & Navigation

[ ] Dark mode toggle (with OS-level preference detection)

[ ] Sticky headers and functional Mobile Menu

[ ] Search functionality (if applicable)

[ ] Scroll progress bar and "Back to top" button

[ ] Expandable FAQ section (using <details> and <summary>)

[ ] Print style sheet (@media print) configured

[ ] Mobile breakpoints tested and Sticky Mobile CTA functional

[ ] Primary CTA placed clearly above the fold

[ ] Custom, helpful 404 error page

📝 Forms & Interactive States

[ ] Loading animations, buffering screens, and clear hover states

[ ] Form success and error states clearly defined with feedback

[ ] Password visibility toggle (eye icon)

[ ] "Copy to clipboard" buttons for code snippets, links, or keys

[ ] Confirmation modals for destructive actions (e.g., Delete Account)

[ ] Dedicated Thank-you page post-submission for tracking

⚖️ Legal, Trust & Security

[ ] Privacy Policy and Terms & Conditions pages accessible

[ ] Simple, non-intrusive Cookie banner implemented

[ ] "Last updated" date visible on content and legal pages

[ ] Real contact address and information listed

[ ] Strict HTTPS/HSTS enforced across the domain

[ ] Content Security Policy (CSP) headers properly set

⚡ Performance & Accessibility (a11y)

[ ] WebP or AVIF next-gen image formats used for all media

[ ] Meaningful alt text applied to every image

[ ] Lazy loading (loading="lazy") enabled for below-the-fold media

[ ] "Skip to content" link active for keyboard navigation

[ ] aria-labels and roles added to toggles and interactive elements

[ ] Semantic HTML5 structure (<main>, <nav>, <section>) applied

[ ] Web App Manifest (manifest.json) and basic Service Worker included
