# Skill: Creator Event Operations Project Management

## Purpose

Use this skill to help a user plan and manage an offline creator / influencer event from scratch.

The skill should output a complete project management workflow and a usable spreadsheet structure covering:

1. WBS master project management
2. Event rundown
3. Venue and on-site flow
4. Creator list and invitation pipeline
5. Budget tracker
6. Team duty roster and rehearsal checklist
7. Seating chart

The audience may have never hosted an event before, so explanations must be concrete, step-by-step and operational.

---

## When to use

Use this skill when the user asks for help with:

- creator / influencer event planning
- offline brand event execution
- creator awards ceremony
- creator relationship maintenance event
- brand dinner / private dinner
- panel + awards + dinner event
- event execution spreadsheet
- WBS / project management for marketing events
- event budget control
- creator invitation list
- seating chart for creator events

---

## Required inputs

Ask for or infer the following:

- Event objective
- Event date and city
- Expected guest count
- Creator type / vertical
- Brand / platform goal
- Rough budget
- Whether travel and hotel are included
- Whether there is a dinner
- Whether there are awards, panels, speeches, photo wall, tea break, raffle, gifts
- Team size and available owners

If some inputs are missing, create a template with placeholders.

---

## Output structure

Always organize the answer in this order:

### 0. WBS Master Control

Explain that WBS is the master project management layer. It should control:

- phases
- workstreams
- tasks
- outputs / acceptance criteria
- deadlines
- owners
- stakeholders
- priority
- status
- risks

Recommended phases:

1. Kick-off
2. Rundown
3. Venue
4. Creator list
5. Budget
6. Production / materials
7. Travel / hotel
8. On-site duties
9. Rehearsal
10. Event day
11. Post-event review

### 1. Confirm the event rundown

Explain that the rundown must come from the event objective.

Example:

If the objective is to maintain relationships with long-term brand creators, give them recognition, deepen exchange, and announce next-year brand moves, the event can include:

- awards ceremony for recognition
- panel discussion for exchange and shared industry direction
- premium Michelin / fine dining dinner for social bonding

For each segment, include:

- time
- duration
- activity
- objective
- what happens on site
- vendor / setup needs
- ops materials
- staffing needs
- owner
- risks / checks

### 2. Confirm the venue

Explain that vendors may provide venue and dinner options, but the operator must visit the site in person.

The venue sheet should compare:

- venue name
- address / area
- capacity
- quote
- included equipment
- pros
- cons / risks
- distance from hotel / dinner
- site visit notes
- decision
- owner

The site visit checklist must include:

- drop-off point
- entrance
- sign-in desk
- photo wall
- main room
- stage
- LED / projection
- microphones / sound
- awards staging area
- tea break area
- restrooms
- elevator
- camera positions
- material storage
- vendor loading path
- transport pick-up point
- dinner entrance
- rain plan
- delay / overtime plan

Make clear that the user should walk through the space as:

1. a creator
2. a VIP / brand guest
3. a staff member

### 3. Confirm the creator list

The creator list must include screening criteria:

- data: followers, recent average views / impressions, engagement, growth, past collaboration performance
- content style: visual quality, tone, narrative, fit with event/brand
- relationship depth: long-term collaborator, strategic creator, new prospect
- brand / event fit: relevance to next-year brand direction, category, audience
- brand safety: controversy, commercial risk, compliance, public sentiment

Priority rules:

- P0: strong data + strong style fit + important relationship + high brand fit
- P1: hits 2-3 key indicators
- P2: useful but not essential
- Backup: used for backfill

Invitation rounds:

1. Initial longlist
2. Round 1 soft invite: check interest, date availability, travel needs
3. Round 2 invite and backfill
4. Final invitation letter with full event details

Final invitation must include:

- event name
- date and time
- venue
- event highlights
- why this creator is invited
- travel / hotel arrangement
- dress code
- whether plus-one is allowed
- point of contact
- RSVP deadline

### 4. Confirm the budget

Explain that budget can be pre-split if the user already has a rough total, but the final budget should be locked after the creator list, venue and rundown are mostly clear.

Budget categories:

- venue
- dinner / catering
- travel
- hotel
- production / build
- materials
- awards
- gifts
- vendors
- contingency buffer

Budget table fields:

- category
- sub-category
- planned budget
- forecast
- actual
- variance
- payment method
- payment status
- handler
- vendor / payee
- contract / invoice
- notes

Tips:

- keep 10%-15% contingency
- dinner costs often hide service fee / alcohol / corkage / minimum spend
- travel costs fluctuate
- every extra request must have an owner and source of budget

### 5. Confirm team duties and rehearsal

Break the event into roles:

- Project Owner
- Stage Manager
- Reception Lead
- Creator Liaison
- VIP / Brand Liaison
- Award Lead
- Panel Lead
- AV / Control Lead
- Photo / Video Lead
- Vendor Lead
- Transport Lead
- Dinner Lead
- Emergency Owner

Each role should include:

- owner
- backup
- time
- location
- responsibility
- materials / tools needed
- success criteria
- risks
- status

Rehearsal checklist:

- host script
- PPT / video / audio
- microphone switching
- awards stage movement
- panel seating and mic handoff
- sign-in simulation
- photo wall and group photo
- tea break flow
- transport handoff
- dinner entry
- raffle
- emergency plan

### 6. Seating chart

Explain that seating is relationship design.

The seating chart should consider:

- VIP and brand priority
- creators who should meet each other
- creators who should not sit together
- mix of content verticals
- relationship closeness
- table captains
- dietary needs
- plus-ones
- people who need to go on stage
- people who may arrive late / leave early

Seat number should connect to:

- table card
- wristband
- raffle number
- transport card
- sign-in sheet
- staff lookup sheet

---

## Writing principles

- Do not assume the user knows event operations.
- Avoid vague advice.
- Every recommendation should be operational.
- Prefer tables and checklists.
- Explain why each sheet exists.
- Include concrete examples.
- Use a professional but readable tone.
- Make the system feel reusable and GitHub-friendly.

---

## Suggested artifact names

- `creator_event_pm_workbook_bilingual.xlsx`
- `README.md`
- `skill.md`
- `prompts/event_ops_prompts.md`

