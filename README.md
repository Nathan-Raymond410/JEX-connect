# JEX Connect

**An AI-assisted networking platform connecting Japanese communities, international visitors, and local organizations.**

> 🚧 **Status: Early development.** This repository documents the plan and tracks progress. Features below are planned unless marked as done.

---

## About

JEX Connect (Japan Exchange Connect) helps people and organizations across Japan and international communities discover one another, meet, and turn conversations into real next steps: collaborations, referrals, internships, partnerships, and community projects.

The first use case is **Speed Meeting events**: structured online or in-person sessions where Japanese participants and international English-speaking participants meet in short rounds. Over time, the platform grows into a full system for matching, follow-up, and tracking outcomes.

### Core cycle

People & organizations → Profiles → Matching & introductions → Meetings & activities → Captured outcomes → Follow-up actions → Better future matching

## Who it's for

- Japanese community members
- International visitors and English-speaking participants
- JEX ambassadors and volunteers
- Local businesses, schools, and community organizations
- Sponsors and business partners

## Planned features

### Phase 1: MVP (current focus)
- [ ] Secure authentication with role-based access (participant, organization, admin)
- [ ] Participant profiles: languages, skills, interests, goals, location, availability
- [ ] Organization profiles: services, needs, and opportunities
- [ ] Event registration
- [ ] Speed Meeting management: cohorts, configurable rounds, and group/room assignments
- [ ] Participant dashboard with schedule and next steps
- [ ] Admin console for users, events, and cohorts
- [ ] Follow-up tasks and basic activity tracking
- [ ] CSV export for event operations
- [ ] Privacy and consent controls

### Phase 2: AI-assisted workflows
- [ ] Explainable match recommendations ("why you two should meet")
- [ ] Summaries of meeting notes (authorized input only)
- [ ] Personalized follow-up suggestions and message drafts
- [ ] Basic outcome analytics

### Phase 3: Business operations
- [ ] Opportunity and referral pipeline
- [ ] Organization subscriptions and sponsorship management
- [ ] Partner reporting
- [ ] External integrations (calendar, email, video meetings)

## First milestone

One complete, testable workflow:

**Sign up → Create profile → Register for event → Get meeting assignments → Record follow-up**

Target: a pilot event with about 20 Japanese and 20 international participants.

## Design principles

- **Simple first.** A maintainable architecture over premature complexity.
- **Transparent matching.** Start with explainable rule-based scoring, not black-box AI.
- **AI assists, humans decide.** No automatic messages, commitments, or data sharing without authorization.
- **Privacy by default.** Collect only necessary data; recording and AI processing are opt-in.
- **Works without AI.** Core event features must function even if AI services are unavailable.

## Planned data model

`User` · `UserProfile` · `Organization` · `OrganizationMembership` · `AmbassadorProfile` · `Event` · `Cohort` · `Registration` · `MeetingRound` · `MeetingAssignment` · `MatchRecommendation` · `MeetingNote` · `FollowUpTask` · `Opportunity` · `Referral` · `Notification` · `ConsentRecord` · `AuditLog`

## Tech stack

To be finalized. This section will be updated as the architecture is set.

## Development

Built with the help of an AI coding assistant (Claude Code). All development uses **test/dummy data only**; no real participant information is stored in this repository.

## Roadmap

| Phase | Focus | Status |
|-------|-------|--------|
| 0 | Audit and architecture planning | 🔄 In progress |
| 1 | Reliable MVP for pilot event | ⏳ Planned |
| 2 | AI-assisted matching and follow-ups | ⏳ Planned |
| 3 | Business and partner tools | ⏳ Planned |

## Author

**Nathan Raymond** · [GitHub](https://github.com/Nathan-Raymond410)

## License

All rights reserved. © 2026 Nathan Raymond
