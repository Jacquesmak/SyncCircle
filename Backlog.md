# 📆 FamSync Calendar App – Product Backlog

## Overview
A calendar-sharing app designed for **friends and family** to view availability, coordinate group events, and sync with personal calendars.

---

## 🧱 Epics

### E1. User Authentication & Profiles
- US101: User registration via email, Google, or Apple login
  - Implement secure auth with JWT
  - OAuth2 for Google/Apple
  - Forgot password flow
- US102: Profile editing (name, avatar, time zone)
  - Avatar upload support
  - Store user preferences

---

### E2. Group Creation & Permissions
- US201: Create groups and invite users
  - Email invite + unique invite link
- US202: Manage member roles (admin/editor/viewer)
  - Role-based access control in DB + UI
- US203: Leave or delete group functionality

---

### E3. Calendar & Event Management
- US301: Create and edit group events
  - Recurrence support (RRULE)
  - Time zone awareness
- US302: RSVP to events
  - Track "Yes / No / Maybe" responses
- US303: Propose and vote on times
  - Poll-based availability
  - Conflict-aware suggestions

---

### E4. External Calendar Integration
- US401: Sync Google Calendar
  - OAuth2 flow, calendar listing, permissions
  - Choose 1-way or 2-way sync
- US402: View synced events in FamSync
  - Render external events with correct formatting
- US403: Push edits back to Google if 2-way enabled

---

### E5. Availability Sharing
- US501: Set calendar sharing level
  - Options: Full, Busy/Free, Custom
- US502: View merged availability of all group members
  - Color-coded time blocks
  - Responsive shared calendar UI

---

### E6. Notifications & Reminders
- US601: Event reminders (push/email)
  - Scheduled jobs (e.g., Firebase, cron)
- US602: Change alerts (RSVPs, edits, cancellations)
  - Notification settings per user

---

### E7. Mobile & Web UI/UX
- US701: Responsive calendar UI
  - Day, week, agenda views
  - Drag-to-create events
- US702: Toggle between calendars (personal, group, merged)
- US703: Light/Dark mode toggle

---

### E8. Admin Console & Analytics (Post-MVP)
- US801: Group usage stats dashboard
- US802: Sync error logs and diagnostics
- US803: Export group events and membership

---

## 🏁 Sprint Plan (10-Week MVP Roadmap)

| Sprint | Focus                               | Epics                |
|--------|--------------------------------------|----------------------|
| 1–2    | Auth system + Group setup            | E1, E2               |
| 3–4    | Event creation + RSVP functionality  | E3                   |
| 5–6    | Availability UI + Notifications      | E5, E6               |
| 7–8    | Google Calendar sync (1-way)         | E4                   |
| 9      | 2-way sync + Mobile polish           | E4, E7               |
| 10     | Admin tools + optional analytics     | E8 (stretch)         |

---

## ✅ Optional Enhancements

- Calendar import/export via .ics
- iCal link generation
- AI assistant for scheduling
- Cross-group event bridging

---

## 🧠 Next Steps

- [ ] Create ER diagram from data model
- [ ] Set up Swagger/OpenAPI spec for REST endpoints
- [ ] Assign story points (1–8 scale)
- [ ] Prioritize MVP tickets for Week 1-2 kickoff
