# Nenolink Website Content Structure

This repository is the working structure for the future Nenolink website content.

The website is organised around four long-term pillars:

1. **Translation**
2. **Content**
3. **Software & AI**
4. **Knowledge**

Additional sections cover **About Nenolink**, policies and contact information.

## Proposed website structure

```text
Home

Translation
├── Localization
├── Translation Agencies
├── Tourism
├── Technical
└── Workflow

Content
├── Copywriting
├── SEO
├── Editing & Proofreading
├── Document Handling
└── Photos & Media

Software & AI
├── AI Consulting
├── Android Apps
├── Windows Apps
├── Development
├── Automation
└── GitHub

Knowledge
├── Articles
├── Guides
├── FAQ
├── Downloads
└── Case Studies

About
├── About Nenolink
├── AI Policy
├── GDPR & Privacy
├── Quality
└── Contact
```

## Page production workflow

Each page is developed in two stages.

### Stage 1 — Content

- Main text
- Images
- Internal linking

### Stage 2 — SEO and distribution

- SEO title
- Meta description
- Structured data / schema
- AI summary
- Open Graph metadata
- LinkedIn preview

This staged workflow makes it practical to build approximately one page per day in Nicepage while keeping content, SEO and structured data consistent.

## Standard page checklist

Every page folder can use the shared checklist in [`templates/seo-checklist.md`](templates/seo-checklist.md).

- [ ] URL
- [ ] H1
- [ ] H2
- [ ] Problem box
- [ ] Main text
- [ ] CTA
- [ ] Internal links
- [ ] Images
- [ ] Alt text
- [ ] Meta title
- [ ] Meta description
- [ ] Structured data
- [ ] AI summary
- [ ] Open Graph
- [ ] LinkedIn image
- [ ] Language versions
- [ ] Last updated

## Folder conventions

Each page has its own folder with:

```text
page-name/
├── content.md
├── metadata.yml
├── seo.md
├── schema.json
├── notes.md
└── images/
```

The repository is intended to be the long-term source of truth for Nenolink website content, while Nicepage remains the publishing interface.
