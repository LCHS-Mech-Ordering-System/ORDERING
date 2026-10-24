Work Order Project README.MD
Proprietary software. Built for the École Secondaire Lacombe Composite High School Mechanics/Automotive program community. Students, teachers, staff, faculty, and members of the public may use the running app, but no one has any right to the source code. See EULA and LICENSE document(s). This repository is not open source. Subject to Copyright terms set out in the See EULA and LICENSE document(s).
 © 2026. Wyatt Oehlerking. ALL RIGHTS RESERVED.
Overview
[One or two sentences: what this app does and who it is for.]
Features
Submit, create, and assign work orders
Track status and history
Potential for billing purposes and parts ordering
Instructor assign and approve work performed by student technicians assigned
Tech Stack
Layer
Technology
Frontend
HTML, GitHub Pages & Repository
Backend
Cloudflare Worker
Database
Supabase, AWS Canada Central Server
Hosting
GitHub Pages and applicable domain provider(s)

Getting Started
Prerequisites
Requires HTML and HTTPS Support in the browser, network, firewall and security measures.
Cloud & Internet Access Required, Support from current, future and past infrastructure
Setup
Visit the website at the disclosed URL. It may be listed in releases, commits and applicable sections of the GitHub repository, linking sites, etc.

Clients must create accounts; students must as well, with the encouraged “Sign in with Google [account]” option.

Teacher accounts must be created in the database, transferred by the previous teacher or equivalent or delegated head of the system/program.

Configuration
All secrets and environment-specific values live in a local .env file, which is git-ignored and must never be committed. Copy .env.example and fill in your own values. Backend secrets stay server-side; only public keys may be exposed to the client.
Project Structure
.
├── LICENSE
├── README.md
├── .gitignore
└── project files such as index.html and src/worker.js file

Contributing
This is a closed-source project and does not guarantee acceptance or authorization of outside contributions. Forks, copies, and self-hosted instances are not permitted. For inquiries, donations and input/feedback. Please submit to the owner, contact, maintainer or equivalent listed: Oehlerkingwyatt@gmail.com
License
Copyright © 2026 Wyatt Oehlerking. All Rights Reserved. Free use of the hosted app is granted to every user (students, teachers, staff, faculty, and the public), with no rights to the source code. See EULA and LICENSE document(s).

