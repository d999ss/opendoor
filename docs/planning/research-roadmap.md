# Research Roadmap

## Overview

Tags: #research #roadmap #geo-targeting #seo #content-validation #performance #optimization

This document outlines the research plan for the Opendoor geo-targeting initiative across multiple sprints, focusing on content validation, technical baseline, performance optimization, and launch preparation.

## Sprint 3: Content Validation

### User Research Focus

- User testing for the pilot state page content and messaging
- A/B testing of state-specific value propositions
- Local validation of testimonials and case studies
- Brand voice tuning for each geographic market

### Technical Content Baseline

- Measure current Opendoor SEO performance
- Analyze competitor rankings for target keywords in each state
- Map local search patterns and seasonal trends
- Compare mobile and desktop usage by region

## Sprints 4 and 5: Scaling and Optimization

### Performance Focus

- Define page speed targets for each region
- Evaluate CDN performance
- Analyze pilot page engagement metrics
- Highlight conversion lift opportunities from pilot data

### Expansion Planning

- City-level keyword research for future programmatic pages (see [geo-targeted-approach.md](../geo-targeted-approach.md) lines 57 to 63)
- Prioritize additional states beyond the first six
- Document integration needs with existing marketing tools
- Assess Contentful model scalability

## Sprint 6: Launch Preparation

### Quality Assurance

- Cross-browser compatibility testing
- Validate accessibility compliance
- Run SEO audit including hreflang and HTML validation (see [geopages-campaign-pages.md](../geopages-campaign-pages.md) lines 194 to 211)
- Confirm analytics and performance monitoring setup

### Post-Launch Planning

- Define success metrics and measurement methods
- Set content maintenance and update schedules
- Establish market expansion decision framework
- Plan long-term SEO tracking

## Detailed Research Roadmap (OP-276)

### Sprint 3: User Research & Content Validation

**Research Focus:**

- User-test pilot state page copy & CTAs
- A/B value props (home-price vs speed) on `/texas`
- Geo-check testimonials, case studies
- Micro-tune brand voice by region

**Key Activities:**

- 10 moderated sessions (remote)
- 2-variant test live 48 h
- Local fact vetting sheet
- Voice matrix (tone, vocab)

**Outputs:** 1-page insights deck → drives copy revisions for S-4

**Technical Baseline Research:**

- Benchmark current Opendoor SEO
- Scrape competitor ranks for top 10 keywords/state
- Pull Google Trends seasonality
- Mobile vs desktop split by state

**Outputs:** SEO baseline report, gap list (per state)

### Sprint 4: Performance & Expansion

**Performance Research:**

- Set Speed Index ≤ 2 s target
- Lab + field test CDN edge nodes
- Track engagement on `/texas` (scroll, CTA)

**Outputs:** Web-perf dashboard, list of quick-win optimizations

**Expansion Research:**

- City-level keyword mining (see geo-targeted-approach 57-63)
- Rank additional states (traffic × CPC)
- Map mar-tech integration hooks (Marketo, Braze, GA4)
- Stress-test Contentful model scale limits

**Outputs:** Prioritized backlog of 50 cities + 6 next states

### Sprint 5: Optimization

**Optimization Activities:**

- Convert perf findings into code tweaks
- Run pilot CRO experiments on new layout elements

**Outputs:** Lift projections + merged PRs

### Sprint 6: QA & Launch

**QA Activities:**

- Cross-browser suite (Chrome, Safari, Edge, Firefox, iOS, Android)
- WCAG 2.2 AA scan
- Full technical SEO audit (hreflang, HTML valid)
- GA4 + Perf monitoring validation

**Outputs:** Green-light checklist signed by PM

### Post-Launch Planning

**Long-term Strategy:**

- Define success KPIs (organic sessions, lead start rate, page value)
- Publish content-update cadence (quarterly)
- Framework for adding new markets (traffic > 30 k/mo or ≥ 5 % share gap)

**Outputs:** Living KPI dashboard + playbook

## Ownership (Lean Team)

- **Research execution**: AI generates scripts, scrapes, analyses
- **Implementation**: Vercel v0 auto-applies page or performance changes
- **Decision & sign-off**: Project Manager

## Critical Path

1. Finish pilot state page (<20 min left): live A/B hooks + analytics tags
2. Sprint 3 research starts immediately on live traffic
3. All subsequent research feeds straight into code via v0 prompts

Everything above fits inside the six-sprint window; no CMS needed.

## Related Documents

- [Research Foundation OP-276](research-foundation-op-276.md)
- [Geo-Targeted Approach](../geo-targeted-approach.md)
- [Geopages Campaign Pages](../geopages-campaign-pages.md)
