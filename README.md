# Internet-ID

**Internet-ID** is a full-stack content provenance platform that helps creators prove authorship and gives viewers a way to verify where digital content came from.

For employers and recruiters, this project is a strong example of the kind of work I enjoy building: product-minded software that combines **blockchain engineering, backend systems, security, and user-facing tooling** into one practical solution.

## What this project demonstrates

- **Smart contract development** with Solidity, Hardhat, TypeScript, and upgradeable contract patterns
- **Full-stack product delivery** across an Express API, Next.js web app, Prisma data layer, and browser extension
- **Production-minded backend design** with validation, rate limiting, background jobs, Redis caching, and monitoring hooks
- **Security-focused implementation** using OpenZeppelin, input sanitization, authentication flows, CSP, and automated scanning
- **Developer experience and quality practices** including CI workflows, testing, formatting, and Docker-based environments

## Key accomplishments

- Built an end-to-end workflow for hashing content, creating signed manifests, anchoring provenance on-chain, and verifying results off-chain
- Added support for multiple EVM-compatible networks and upgradeable deployments
- Extended the product beyond contracts with API endpoints, async verification queues, database-backed services, and a browser extension for verification on supported platforms
- Structured the repository as a realistic engineering project with documentation, deployment scripts, and operational tooling

## Technology snapshot

**Solidity · Hardhat · TypeScript · Ethers · Express · Next.js · Prisma · Redis · BullMQ · OAuth/NextAuth · Docker · GitHub Actions**

## Why it matters

Internet-ID tackles a timely problem: helping people distinguish opted-in, human-created content from anonymous or manipulated media. It is intentionally more than a contract demo—it shows how I approach building complete, secure, maintainable systems around a clear product need.

## Explore the project

- [Architecture overview](./docs/ARCHITECTURE.md)
- [Contributor onboarding](./docs/CONTRIBUTOR_ONBOARDING.md)
- [User documentation](./docs/user-guide/INDEX.md)
- [Browser extension](./extension/README.md)
