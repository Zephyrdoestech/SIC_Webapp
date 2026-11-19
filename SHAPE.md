# SIC website planning brief

Status: Planning brief confirmed by the user. Campus assembly programme (the card labeled THE ROLL) selected, with the actual supplied SIC logo required. Proceed to the comp workflow and then local implementation. No direction contract is included here.

## Job and audience

Help Teknoys find an initiative and take part. The public homepage is Persuade; initiative discovery and administrative workflows are Operate; organizational information and publications are Read.

## Outcome and evidence

Primary journey: discover an initiative -> inspect activity details -> follow its registration link. Approved organization records support public impact reporting. All prototype events, statistics, and stories must be visibly identified as demonstration content. Existing evidence is limited to the brand bible and supplied logos.

## Selected direction

Campus assembly programme: a date-led programme of student action, with visible SDG filters, organizer details, and activity actions. Preserve the selected preview's broad composition: branded opening and date-indexed agenda, followed by an explanation of how reviewed contributions become shared impact. The focal moment is finding a relevant activity within the opening programme.

Reference: `.impeccable/mocks/decision/assembly.png`. This is the selected direction preview, subject to the user's logo correction; generated text, imagery, and marks are not approved factual content or final assets. Use `ASSETS/SIC-LOGO-WHITE.png` unchanged in a white logo area: inspection confirms full-color artwork on white, despite the filename. Do not redraw it. Keep the supplied brand colors and typography; ensure readable contrast in the eventual implementation.

The public programme language extends to dates, activity listings, and editorial section headings. Working screens use clear forms, status lists, and review controls rather than decorative programme treatments.

## Proposed sitemap

| Area | Screens and content |
| --- | --- |
| Home | Initiative discovery, upcoming opportunities, reviewed-impact explanation, stories, participation links |
| Explore | Searchable projects/events, date/SDG/organization/status filters, activity details |
| Impact | Approved-record statistics, SDG coverage, links to contributing records |
| Stories | Event highlights and SIC blog, with separate categories and detail views |
| About SIC | Background, mission, vision, goals, advocacy, membership redirect |
| Partnerships | Verified collaborations when available, validated inquiry form |
| Organization workspace | Own submissions, create/edit draft, preview, submit, revision feedback, resubmit |
| SIC administration | Review queue, record review, request changes, approve, publications and impact-record management |
| Supporting screens | Local registration demo, feedback, not found, access denied |

## User flows

1. Visitor: home programme -> filter/search -> activity details -> external registration. Missing real links lead to an explicitly labeled local demonstration, never a claim of actual registration.
2. Representative: simulated organization role -> own records -> draft -> validation and preview -> submit -> read review status. Changes requested -> revise -> resubmit.
3. SIC administrator: review queue -> inspect submission -> request changes with feedback or approve -> approved record becomes publicly eligible. Approval and event completion are distinct states.
4. Reader: stories -> event highlight or SIC publication -> related initiative or participation opportunity.
5. Potential partner: partnerships -> inquiry -> validation -> clearly simulated local confirmation.

## Wireframe intent

- Desktop homepage: clear identity/navigation; short participation introduction beside the dominant date-indexed programme; filters above activity rows; each row exposes title, organizer, date, SDGs and View activity. Below: reviewed-impact explanation, selected stories and participation links.
- Mobile homepage: identity/menu, concise introduction, filters, then stacked event rows; no horizontal scrolling required to find the activity action.
- Activity detail: title and status, organizer, date/location, purpose and SDGs, participation information, registration action, related records.
- Workspace: role and organization context, status-filtered list, edit/preview flow, visible save/submit feedback, review notes near fields needing correction.
- Admin review: submission details and review history before explicit approve/request-changes actions; preserve entered feedback on validation failure.

## States and representative ranges

Prototype coverage should include zero results, one result, and multiple pages of records; long titles, multiple SDGs, absent images and missing dates. Fixture quantities are test coverage, never university statistics.

Cover initial, loading, empty, no-match, validation-error, save-error, success, access-denied, missing-record, draft, submitted, changes-requested and approved states. Treat upcoming/ongoing/completed as activity lifecycle values distinct from review status. Provide search reset, clear status text, and retry paths where relevant.

## Boundaries and open decisions

React/Vite/Tailwind; local JSON/localStorage and simulated roles; modular data access; WCAG 2.2 AA target; responsive keyboard-accessible forms and navigation. No cloud integration or deployment in this phase. The future local prototype must cover the complete public and administrative scope.

Still to resolve during detailed planning: counting rules and deduplication for impact metrics, edits to approved records, detailed publication permissions, exact fields and attachment limits, actual registration/membership destinations, verified content, and font availability. No invented organizational policies or public claims.

Next stage after brief confirmation: detailed wireframes and the approved-comp workflow before frontend implementation. Shape stops at planning.
