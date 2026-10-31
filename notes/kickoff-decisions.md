# Kickoff session · Finalized decisions

Team 4 · Paris Under Pressure · STEM Link Session 2

Text version of [kickoff-decisions.pdf](kickoff-decisions.pdf), so it can be read directly on GitHub. Some of these were refined after the client meeting. The final versions are in the documents in `docs/`.

---

### Web, mobile or both
- **Idea to start with:** One mobile-friendly web app for residents, shopkeepers and responders, and a desktop dashboard for officials.
- **Our final answer:** Both interfaces need to be supported.

### User types
- **Idea to start with:** Resident, shopkeeper, support service responder, government official.
- **Our final answer:**
  - High-level user: Shopkeeper
  - Low-level user: Resident
  - Admin: Support service

### How we show a report can be trusted
- **Idea to start with:** Every report is unverified until an official checks it, then it becomes confirmed.
- **Our final answer:** The nearest police station member goes to the location, takes a picture of the damaged place and adds it to the user's case report, and the support service approves the case. We also add rules for evidence (rules for videos and pictures, avoiding other user inputs completely).

### First version features
- **Idea to start with:** Sign-up, injury report, vandalism report, duplicate flag, official dashboard, responder case list with Case Resolved.
- **Our final answer:** The normal sign-up and sign-in procedure, collecting the necessary documents when the user signs up: National ID, passport, business registration, utility bills paid in the last 6 months, and insurance certificates or documents if any. During sign-up, the user also uploads a short 10-second live video (mobile app or web) holding their NIC or passport, which must be clearly visible.

### Exception for each journey
- **Idea to start with:**
  - Journey 1: account not approved yet
  - Journey 2: location unknown or location access off
  - Journey 3: no photo or cost not known
  - Journey 4: two officials updating the same case
- **Our final answer:** Notify the user by email or SMS about invalid inputs, missing inputs or wrong file sizes, with a warning at the input box when the maximum file size is exceeded (this applies to Journeys 1 to 4). If two users update the same scenario, check the documents collected at sign-up and the 10-second ID video to confirm who the real user is. The ID video takes time at sign-in, and an account still marked as rejected must be finalized as accepted or rejected.

### Sample case
- **Idea to start with:** One made-up case with the same ID, street and time in every journey.
- **Our final answer:** If one user sends duplicates, check the latest incident and the one with the most accurate inputs. If both are valid, the case is approved. If two users report the same scenario, verify who the actual user is.

### GitHub setup
- **Idea to start with:** Branch names `yourname-task`, folders `docs` / `wireframes` / `notes`, Nadev merges into `main`.
- **Our final answer:** GitHub process started, used as evidence of each member's contribution and for version control.

### Tools
- **Idea to start with:** Excalidraw for drawings and one shared folder.
- **Our final answer:** After the client requirements are finalized (the stakeholder contacts the client the next day to verify their expectations), the user flow, finalized requirements and functional and non-functional requirements go into the Excalidraw space.

### Check-in times
- **Idea to start with:** Wednesday and Thursday night, longer review on Friday.
- **Our final answer:** After the client meeting (run by the stakeholders), arrange a meeting to discuss next steps.

### Who submits
- **Idea to start with:** Nadev
- **Our final answer:** Not decided at kickoff.
