# Contributing to Cybersecurity Career Roadmap

First of all, thank you for being here. This project exists to help people understand the cybersecurity field clearly and completely. Every contribution makes it better for thousands of learners.

---

## Before You Contribute

Please read this document fully before opening a pull request. It keeps the quality consistent across the entire wiki.

---

## What You Can Contribute

- A new role page (from the role list in README)
- A concept page inside any pillar's `concepts/` folder
- A tool overview page inside the `tools/` folder
- Fixing typos, broken links, or outdated information
- Improving an existing page with better resources or clarity

---

## What You Cannot Contribute

- Exploit code, payloads, or attack scripts
- Illegal or unethical instructions of any kind
- Content that promotes harm, misuse, or illegal activity
- Copy-pasted content from other sources without credit
- AI-generated content that is unreviewed or inaccurate

This is a **learning resource**, not an attack toolkit. Keep it that way.

---

## Role Page Template

Every role page must follow this exact structure. Do not skip any section.

```markdown
# Role Name

## Role Overview
A clear 2-3 sentence description of what this person does day to day.

## Core Responsibilities
- Responsibility 1
- Responsibility 2
- Responsibility 3

## Knowledge Required
- Topic 1
- Topic 2
- Topic 3

## Tools Used
| Tool | Purpose |
|------|---------|
| Tool Name | What it is used for |

## Career Progression
Entry Level → Mid Level → Senior → Lead / Manager

## Certifications
| Certification | Level | Provider |
|---------------|-------|----------|
| Cert Name | Beginner / Intermediate / Advanced | Org |

## Learning Resources
- [Resource Name](URL) — short description
- [Resource Name](URL) — short description
```

---

## File Naming Rules

- Use lowercase only
- Use hyphens instead of spaces
- Include the role number as prefix

**Examples:**
```
01-junior-penetration-tester.md
02-penetration-tester.md
15-adversary-simulation-specialist.md
```

For concept pages:
```
concepts/what-is-pentesting.md
concepts/pentest-methodology.md
```

For tool pages:
```
tools/nmap.md
tools/burp-suite.md
```

---

## Folder Structure

Place your file in the correct folder:

```
01-Offensive-Security/        ← Offensive roles
02-Defensive-Security/        ← Defensive roles
03-Security-Engineering/      ← Engineering roles
04-GRC/                       ← GRC roles
05-Threat-Intelligence/       ← Intel roles
tools/                        ← Tool overview pages
```

Each pillar folder also has a `concepts/` subfolder for topic pages.

---

## How to Submit

1. Fork this repository
2. Create a new branch: `git checkout -b add/role-name`
3. Add your file following the template above
4. Commit with a clear message: `git commit -m "add: junior penetration tester page"`
5. Push and open a Pull Request
6. Fill in the PR description — what role/concept you added and any sources used

---

## Commit Message Format

Keep commit messages clean and consistent:

```
add: junior penetration tester page
add: nmap tool overview
fix: broken link in penetration-tester.md
update: added OSCP to certifications in red-team-operator.md
```

---

## Quality Checklist

Before submitting, check every item:

- [ ] File is in the correct folder
- [ ] File name follows naming rules
- [ ] All template sections are filled in
- [ ] No placeholder text left behind
- [ ] Links are working
- [ ] No exploit code or illegal content
- [ ] Language is clear and simple English

---

## Questions?

Open an issue and tag it `question`. We will get back to you.

---

*Built with consistency by [@krakeninfosec](https://github.com/krakeninfosec)*
