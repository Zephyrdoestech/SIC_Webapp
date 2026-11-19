# Social Impact Catalyst - CIT-U Chapter

<!-- impeccable:product-schema 1 -->

## Platform

web

## Stack

- ReactJS with Vite and Tailwind CSS.
- Initial data: local JSON, clearly labeled mock data, and localStorage.
- Keep data-access logic separate from UI components so backend integration does not require rebuilding the frontend.
- Optional Node.js and SQLite only if needed to test persistent data and administrative workflows; avoid unnecessary backend complexity.
- Future backend: Supabase PostgreSQL, Authentication, Storage, and Row Level Security, only after the local experience is validated and integration is explicitly approved.
- Run locally with Vite during initial development. No deployment or cloud-service initialization in the planning and local prototype stages.
- Future hosting preference: Vercel frontend and Supabase Cloud, prioritizing free-tier compatibility and minimal cost.

## Users

Primary audiences are Cebu Institute of Technology-University students (Teknoys), recognized student organizations, and SIC members and officers. University administrators, potential partners, and the wider community are also welcome.

Students discover opportunities, join initiatives, and understand collective impact. Organization representatives submit and track their projects and events. SIC administrators review contributions and manage organizational content and impact records.

## Product Purpose

Create a centralized university-wide social impact platform that empowers students to participate in meaningful initiatives, enables collaboration among organizations, and showcases CIT-U's collective contributions toward the United Nations Sustainable Development Goals (SDGs).

Success means Teknoys can discover opportunities, collaborate, take action, and see measurable collective contributions. SIC should be represented both as a student-led advocacy organization and a university-wide catalyst for social impact.

## Positioning

A CIT-U community platform connecting student-led initiatives across organizations through SDG-aligned project records, reviewed contributions, and shared impact reporting, while retaining a dedicated SIC organizational presence.

## Operating Context

- Public visitors explore SIC, events, impact records, stories, publications, partnerships, and participation opportunities.
- Authorized organization representatives submit SDG-related projects and events through forms and track submissions.
- SIC administrators review and approve submissions before they contribute to public impact statistics.
- Administrators and authorized representatives manage permitted submissions, publications, event information, and impact records in a dedicated workspace.
- Membership applications redirect to an external application destination; event registration, feedback, and partnership inquiries use integrated forms or confirmed destinations.
- Local development uses simulated roles. Real authentication and authorization belong to the explicitly approved backend integration phase.
- Homepage priority: discover initiatives and join an activity.
- Organization representatives manage only their own organization's submissions. The confirmed review flow is draft -> submitted -> changes requested or approved, with resubmission. SIC administrators approve public records and manage SIC publications.
- Event registration uses per-event external links, with a clearly labeled local demo destination until real links exist. Membership remains an external redirect.

## Capabilities and Constraints

Required content and functionality:

- About Us, Mission, Vision, Goals, organizational background, advocacy, and commitment to leadership and sustainable development.
- Upcoming events, ongoing projects, and previous activities from SIC and other recognized CIT-U student organizations.
- Interactive impact dashboard showing completed projects, participating organizations, events conducted, and SDGs addressed, calculated from approved project records.
- University-wide SDG project and event tracker with submission, review, approval, and tracking workflows.
- Unified event highlights featuring photographs, achievements, and impact stories across organizations.
- Dedicated SIC blog with advocacy articles, announcements, organizational updates, and featured stories.
- Partnerships page with existing collaborations and inquiry or proposal submission.
- Integrated forms, membership application redirect, event registration, feedback, and participation opportunities.
- Functional validation, filtering, search, navigation, dashboards, and content-management interfaces using local mock data.

Prioritize an engaging public website with clear navigation and storytelling, supported by an administrative system. Maintain modular, scalable, maintainable code. A local simulated-role prototype must not be presented as production authentication or security.

Development sequence: sitemap, user flows, wireframes, and design system, followed by a complete local frontend prototype. Validate locally before requesting approval for Supabase integration. Do not deploy during these stages.

Open decisions: detailed permissions beyond the confirmed organization ownership and SIC review roles; edit-after-approval behavior; impact metric definitions and counting rules; final sitemap; production form destinations; publication and project schemas; and verified public content. Decide these during planning without inventing organizational policy.

## Brand Commitments

Strictly follow `ASSETS/SIC BRAND BIBLE.pdf` and the supplied logo assets.

Use the actual `ASSETS/SIC-LOGO-WHITE.png` for SIC branding, preserving its proportions and artwork. Visual inspection confirms this is a full-color logo on a white background despite its filename; retain a white logo area. Generated preview marks are placeholders and must not be recreated or shipped as the SIC logo.

- Name: Social Impact Catalyst (SIC) - CIT-U Chapter.
- Primary Azure: #1FA7E3; Light Azure: #5ABDE7; Accent Orange: #DE7C40; Neutral Grey: #787878.
- Typography: Montserrat and Helvetica Now with suitable fallbacks. Font files and licensing availability remain to be verified.
- User-requested character: a modern, premium social impact platform with strong visual storytelling, clean information architecture, meaningful data visualization, and intuitive interaction; avoid a generic university portal or SaaS dashboard treatment.

These are supplied brand constraints, not a newly established design system.

## Evidence on Hand

- `ASSETS/SIC BRAND BIBLE.pdf`: organizational purpose and brand guidance.
- `ASSETS/SIC-LOGO-WHITE.png`: supplied SIC logo.
- `ASSETS/CIT-U LOGO.png`: supplied university logo.
- User-confirmed product scope and development constraints captured in this record.

Verified project statistics, partner lists, event records, photographs, impact stories, mission/vision/goals copy, blog articles, and application links have not yet been supplied. Use realistic development placeholders clearly distinguished from actual university data. Do not fabricate public claims, partnerships, achievements, or endorsements.

## Product Principles

1. Make meaningful participation easy to discover and act on.
2. Connect university-wide contributions while preserving SIC's dedicated identity and publications.
3. Ground public impact reporting in reviewed records and transparent metric definitions.
4. Validate complete local workflows before adding cloud infrastructure.
5. Keep participation and administration accessible, understandable, and maintainable.

## Accessibility & Inclusion

Target WCAG 2.2 AA, including semantic HTML, keyboard navigation, accessible forms and validation, sufficient color contrast, and mobile-first responsive layouts across phones, tablets, and desktop devices. Apply supplied brand colors in combinations that meet the accessibility target.
