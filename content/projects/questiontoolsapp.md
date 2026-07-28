---
title: QuestionToolsApp
slug: questiontoolsapp
weight: 3
project_number: 3
featured: true
summary: A desktop data-cleaning tool for question-bank spreadsheets with filtering, deduplication, and backup-safe export.
categories:
  - desktop
  - data
stack:
  - Python
  - pandas
  - openpyxl
  - Tkinter
  - ttkbootstrap
  - PyInstaller
visual: clean
platform: Windows desktop
distribution: Standalone .exe
github: https://github.com/ShahriarAR/QuestionToolsApp-Demo
description: Case study for QuestionToolsApp, a practical utility for safely cleaning educational spreadsheet content.
---

## The operational problem

Question-bank spreadsheets can accumulate duplicate rows, inconsistent language content, and changes that are difficult to undo. Manual cleanup is slow, while a careless automated edit can remove valuable material.

QuestionToolsApp provides a focused desktop workflow for those recurring cleanup tasks. It combines filtering and deduplication with backup-aware export so users can make changes without losing a recovery path.

## The solution

The tool uses **pandas** and **openpyxl** for spreadsheet operations, with a Tkinter and ttkbootstrap interface that keeps the workflow accessible on Windows.

Key capabilities include:

- Filtering and deduplication for messy question banks
- English-only removal workflow
- Safe export with undo backups
- Packaged Windows distribution through PyInstaller

## Design priorities

### Reversible cleanup

Data cleaning should not require blind trust. Backup-safe export creates a practical recovery path and makes destructive operations less intimidating.

### Focused controls

The interface is organized around the actual cleanup jobs rather than exposing every low-level spreadsheet operation. That keeps the tool approachable for repetitive use.

### Local, distributable software

As a packaged desktop application, the workflow stays close to the source files and does not depend on a remote service.

## What the project demonstrates

QuestionToolsApp shows my interest in the less glamorous but highly valuable side of software: careful data preparation, understandable tools, and small safeguards that prevent avoidable problems.
