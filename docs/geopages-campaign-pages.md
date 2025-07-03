---
project_id: "OP-276"
title: "Opendoor Geopages and Campaign Pages"
status: "In Progress"
priority: "P0"
owner: "Jocelyn McArthur"
last_updated: "2025-07-02"
related_projects: ["OP-000"]
tags: ["geopages", "campaigns", "seo"]
---

# Opendoor Geopages and Campaign Pages

## Project Metadata

- **Delivery Lead:** Jocelyn McArthur  
- **Client Partner:** Nicole Hampton  
- **Creative Lead:** Chris Kerr  
- **Project Status:** Planning  
- **Target Completion:** September 5, 2025
- **Project Number:** OP-276  

## Table of Contents

- [Background and Motivation](#background-and-motivation)
- [Key Challenges and Analysis](#key-challenges-and-analysis)
- [High-level Task Breakdown](#high-level-task-breakdown)
- [Timeline Planning](#timeline-planning)
- [Project Status Board](#project-status-board)
- [Integration with Other Systems](#integration-with-other-systems)
- [Resources](#resources)
- [Related Documents](#related-documents)

## Background and Motivation

Opendoor needs to develop and organize location-specific (geo) pages and campaign landing pages to improve SEO performance and provide targeted content for marketing campaigns. These pages will help capture location-specific search traffic and provide customized experiences for users coming from different marketing campaigns.

A detailed analysis has identified that Opendoor currently lacks robust geo-targeted content for its top markets, impacting SEO performance and local discoverability. There's an opportunity to develop a scalable strategy that balances unique market storytelling with programmatic efficiencies — ultimately increasing visibility and engagement in high-priority markets. For complete details, see the [Geo-Targeted Approach](./geo-targeted-approach.md) document.

## Key Challenges and Analysis

- Need to create a scalable template system for location-based content
- Must ensure consistent branding while allowing for location-specific customization
- Campaign pages need to be easily created and modified for different marketing initiatives
- Both page types need strong SEO optimization
- Content must align with the overall goal of improving brand perception and increasing offer flow
- Opendoor is not currently ranking for key non-branded search terms in major markets
- Competitors like Zillow and Offerpad have established presence in top markets

## High-level Task Breakdown

### Geopages Implementation

1. **Research and Analysis**
   - Success criteria: Complete analysis of target locations and SEO keywords
   - Identify high-priority markets for initial implementation
   - Research location-specific real estate trends and terminology
   - Analyze competitor geopage strategies

   **Note**: Initial research has identified six priority states for implementation: Texas, California, Florida, Georgia, Virginia, and North Carolina. These states offer strong search demand and relatively low visibility for Opendoor today.

2. **Template Design**
   - Success criteria: Approved template design that can be easily adapted for different locations
   - Create modular components that can display location-specific data
   - Design dynamic content sections for market statistics
   - Incorporate location-specific imagery and testimonials

   **Note**: The recommendation is to leverage Opendoor's current Contentful setup and design system—particularly the use of modular components via Storybook and the SX prop—to create a scalable content model.

3. **Content Strategy**
   - Success criteria: Content guidelines and structure for each location
   - Develop location-specific value propositions
   - Create content templates for consistent messaging
   - Plan for regular content updates based on market changes

4. **Technical Implementation**
   - Success criteria: Functioning geopages with dynamic content loading
   - Build backend system for managing location data
   - Implement URL structure for optimal SEO
   - Create automated testing for location-specific content rendering

### Campaign Pages Implementation

1. **Campaign Framework Development**
   - Success criteria: Flexible campaign page system that marketing can easily configure
   - Design modular campaign page templates
   - Create component library specific to campaign needs
   - Develop tracking system for campaign performance

2. **Integration with Marketing Tools**
   - Success criteria: Seamless connection between campaign pages and marketing analytics
   - Set up UTM parameter handling
   - Implement conversion tracking
   - Create dashboard for campaign performance metrics

3. **A/B Testing Framework**
   - Success criteria: System for testing different campaign page variations
   - Develop methodology for testing page elements
   - Create reporting system for test results
   - Implement easy deployment of winning variations

## Timeline Planning

### Target Completion Date

September 5, 2025

Based on the tasks outlined in this document, the following timeline structure will be used to track progress. The implementation is planned for 6 sprints over 12 weeks with a budget of $75,150.

A detailed sprint-by-sprint implementation plan is available in the [Geo-Targeted Approach](geo-targeted-approach.md) document.

### Phase 1: Research and Planning

- Research target locations and SEO keywords for geopages
- Analyze competitor geopage strategies
- Define requirements for campaign page framework

### Phase 2: Design and Prototyping

- Design geopage template structure
- Create modular components for location-specific data
- Design campaign page framework
- Develop content strategy for geopages

### Phase 3: Development

- Implement technical foundation for geopages
- Build backend system for managing location data
- Integrate campaign pages with marketing tools
- Develop A/B testing system for campaign pages

### Phase 4: Testing and Refinement

- Test location-specific content rendering
- Verify SEO optimization
- Test campaign tracking and analytics
- Create documentation for marketing team

### Phase 5: Launch and Evaluation

- Deploy initial set of geopages
- Launch campaign page system
- Establish monitoring and performance metrics
- Plan for ongoing optimization

## Project Status Board

- [ ] Task 1: Research target locations and SEO keywords for geopages

- [ ] Task 2: Create wireframes for geopage templates

- [ ] Task 3: Develop content strategy for location-specific pages

- [ ] Task 4: Build backend system for managing location data

- [ ] Task 5: Implement frontend components for geopages

- [ ] Task 6: Launch initial set of geopages for top markets

- [ ] Task 7: Develop A/B testing system for campaign pages

- [ ] Task 8: Create documentation for marketing team on using campaign page system

## Current Status / Progress Tracking

Project planning phase. Awaiting initial direction on which task to prioritize first.

## Executor's Feedback or Assistance Requests

No feedback or assistance requests at this time.

## Integration with Main Site Brief

The geopages and campaign pages work should align with the overall site redesign principles outlined in the main site brief:
- Incorporate the warmer, more human design elements
- Ensure dynamic content capabilities
- Allow for personalization based on user data
- Follow the seasonal messaging strategy (Q4/Q1 vs Q2/Q3)
- Utilize the expanded component library being developed

## Resources Needed

- Access to location-specific market data
- Marketing campaign calendar and objectives
- Analytics on current site performance by location
- Brand guidelines and updated design system components

## SEO and Competitive Intelligence

### Technical SEO Findings

Based on the April 2024 technical SEO audit, several critical issues need to be addressed as part of the geopages implementation:

1. **Hreflang Implementation Issues**
   - 71.43% of URLs have missing return links in hreflang annotations
   - 5.33% of URLs are not using canonical URLs in hreflang annotations
   - These issues may cause search engines to misinterpret or ignore our international targeting

2. **HTML Validation Problems**
   - Multiple `<body>` and `<head>` tags detected across pages
   - Page titles outside `<head>` element (4.38% of URLs)
   - These structural issues can impact how search engines parse and index our content

3. **Content Duplication**
   - 1.44% of pages are exact duplicates using MD5 hash comparison
   - This splits PageRank signals and creates unpredictability in rankings

4. **Image Optimization Needed**
   - 41.09% of images missing alt text
   - 20.59% of images missing alt attributes entirely
   - Proper image optimization is essential for accessibility and image search visibility

### Competitor Analysis Insights

**Offerpad Strategy:**
- Uses location-specific landing pages with customized market data
- Offers flexible closing dates (8-90 days) and additional perks like free local moves
- User flow focuses on quick offer generation (within 24 hours)
- Currently experiencing financial challenges in declining housing market

**Redfin Approach:**
- Combines traditional brokerage services with iBuyer program (RedfinNow)
- Strong focus on user-friendly property search with robust filtering
- Provides agent insights directly on listings
- Offers both in-person and virtual tours through their platform

**Zillow Strategy:**
- Discontinued Zillow Offers program after substantial losses
- Remains a significant player through their marketplace model
- Strong focus on content marketing and SEO for location-based searches

**European Competitors:**
- Casavo (Italy/Spain/Portugal): Recently secured €20 million in funding, transitioning from iBuyer to marketplace model
- Kodit.io (Finland/Spain): Rebranded as Rive in 2022, expanding beyond iBuying to comprehensive home services

These insights should inform our geopages strategy, particularly in how we position Opendoor's value proposition against competitors in each market and address technical SEO issues that could impact performance.

## Related Documents

- [OP-000: Opendoor Site Brief](opendoor-site-brief.md) - Main project brief and overview
- [OP-276: Geo-Targeted Approach](geo-targeted-approach.md) - Detailed SEO strategy for state and city pages
- [OP-262: Opendoor Landing Pages](/.cursor/scratchpad.md) - Project status for overall landing pages initiative
