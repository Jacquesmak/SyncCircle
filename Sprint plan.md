# FamSync Calendar MVP – Windsurf Sprint Plan

**Team**: 1 PM, 1 Designer, 2 Frontend, 2 Backend, 1 QA  
**Duration**: 4 Sprints (1 week each)  
**Framework**: Windsurf Agile  
**Goal**: Deliver a usable MVP for family/friend calendar sharing and syncing

---

## 🧭 Weekly Windsurf Rhythm

| Day        | Activity                          |
|------------|-----------------------------------|
| Monday     | Sprint Planning + Goal Setting    |
| Tuesday    | Build Focus (Heads-down)          |
| Wednesday  | Midweek Demo + Internal Feedback  |
| Thursday   | Refinement + Bug Fixes            |
| Friday     | Show & Tell + Retrospective       |

---

## ✅ Sprint 1: Foundations & Auth

**Goal**: Enable user auth and group creation

### Features
- Email + Google OAuth login
- Create/join/view groups
- Calendar visibility settings (full, busy/free, custom)
- Backend schema + scaffolding

### Deliverables
- Working auth and group modules
- API structure defined
- Internal demo of group creation and roles

### Risks
- OAuth token handling complexity

---

## ✅ Sprint 2: Calendar Sync & Event Creation

**Goal**: Enable shared event creation and availability sync

### Features
- Create/edit/delete events
- RSVP tracking
- Google Calendar 1-way sync
- Merged group calendar view

### Deliverables
- Synced events with availability logic
- Conflict detection in scheduling
- Internal “dinner planning” test case

---

## ✅ Sprint 3: RSVP, Polling, and Group Features

**Goal**: Enable interactive coordination tools

### Features
- Availability polling UI
- RSVP management
- Email + in-app notifications
- Group permissions (admin/editor/viewer)

### Deliverables
- Functional poll scheduling flow
- Notifications on event changes
- User role enforcement

---

## ✅ Sprint 4: Polish, QA & Beta Launch

**Goal**: Deliver a polished MVP to beta users

### Features
- Mobile responsiveness
- Error states + input validation
- Unit/integration/smoke tests
- Friend invite system (link or email)

### Deliverables
- Deployed beta version
- Full test plan passed
- Live test groups on app

---

## 🚀 Post-Sprint 4: Beta Feedback & Planning

**Next Steps**
- Usage analytics (event creation rate, RSVP activity)
- Beta interviews
- Prepare v1.1 roadmap:
  - 2-way calendar sync
  - Recurring events
  - Location-aware alerts
