# Paris Under Pressure · Team 4

**STEM Link Session 2** · Feature proposal, user journeys and wireframes

Paris Under Pressure is an incident reporting app for a fictional Paris. Residents and shopkeepers can report injuries and shop damage with a location and photo or video evidence. Support services, such as healthcare dispatch and ambulance teams, use it to check reports and send the right team. Government officials get a desktop dashboard showing serious cases, repeated incidents and estimated damage, so they can decide where to act. It works on mobile for reporting and on desktop for officials.

This repo holds everything our team produced for the brief. No code was required.

---

## Team

| Name | Role |
|---|---|
| Nadev | Project manager |
| Mahesh | Stakeholder (client relationship) |
| Adrina | Business analyst + client support |
| Sajath | Business analyst |
| Nethmi | UI / UX (design lead) |
| Hiruna | UI / UX |

---

## Deliverables

### Task 1: Feature proposal

| Document | Author |
|---|---|
| [Feature proposal](docs/task-1-feature-proposal.docx): app description, feature table, limits and assumptions | Sajath |

### Task 2: User journeys and wireframes

| Journey | Write-up | Wireframes |
|---|---|---|
| 1. Sign up and access | [journey-1-signup](docs/journey-1-signup.docx) · Adrina | [journey-1-signup.png](wireframes/journey-1-signup.png) · Nethmi |
| 2. Report an injured person | [journey-2-injury](docs/journey-2-injury.docx) · Adrina | [journey-2-injury.png](wireframes/journey-2-injury.png) · Hiruna |
| 3. Report shop vandalism | [journey-3-vandalism](docs/journey-3-vandalism.docx) · Sajath | [journey-3-vandalism.png](wireframes/journey-3-vandalism.png) · Hiruna |
| 4. Government dashboard | [journey-4-dashboard](docs/journey-4-dashboard.docx) · Sajath | [journey-4-dashboard.png](wireframes/journey-4-dashboard.png) · Nethmi |

Each journey follows the worksheet format: user and goal, starting point, main flow in order, one exception and how the user carries on, end result, and screens to sketch. In the wireframes, solid arrows are the main path and dashed arrows are the exception.

All four journeys are also in one editable file: [team4-wireframes.excalidraw](excalidraw/team4-wireframes.excalidraw) · Nethmi. To view or edit it, download it and open it at [excalidraw.com](https://excalidraw.com) (☰ menu → Open).

---

## Sample case

We used one made-up story across all four journeys, so they read as one evening on one street:

- **Rue des Lilas, Friday 7:40 PM**
- **Léa** (shopkeeper) signs up (Journey 1) and reports her smashed shop window as **PU-028** (Journey 3)
- **Amir** (resident) finds an injured man at the bus stop and reports it as **PU-027** (Journey 2)
- **Camille** (government official) sees both on her dashboard, sends a team to PU-027 and flags Rue des Lilas as a repeated area (Journey 4)

All people and incidents are fictional, as in the brief.

---

## Key decisions

| Topic | What we decided |
|---|---|
| Platform | Mobile-friendly app for people reporting, desktop dashboard for officials |
| Users | Residents, shopkeepers, support services (healthcare dispatch, ambulance, police, fire), government officials and government IT desk staff. Insurance companies come later |
| Sign-up checks | Email and strong password, NIC or passport, business registration for shops, a utility bill from the last 6 months and a 10-second live ID video. New accounts stay Pending until government IT desk staff approve them |
| Trust | Evidence is photos and videos. The nearest police officer adds an on-site photo before the support service approves a case |
| Severity | Normal cases go to the nearest police officer. Critical cases go to fire service, police and ambulance |
| Duplicates | A warning shows similar nearby reports before sending. The reporter can add their details to the existing case or send a new one |
| Dashboard | Shows serious cases, repeated incidents and estimated damage. Officials can send teams, flag an area for action and mark a case Not found with a reason |
| Languages | French and English |

Where the brief left things open, our assumptions are listed in the feature proposal (Part C).

---

## Folder guide

```
docs/         Task 1 and the four journey write-ups
wireframes/   One PNG per journey
excalidraw/   Editable Excalidraw file with all four journeys
notes/        Kickoff decisions, client meeting notes and client answers
```

---

## How we worked

- Kickoff session to agree on users, platforms, sign-up checks and evidence rules ([kickoff decisions](notes/kickoff-decisions.md))
- Client requirement meeting (Mahesh and Adrina), then decisions updated from the client notes ([meeting notes](notes/client-meeting-notes.pdf), [client answers](notes/client-answers.md))
- Each member worked on their own branch and opened a pull request, merged into `main` by the project manager
- Final review of every write-up against its wireframes before submission
