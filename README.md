# BrightSAT Case Study

BrightSAT is a private full-stack SAT preparation platform. This public case study summarizes the product, architecture, and engineering work without exposing private source code, secrets, or proprietary content.

## Portfolio Summary

- Built a full-stack SAT practice platform with realistic test-taking routes, targeted practice blocks, completed-test persistence, and learner dashboard workflows.
- Used Next.js, React, TypeScript, Prisma, Supabase, Tailwind CSS, React Query, and Stripe-ready application infrastructure.
- Demonstrated production-style app architecture by connecting JSON-backed SAT content, API routes, auth-aware dashboards, test attempts, and math-practice tooling.

## Problem

Most SAT practice demos look like static question banks. BrightSAT was built around realistic learner workflows: start a practice test, work through module-style questions, use math tools, submit an attempt, and review completed-test history.

## What I Built

- Practice-test routes for SAT-style learning flows.
- Targeted practice blocks for focused Reading/Writing and Math review.
- Completed Tests persistence for finished attempts.
- JSON-backed SAT content and validation scripts.
- Auth-aware learner dashboard surfaces.
- API routes for attempts and content access.
- Calculator/highlighting behavior for math and reading workflows.
- Database-backed app structure with Prisma and Supabase.

## Tech Stack

- Next.js 15
- React 19
- TypeScript
- Prisma
- Supabase
- Tailwind CSS
- React Query
- Zod
- Recharts
- Stripe-ready backend integration

## Architecture Snapshot

```text
Learner UI
-> Next.js routes and React components
-> API routes / server logic
-> Prisma data models
-> Supabase database/auth layer
-> JSON-backed SAT content and validation scripts
```

## Screenshots To Add

Add sanitized screenshots before publishing this as a polished portfolio project:

- Learner dashboard.
- Practice-test page.
- Targeted practice flow.
- Completed Tests history.
- SAT math screen with calculator/tooling visible.

## Privacy Note

The production repository should stay private if it contains secrets, paid-product logic, unfinished infrastructure, or licensed/proprietary SAT content. This public case study should show architecture, product thinking, screenshots, and technical decisions without exposing private implementation details.
