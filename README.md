# Technical Interview

The technical interview will take around 90 minutes and consists of two parts:

1. Refinement
The problem statement should be thoroughly understood and possible solutions should be formulated. The selected solution should prepared for implementation.

2. Pair Programming
The soulution that has been selected is now to be implemented together with an engineer from Penzilla.

Our product development process is fully dependent on engineers taking ownership of the problems they tackle. It is therefore essential to build a deep understanding of why this problem exists and how to best address it. It is frequently necessary to gather input from other team members such as Advisors or Sales for this.

Which shape the solution takes should ultimately be a logical consequence of the process. Of course there could be many solutions that overlap or complement each other.

## Problem Statement

For this interview the problem we work on will be:

**Advisor (bAV-Berater) haben keine Übersicht über bAV-relevante Änderungen der Mitarbeitenden.**

## About this repository

This repository is a [NX Workspace](https://nx.dev). All tooling works through the `nx` CLI tool. We use NX internally and encourage you to make yourself familiar with it. However, for this interview it is not expected that you know anything about the tool.

To make working with this workspace a bit easier here the most important commands:

### Frontend
Serve the frontend: `nx serve frontend`
Run tests for the frontend: `nx test frontend`

### Backend
Serve the backend: `nx serve backend`
Run tests for the backend: `nx test backend`

### Both
`nx run-many --target serve|test`
