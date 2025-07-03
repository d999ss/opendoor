---
project_id: "OP-276"
title: "Geo-Targeted Approach"
status: "In Progress"
priority: "P0"
owner: "Jocelyn McArthur"
last_updated: "2025-07-02"
related_projects: ["OP-000"]
tags: ["geopages", "seo", "geo-targeting"]
---

# Geo-Targeted Approach

## Table of Contents

- [Overview](#the-challenge)
- [SEO Strategy](#seo-strategy)
- [Market Opportunity Analysis](#market-opportunity-analysis)
- [Development Approach](#sprint-plan)
- [Assumptions](#assumptions)
- [Timeline and Budget](#timeline--budget)
- [Related Documents](#related-documents)

## Overview

Opendoor currently lacks robust geo-targeted content for its top markets, impacting SEO performance and local discoverability. There's an opportunity to develop a scalable strategy that balances unique market storytelling with programmatic efficiencies — ultimately increasing visibility and engagement in high-priority markets.

## The Challenge

Opendoor currently lacks robust geo-targeted content for its top markets, impacting SEO performance and local discoverability. There's an opportunity to develop a scalable strategy that balances unique market storytelling with programmatic efficiencies — ultimately increasing visibility and engagement in high-priority markets.

## SEO Strategy

Rather than conducting a full strategy phase, a targeted research sprint was conducted to quickly assess where Opendoor has the most opportunity to capture non-branded organic traffic.

By evaluating state-level search volume, current rankings, and competitor visibility, markets were prioritized based on potential monthly conversions.

This analysis considered both the SEO opportunity (based on "sell my house/home" search intent) and Opendoor's current performance relative to competitors in those regions.

The focus was intentionally placed on where Opendoor is not currently ranking, rather than where branded search is already driving traffic.

## SEO Recommendations

### Initial Focus: State-Level Hub Pages

Begin with state-level hub pages for the six markets with the highest untapped SEO opportunity:

1. Texas
2. California
3. Florida
4. Georgia
5. Virginia
6. North Carolina

These states offer strong search demand and relatively low visibility for Opendoor today—making them ideal candidates for content investment.

### Future Roadmap: City-Specific Pages

Once state pages are live, explore a programmatic SEO approach for city-specific pages.

This mirrors the structure used by competitors like Zillow and Offerpad, and allows for efficient scaling using a consistent template.

This two-tiered model—starting with high-opportunity state hubs, followed by scalable city-level rollout—provides the best balance of strategic targeting and long-term SEO growth.

## Market Opportunity Analysis

### Opportunity Analysis by State

| Priority | State | Estimated Potential Monthly Conversions |
|----------|-------|----------------------------------------|
| 1 | Texas | 120 |
| 2 | California | 93 |
| 3 | Florida | 78 |
| 4 | Georgia | 64 |
| 5 | Virginia | 63 |
| 6 | North Carolina | 62 |
| 7 | Pennsylvania | 39 |
| 8 | Tennessee | 35 |
| 9 | New Jersey | 32 |
| 10 | Ohio | 28 |

### Opportunity Analysis by City

| Priority | City | Estimated Potential Monthly Conversions |
|----------|------|----------------------------------------|
| 1 | Los Angeles, CA | 31 |
| 2 | Atlanta, GA | 30 |
| 3 | Dallas, TX | 25 |
| 4 | Charlotte, NC | 23 |
| 5 | Tampa, FL | 23 |
| 6 | Raleigh, NC | 20 |
| 7 | Orlando, FL | 20 |
| 8 | Miami, FL | 19 |
| 9 | Houston, TX | 18 |
| 10 | Phoenix, AZ | 17 |

### Session Opportunity by City

| City | Monthly Session Opportunity | Domain Position 1-4 | Opendoor Position |
|------|----------------------------|---------------------|-------------------|
| Houston, TX | 2,989 | Offerpad, Zillow, Houzeo, iBuyer | Not Ranking |
| Dallas, TX | 2,098 | Offerpad, iBuyer, Zillow, Houzeo | Not Ranking |
| Miami, FL | 1,775 | Zillow, Houzeo, iBuyer, HomeLight | Not Ranking |
| Tampa, FL | 1,636 | Offerpad, Houzeo, iBuyer, HomeLight | Not Ranking |
| Phoenix, AZ | 1,214 | OpenDoor, Houzeo, iBuyer, Offerpad | 1 |
| Charlotte, NC | 1,193 | Zillow, Houzeo, iBuyer, HomeLight | Not Ranking |
| Orlando, FL | 1,116 | Zillow, Offerpad, Houzeo, iBuyer | Not Ranking |
| Atlanta, GA | 1,112 | Houzeo, Offerpad, iBuyer | Not Ranking |
| Los Angeles, CA | 849 | Zillow, Houzeo, HomeLight | Not Ranking |
| Raleigh, NC | 592 | Zillow, OpenDoor, iBuyer, Offerpad | 2 |

## Development Approach

The development approach aligns with Opendoor's existing architecture—leveraging available tools, minimizing tech debt, and enabling scalable SEO-friendly content creation.

Based on the current setup, there is a clear opportunity to build within the existing Contentful framework and design system using a modular, maintainable approach.

### Development Recommendations

Opendoor's current Contentful setup and design system—particularly the use of modular components via Storybook and the SX prop—supports a scalable content model.

The recommendation is to start with a single flexible state-level landing page template, built from existing components wherever possible, and enhanced with lightweight SEO-optimized modules (headlines, CTAs, FAQ blocks, metadata support, etc.).

This approach:

- Minimizes custom development lift
- Speeds up time-to-market
- Supports future scaling to city-level pages via a repeatable structure
- Can be styled and curated uniquely per state using Contentful's layout flexibility

### Future Roadmap: City-Level Pages

Once the state-level pages are launched and validated, extend the template or create a small library of reusable components to support a programmatic rollout of city-specific landing pages.

These pages can reuse shared structures, drawing from structured data sources (e.g. ZIP codes, market data) to populate content dynamically.

This approach:
- Mirrors the approach taken by competitors (Zillow, Offerpad)
- Reduces manual overhead for long-tail content
- Aligns with SEO strategy to dominate non-branded search queries at scale
- Can be maintained by content and marketing teams using the existing self-service CMS setup

## Implementation Plan

With the market strategy in place, the implementation phase will bring six state-level geo-targeted pages to life through design, content, SEO, and development.

To ensure scalability and alignment across teams, the approach begins by building and launching a single state page first. This pilot will help validate the page structure, finalize content requirements, and identify any design system components that may need refinement. Once the initial page is approved, that framework will be applied to efficiently create and launch the remaining five state pages using a consistent, scalable format.

The full process will be managed from finalizing SEO specifications and UX templates to producing content and visual assets, building in Contentful, and launching with full QA.

### Sprint Plan

#### Sprint 1: Pilot Page Foundation & Setup

- Final SEO spec sheets and keyword mapping for six priority states
- Define UX structure and layout for state landing pages
- Audit and select existing DS components (identify any gaps)
- Build initial Contentful structure for state pages
- Outline copy + asset requirements for pilot state

#### Sprint 2: Pilot Page Content, Design & Build

- Draft copy for pilot state page
- Design visual layout for pilot page (desktop + mobile)
- Source or create necessary imagery
- Build pilot page in Contentful
- Input and configure copy + assets in CMS

#### Sprint 3: Pilot Review + Remaining State Prep

- Internal QA and feedback on pilot page (copy/design/dev)
- Apply edits and finalize pilot implementation
- Confirm final structure and content format for remaining 5 states
- Outline copy + asset requirements for remaining states
- Begin copywriting and design work for 2–3 state pages

#### Sprint 4: Remaining State Pages – Content, Design & Build

- Complete copywriting for remaining state pages
- Visual design for remaining state pages (using approved format)
- Source/create images for each state
- Build remaining state pages in Contentful
- Input and configure copy + assets in CMS

#### Sprint 5: QA

- QA all six pages across browsers, devices, and screen sizes
- Design and copy QA
- Client review and feedback
- SEO checks: metadata, internal linking, structured data

#### Sprint 6: Final Edits & Launch

- Final fixes from QA list
- Final copy/design refinements based on internal/client feedback
- Final client review before launch
- Publish and deploy all pages

## Assumptions

- **CMS Implementation Will Use Existing Design System and Contentful Setup**: Pages will be built using existing CMS capabilities and modular components from the current design system. Any required new components will be identified during the pilot build, but no major changes to the platform's architecture or functionality are assumed.

- **Pilot Page Will Finalize Structure for Remaining Builds**: One state page will be launched first to validate structure, content needs, and component use. That pilot will serve as the template for all remaining state pages, which will follow the same layout and content model with light variation.

- **Content Scope Includes Copywriting, Imagery, and SEO Metadata**: Each page will include new copy, sourced or created imagery (e.g., maps or icons), and full SEO tagging (headings, metadata, alt text, structured data). No video or advanced interactive content is assumed at this time.

- **Content Population in CMS**: The team will be responsible for uploading and formatting all copy and visual assets in Contentful, including page-level configuration and SEO metadata.

- **No Net-New Platform Features Required**: Development will stay within the current stack (React + Contentful) and not require major backend updates, new infrastructure, or third-party integrations. If blockers arise during pilot implementation, they'll be flagged and scoped separately.

- **Scope Covers Six Pages Only; Scaling Out of Scope**: This estimate includes six custom state landing pages. Any future expansion—such as city-level programmatic pages or scaling to additional states—can be scoped separately based on performance and team readiness.

## Timeline & Budget

- **Timeline**: 6 sprints / 12 weeks
- **Budget**: $75,150

## Related Documents

- [OP-000: Opendoor Site Brief](opendoor-site-brief.md) - Main project brief and overview
- [OP-276: Geopages & Campaign Pages](geopages-campaign-pages.md) - Implementation plan for location-specific pages
