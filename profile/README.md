# Krypto Industries

[![website]: #](#) [![team]: #](#) [![license]: #](#)

Krypto Industries is a creative technology studio building software, video games, and digital media. We design and ship studio-owned engines, tools, games, and media assets with a focus on craft, security, and player experience. We build our own proprietary game engines and core runtime systems — we do not rely on public game engines for our primary projects.

Table of Contents
- About
- Mission & Vision
- What we build
- Studio-owned engines & tech approach
- Private-first development & open-source roadmap
- Core values
- Technology & stack
- Internal workflows (what contributors should know)
- Recommended repo structure
- Contributing (how to engage now and later)
- Code of Conduct
- Security & responsible disclosure
- License
- Contact & community
- Changelog

---

## About
Krypto Industries builds interactive entertainment, developer tools, and production-quality digital media. Our engineering teams design and maintain studio-owned game engines, runtimes, and pipelines that power our games and tools from the ground up. This lets us optimize performance, tailor feature sets to our creative needs, and control our technical roadmap.

## Mission
To make delightful, trustworthy experiences and high-quality development tools that empower creators and players alike.

## Vision
To combine creative storytelling, strong engineering, and privacy-by-design so creators can ship experiences that scale and players can enjoy with confidence.

## What we build
- Proprietary game engines and runtime systems tailored for our gameplay, rendering, and networking needs.
- Engine middleware: asset pipelines, animation systems, audio middleware, and platform integration layers.
- Games & experiences: prototypes, single-player and multiplayer titles, and interactive media powered by our engines.
- Production tools: build systems, CI helpers, asset importers/converters, live-ops tooling.
- Media & content: trailers, cinematics, music, and promotional assets.

Note: Major products and engines are developed internally. When components become generic, stable, and safe to share, we will consider publishing them as open-source or shared SDKs.

## Studio-owned engines & tech approach
- In-house engines: We design our own rendering, physics, animation, and network stacks to meet our creative and performance goals.
- Extensibility: Engines include plugin systems and scripting layers so teams can iterate quickly while preserving core performance.
- Platform targets: We optimize for the platforms relevant to each project (PC, consoles, mobile, cloud).
- IP & protection: Proprietary engines are core studio IP and are developed privately until we decide a component is suitable for external release.

## Private-first development & open-source roadmap
- Private-first: We iterate privately to protect design and IP while stabilizing APIs, tests, and documentation.
- Selective OSS: When engine subsystems, CLI tools, or small SDKs are broadly useful and well-documented, we'll open-source them.
- Roadmap: We maintain an internal Open Source Roadmap and will publish timelines and licensing choices when we prepare a public release.

## Core values
- Player-first design and accessibility.
- Craftsmanship in engineering and art.
- Security & privacy by default.
- Collaboration across design, engineering, and production.
- Iteration and experimentation.
- Respect for intellectual property and responsible sharing.

## Technology & stack
- Engines: Proprietary, studio-built engines and runtime systems.
- Languages: C++, Dart, Swift, Go, Java.
- Rendering & tools: Custom renderer pipelines, Blender, Substance, in-house tools for shader/asset workflows.
- Audio: Custom audio systems and integrations with middleware where needed.
- Backend: Kubernetes, Docker, PostgreSQL, Redis, gRPC, bespoke multiplayer services.
- CI/storage: Git LFS for large assets, GitHub Actions or internal CI, artifact storage for builds and test assets.
- Distribution: Native installers, platform-specific packaging systems, and partner integrations.

## Internal workflows (what contributors should know)
- Private repositories often hold engine source and large binary assets; we use Git LFS and artifact storage.
- Branch naming: `feat/`, `fix/`, `chore/`, `docs/`.
- Pull requests: Provide playtest instructions, recordings, or screenshots for gameplay changes and performance notes for engine changes.
- Engine changes: Follow the engine's stability policy — breaking API changes require review, deprecation planning, and migration guides.
- Tests: Unit tests for tools and systems, automated integration tests for critical engine subsystems, and playtests where applicable.

## Recommended repository structure
- README.md
- CONTRIBUTING.md
- CODE_OF_CONDUCT.md
- SECURITY.md
- LICENSE
- /docs
- /design (GDDs, technical design docs, API contracts)
- /engine (engine source or references)
- /assets (or LFS pointers)
- /project or /src
- /ci (.github/workflows or internal CI)
- /examples /demos
- /tests /playtests

## Contributing (how to engage now and later)
- Today: Most core engine and game repos are private. For collaboration, contracting, or employment opportunities, contact us (see below).
- Future public repos: When we publish repos, follow the repository's CONTRIBUTING.md. Typical expectations:
  - Branch or fork, create focused changes, include tests and docs.
  - Use branch naming conventions and reference issue numbers.
  - Provide screenshots, videos, or benchmark results for engine or gameplay changes.
  - Respect asset licensing and third-party content terms.

## Code of Conduct
We require respectful, behavior across all projects and communication channels. Refer to CODE_OF_CONDUCT.md for details on expected conduct and reporting.
      
## Security & responsible disclosure
If you discover a security vulnerability:
- Do not open a public issue.
- Follow the instructions in SECURITY.md to report privately. Provide reproduction steps and impact assessment.
- We will acknowledge receipt and coordinate a response.

## License
Code and assets are subject to the license included in each repository. Proprietary engine and game repositories remain under internal/studio licenses until we opt to publish components under an open-source license (MIT, Apache-2.0, or otherwise) with clear usage terms.

## Contact & community
- Website: https://kryptoindustries.com
- General contact: contact@kryptoindustries.com
- Security: security@kryptoindustries.com
- Hiring / collaboration: jobs@kryptoindustries.com
- Socials:
- GitHub org: [https://github.com/krypto-industries](https://github.com/Krypto-Industries)

---

Changelog
- 2025-10-24 — Clarified that Krypto Industries builds our own proprietary game engines and updated technology and workflow sections to reflect studio-owned engine development.
