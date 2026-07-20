# Contributing to Bottega

This document defines the basic contribution rules for the Bottega project.

## Commit Message Rules

Commit messages should be written in English and in imperative mood.

A commit message should describe what the commit does when applied. For example, use `Add contributing guide` instead of `Added contributing guide`.

The summary line should be short, clear, and meaningful. As a general rule, keep the first line around 50 characters when possible.

Good examples:

```bash
Add product card markup
Fix footer navigation link
Update README setup section
```

Weak examples:

```bash
changes
update
fix stuff
```

## Branch Naming

Branch names should be short, descriptive, and related to the work being done.

Use lowercase words separated with hyphens.

Good examples:

```bash
docs-contributing
feature-footer-year
fix-readme-heading
```

## Course Commit/Tag Convention

Each completed course should be committed and pushed to GitHub.

For content or build courses, the completed version should also be tagged with the course number.

Example:

```bash
git add .
git commit -m "Complete course 1.1"
git push

git tag course-1.1
git push origin course-1.1
```

This convention makes each course milestone easy to find in the Git history and on GitHub.