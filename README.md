## whoami

Computer Systems Engineering student specializing in DevOps.

I mostly work on audio plugins (VST3) in C++ with JUCE, backend services with Node.js and PostgreSQL, and CI/CD with automated testing.

---

## What I do

**Audio and C++**
- Audio DSP: dynamics, oversampled saturation, filtering, soft clipping and loudness measurement (BS.1770 K-weighting).
- Plugin interfaces in JUCE: custom `LookAndFeel`, meters, real-time visualizations and resizable layouts.
- Plugin state and presets: file formats, crash-safe saves and renames, A/B comparison.

**DevOps, CI and testing**
- CI/CD with GitHub Actions: builds, unit tests and plugin validation for C++ audio code, API tests against a temporary PostgreSQL service container, and releases from version tags.
- Deployment with Nginx as a reverse proxy over HTTPS, serving a React build and forwarding the API and WebSocket traffic, with setup guides for Windows and Ubuntu.
- End-to-end tests with Playwright, API tests with Node's test runner and Supertest, and concurrency tests that force real race conditions through database locks.
- CMake build systems, including reading a project's real configuration through CMake's File API, and PowerShell build scripts.

**Backend**
- REST APIs with Node.js and Express on PostgreSQL: schema design, least-privilege database roles, and payment and audit records the application can't alter.
- Authentication and authorization: JWT sessions in httpOnly cookies backed by the database so they can be revoked instantly, bcrypt password hashing, role-based permissions and login rate limiting.
- Real-time updates with Socket.IO that only announce what changed, so each screen re-reads the data through the API and its permission checks.
- Hardware integration: printing tickets on network thermal printers with ESC/POS.

**Frontend**
- React frontends connected to REST APIs: typed clients, error handling, retries and idempotency keys.
- Tablet-friendly interfaces with menus driven by user permissions, client-side validation with unit tests, and maps with geolocation.

**Teamwork**
- Feature branches and pull requests with code review, issue tracking, and turning tester feedback into bugs and tasks.
- Project documentation: architecture, database diagrams, contribution guides and changelogs.

---

## Tech Stack

<div align="center">

**Audio and C++**

[![C++, CMake, Visual Studio, Windows](https://skillicons.dev/icons?i=cpp,cmake,visualstudio,windows&theme=dark)](https://skillicons.dev)

![JUCE](https://img.shields.io/badge/JUCE-e0245e?style=for-the-badge)
![VST3](https://img.shields.io/badge/VST3-e0245e?style=for-the-badge)
![pluginval](https://img.shields.io/badge/pluginval-e0245e?style=for-the-badge)

**Backend**

[![Node.js, Express, PostgreSQL](https://skillicons.dev/icons?i=nodejs,express,postgres&theme=dark)](https://skillicons.dev)

![Socket.IO](https://img.shields.io/badge/Socket.IO-e0245e?style=for-the-badge)

**DevOps and Tools**

[![GitHub Actions, Nginx, PowerShell, Git, GitHub, VS Code, Obsidian](https://skillicons.dev/icons?i=githubactions,nginx,powershell,git,github,vscode,obsidian&theme=dark)](https://skillicons.dev)

![Playwright](https://img.shields.io/badge/Playwright-e0245e?style=for-the-badge)

**Frontend**

[![React, JavaScript, TypeScript, Vite, Vitest, Tailwind](https://skillicons.dev/icons?i=react,js,ts,vite,vitest,tailwind&theme=dark)](https://skillicons.dev)

**Also**

[![Java, Python](https://skillicons.dev/icons?i=java,py&theme=dark)](https://skillicons.dev)

</div>

<!-- Contacto: cuando tengas el correo, cambia PUBLIC_EMAIL y quita los marcadores de comentario de este bloque.

---

## Contact

<div align="center">

[![Email](https://img.shields.io/badge/Email-Contact-e0245e?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0d1117)](mailto:PUBLIC_EMAIL)

</div>

-->
