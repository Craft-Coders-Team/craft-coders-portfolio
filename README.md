# CRAFT CODERS: Portfolio & Studio Platform

![CRAFT CODERS logo](./assets/craft-coders-logo.jpeg)

> **Build • Code • Together**
> *Building what's next.*

A design-forward portfolio and studio platform for **CRAFT CODERS**, a software development studio. The project covers a public website, an internal admin dashboard, and a set of reusable components, all built on one brand system derived from the studio's logo.

---

## Team

| Name | Role | GitHub | LinkedIn |
|---|---|---|---|
| Assem Karam | Developer | [@assemkaram](https://github.com/assemkaram) | [Profile](https://www.linkedin.com/in/assemkaram) |
| Amany Mohamed | Developer | [@AmanyMohamed-eng](https://github.com/AmanyMohamed-eng) | [Profile](https://www.linkedin.com/in/amanymsadky) |

---

## Overview

The platform has three parts:

1. **Public website:** Homepage, About, Services, Projects, Case Studies, Team, Contact, Blog, Testimonials, FAQ, Process, Privacy Policy, and a 404 page.
2. **Admin dashboard:** Visitor analytics, GitHub and LinkedIn insights, team and project management, a CRM pipeline, CMS, SEO health, and client portal.
3. **Signature modules:** Command palette, technology node map, project cost estimator, interactive timeline, conversion funnel, and project comparison.

The visual direction is editorial and geometric, closer to a premium design studio than a SaaS product. The brand mark, an isometric folded "C" with a `</>` cut into its center, drives the layout, motion, and iconography.

---

## Brand System

### Color

| Token | Hex | Use |
|---|---|---|
| Void Black | `#05070D` | Sidebar, footer, modal scrims |
| Logo Navy | `#0A0F1F` | Primary dark background |
| Surface Navy | `#131B33` | Cards, table rows, inputs |
| Electric Blue | `#2F7BFF` | Primary CTAs, active navigation, key data |
| Sky Blue | `#5AA9FF` | Hover states, chart series, text accents on dark |
| Cobalt | `#1E40C8` | Pressed states, offset shadows |
| Silver | `#C7D0DF` | Secondary text, dividers, mark edges |
| Ice White | `#F5F7FB` | Primary text on dark, light-mode background |
| Slate | `#8A93A8` | Metadata, captions |
| Coral | `#FF6B4A` | Errors, warnings, Archived and Lost states only |
| Lavender | `#B9A2FF` | Tertiary chart series, tags |

Hex values are sampled from the logo and should be replaced with official brand values when available.

### Typography

- **Space Grotesk:** headlines and display type
- **Inter:** body copy, interface labels, forms
- **Space Mono:** statistics, timestamps, code, technical labels

### Accessibility

- Body text meets WCAG AA (4.5:1).
- Electric Blue is never used for text on Surface Navy. Sky Blue is used instead.
- Visible 2px focus rings for keyboard navigation.

---

## Project Structure

```
craft-coders/
├── assets/                 # Logo files, icons, illustrations
├── design/                 # Stitch and Figma exports, reference frames
├── docs/                   # Brand guidelines, content notes
├── src/
│   ├── components/         # Shared UI components (buttons, cards, tables, charts)
│   ├── tokens/             # Color, type, spacing, and effect tokens
│   ├── pages/
│   │   ├── public/         # Website pages
│   │   └── admin/          # Dashboard screens
│   ├── modules/            # Command palette, node map, estimator, timeline, etc.
│   └── data/               # Demo data (clearly labeled)
└── README.md
```

Adjust this structure to match the chosen framework.

---

## Features

### Public Website
- Asymmetric homepage with an animated isometric C-fold hero
- Services index with expandable entries
- Masonry project gallery with category and technology filters
- Case studies with architecture diagrams, process timelines, and result metrics
- Team profiles with GitHub and LinkedIn links
- Multi-step contact form with budget slider
- Mobile navigation sheet

### Admin Dashboard
- Overview with period-over-period comparison
- Visitor analytics: sources, devices, geography, funnels, custom events
- GitHub intelligence: repositories, commits, pull requests, language distribution
- LinkedIn insights: followers, impressions, engagement
- Team, project, and service management
- CRM pipeline: New → Contacted → In Discussion → Proposal Sent → Won / Lost
- AI business intelligence panel with a natural-language analytics chat
- CMS for all public content, plus SEO and website health
- Role-based permissions, audit logs, and security settings

### Interaction
- Command palette (Ctrl/⌘ + K)
- Light and dark themes
- Subtle motion: 4px hover offsets, underline wipes, panel transitions

---

## Data & Integrations

**All data in this project is demo data.** Sample metrics, team members, projects, and leads are placeholders for visual and usability review.

Integration panels are shown in one of three states:

- **Connected:** the integration is authorized and syncing
- **Not connected:** no integration has been set up
- **Authorization required:** the integration exists but needs permission

No screen implies that live GitHub, LinkedIn, or Search Console data is connected unless that integration is actually built and authorized.

---

## Getting Started

> Setup steps depend on the chosen stack. Update this section once the framework is selected.

```bash
# 1. Clone the repository
git clone https://github.com/<your-org>/craft-coders.git
cd craft-coders

# 2. Install dependencies
npm install

# 3. Copy environment variables
cp .env.example .env.local

# 4. Start the development server
npm run dev
```

### Environment Variables

```bash
# Optional integrations, leave empty to keep them disconnected
GITHUB_TOKEN=
LINKEDIN_CLIENT_ID=
LINKEDIN_CLIENT_SECRET=
GOOGLE_SEARCH_CONSOLE_KEY=
```

---

## Design Workflow

1. **Foundations:** tokens, type styles, logo assets, and grid settings are defined first.
2. **Reference screens:** Homepage and Admin Overview are designed first to set the design language.
3. **Remaining screens:** built from the same grid, type scale, and components.
4. **Review:** check both themes, mobile layouts, and keyboard focus states.

---

## Roadmap

- [ ] Finalize official brand colors and confirm the tagline
- [ ] Build foundations: tokens, type, grid, logo assets
- [ ] Design homepage and admin overview
- [ ] Build the public website pages
- [ ] Build the admin dashboard
- [ ] Add the signature modules
- [ ] Connect real content through the CMS
- [ ] Authorize GitHub, LinkedIn, and Search Console integrations
- [ ] Accessibility and performance audit
- [ ] Launch

---

## Contributing

1. Create a branch from `main`: `git checkout -b feature/your-feature`
2. Commit changes with clear messages.
3. Open a pull request with screenshots for any visual change.

---

## Contact

- **Email:** hello@craftcoders.dev
- **GitHub:** github.com/craft-coders
- **LinkedIn:** linkedin.com/company/craft-coders

---

## License

© CRAFT CODERS. All rights reserved. Replace with the chosen license before publishing.
