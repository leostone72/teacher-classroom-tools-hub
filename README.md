# Teacher Tools and Director Dashboard v2026 - web app 2026

> **A browser PWA for classroom and school operations in 2026: teacher utilities, a director dashboard, role-aware access, and workflow-oriented management screens.**

[![Platform](https://img.shields.io/badge/Platform-browser-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/leostone72/teacher-classroom-tools-hub?style=flat-square)](https://github.com/leostone72/teacher-classroom-tools-hub)

---

<p align="center">
  <a href="https://leostone72.github.io/teacher-classroom-tools-hub/">
    <img src="https://img.shields.io/badge/Download-Teacher%20Tools%20and%20Director%20Dashboard%20Latest-brightgreen?style=for-the-badge" alt="Download Teacher Tools and Director Dashboard">
  </a>
</p>

> **[Direct Download - Teacher Tools and Director Dashboard v2026](https://leostone72.github.io/teacher-classroom-tools-hub/)**

---

[Download Latest Build](https://leostone72.github.io/teacher-classroom-tools-hub/)

---

## What this project is

Teacher Tools and Director Dashboard is a web app shell that runs in the browser and gives teachers and directors a clear place to organize school work. Staff see different surfaces by role, with attention on profiles, assignments, scheduling, and curriculum planning.

Day-to-day prototype state stays local in the browser. Protected live data goes through Supabase. Sign-in is email and password, entry is approval-gated, and the shell can be installed as a PWA with offline use.

---

## What you get

- Distinct teacher and director interfaces matched to each role
- Teacher profiles that carry school assignment context
- Partner school cards you can sort for faster scanning
- Tools for schedules and curriculum upkeep
- Message and pay-stub sections reserved for later workflow growth
- Prototype persistence via browser local storage
- Email/password authentication plus approval-based entry
- Installable PWA packaging and offline-capable shell behavior

---

## Installation

Bring down the source (clone or archive), then load the app in a browser that handles modern HTML and PWAs.

1. Clone the repository:
   `git clone https://github.com/leostone72/teacher-classroom-tools-hub.git
2. Enter the project folder:
   `cd dance-techniques-teacher-tools`
3. Launch it in the browser or publish the files on any static host you prefer.

Local checks can use a lightweight static server or direct file opening, depending on how your environment is set up.

---

## Usage

Open the app and authenticate with an approved email/password pair. Because access is role-based, teachers and directors land on different interfaces.

Common path through the product:
1. Complete sign-in on the auth screen.
2. Look over teacher profiles and linked school assignments.
3. Sort partner schools or open schedule information.
4. Adjust curriculum data when your process requires it.
5. Treat messages and pay stubs as stand-in areas for active or upcoming flows.

To work offline, install the PWA from a compatible browser, then start it from the device home screen or app list.

---

## Configuration

Prototype content lives in browser storage; protected live records use Supabase. Exact setup follows your deployment, with most knobs living in the app environment and storage layer.

Example structure:
```json
{
  "auth": "email-password",
  "access": "approval-gated",
  "storage": "localStorage",
  "backend": "Supabase",
  "mode": "PWA offline shell"
}
```

When you ship or customize the project, inspect the HTML and client-side config for auth, storage, and access rules.

---

## Requirements

- Modern browser with HTML5, JavaScript, and PWA capability
- Network connectivity for sign-in and Supabase-backed records
- Local storage turned on so prototypes can persist
- Enough browser storage space for offline shell assets
- A static-hosting-friendly setup if you intend to publish the app

---

## FAQ

**How is access granted?**  
Accounts sign in with email and password, and approval gating means only authorized users can proceed.

**Is offline use supported?**  
Yes. The installable PWA shell is built with offline support.

**Where does data live?**  
Browser local storage can hold prototype data; protected live records stay in Supabase.

**Can layouts or fields be customized?**  
Yes. As a web shell, you can extend structure and workflows by editing the project source.

**Login is failing—what next?**  
Confirm credentials, ensure the account was approved, and check that the browser can reach Supabase-backed services.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
