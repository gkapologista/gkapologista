# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Purpose

This is a documentation-only GitHub profile repository. The sole file is `README.md`, which renders as the public-facing portfolio summary on the GitHub profile page (https://github.com/gkapologista).

There are no build, lint, or test processes — no package.json, Makefile, or CI configuration exists.

## Working with This Repository

All changes are documentation edits to `README.md`. Commit messages predominantly follow the `docs:` prefix convention (e.g., `docs: update professional title`).

The README renders tech-stack badges and activity stats via external image services — `skillicons.dev`, `img.shields.io`, and `streak-stats.vercel.app`. These are the most fragile part of the file: icons break when a slug is wrong or a service changes, and much of the commit history is fixes to them. When editing badges, verify each icon slug against the service's supported list and check that images resolve in the rendered GitHub preview.

## Portfolio Context

The README showcases a Senior Full Stack Engineer specializing in:
- Frontend architecture with Vue.js, React, TypeScript, and Quasar Framework
- Backend development with Node.js/Express.js, Laravel, and Django
- Infrastructure with Docker and Kubernetes
- State management (Pinia), build tooling (Vite), and databases (PostgreSQL, MongoDB)

The live portfolio site is at https://gkapologista.github.io/gkapologista-portfolio/#/
