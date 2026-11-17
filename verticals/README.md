# SaintSal industry landing pages

Three standalone, dependency-free landing pages targeting `/medtech`, `/fintech`, and `/edtech` on https://www.saintsal.ai/. Built November 16, 2026 (Los Angeles).

## Deployment status

Live standalone showcase: https://saintsal-industry-showcase.vercel.app/ (Vercel project saintsal-industry-showcase, deployment dpl_E43odzXhZVCrPDF4dAYQKeaNzTYp). All three public HTTPS routes and MedTech example interaction verified in browser. No login required. Source uploaded through Vercel API; automatic Git deployments are not configured. Search engines are instructed not to index this showcase. NOT deployed on SaintSal.ai. This repository is the founder feed repository, not a confirmed source for the live SaintSal.ai application. The connected Vercel account returned 403 for the SaintSal.ai domain; the accessible webapp redesign source does not match the live homepage. Identify the active production repository/service before integrating. Do not point the apex domain at this package or replace the main application.

## Integration

The three directories contain self-contained index.html files with inline CSS and JavaScript, no dependencies, no database calls and no authentication changes. Mount them at the three exact paths in the production application's existing routing system; ensure slash and no-slash variants resolve. In Next.js, migrate the markup/styles and example selector into route components, or serve these files through explicit rewrites to public assets after checking existing middleware. Add the three destinations to the existing product navigation and sitemap. Preserve existing consent and attribution controls; this package loads no analytics scripts.

Calendly links carry a per-vertical UTM campaign. This does not install attribution, a CRM connection or lead capture. Email and telephone links use founder-authorized public details. Confirm Calendly availability during production acceptance.

## Content basis

Reviewed public sources:
- https://www.saintsal.ai/ — document knowledge, conversation, team setup and guardrails.
- https://www.saintsal.ai/pricing — platform plan differences and Enterprise API access.
- https://www.saintsal.ai/download — current download offering.
- https://www.saintsal.ai/trust — access, processing, governance and organization-specific questions.

Product examples are editorial illustrations, not live AI demonstrations. Platform capabilities are distinguished from proposed specialist integrations. Public SDK package/version availability, EHR/LMS integrations, regulatory certifications and industry-specific production readiness were not verified. No funding, performance, clinical, educational outcome or regulatory approval claims are made. Industry rollout language must be updated from verified release information before claiming general availability of a complete specialist system.

## Validation

- All three HTML files parsed; one H1 per page, unique IDs, valid local anchor targets and cross-page destinations.
- Embedded JavaScript passed Node syntax checks.
- Browser preview: all three pages opened, cross-page navigation worked, each example selector changed the displayed request/output, and the EdTech FAQ expanded.
- Desktop MedTech visual review completed. Mobile-specific browser testing and production HTTP/HTTPS checks remain for deployment.

To preview locally, serve this directory using a static web server and open one of the three routes. `build.py` regenerates the pages from their content model.
