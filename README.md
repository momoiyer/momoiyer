# 👋 Hey, I'm Momo.

I'm a Senior Software Engineer in Calgary, and I love what I do: writing code and solving hard problems, especially the ones nobody has fully figured out yet.

I'm at my best in startups, where I can own something end to end. I like shaping the design, building the frontend and backend, setting up the infrastructure, shipping it, and looking after it in production. Most recently, I did exactly that for almost three years as a Senior Software Engineer at TOTEC AI Energy, building a full-stack energy software platform.

I'm currently open to senior full-stack, backend, and infra roles.

## 🛠 Work I'm proud of

- **Building production AWS from the ground up.** At TOTEC, I designed and set up the staging and production environments, including networking, Auto Scaling, deployment infrastructure, security, and monitoring. I also built the CI/CD workflows with GitHub Actions, ECR, and CodeDeploy, so releases were repeatable across environments.
- **Shipping real-time features across the stack.** I built live communication and notifications with WebSockets, backend events, and background jobs, and integrated Auth0, Redis/Valkey, SES, SNS, and EventBridge to support them.
- **Turning large, messy data into something people can use.** I designed the database structures and processing workflows for large GeoJSON and Excel datasets, then built the extraction and visualization features for map-based analysis and reporting.
- **Tracing production problems to their real cause.** When notifications started crashing one of our EC2 instances, I tracked it down to a single post triggering a huge number of synchronous notifications. I moved notifications into a separate Node service, so a spike could no longer bring down the main application.
- **Helping junior developers grow.** I love sharing what I know. At TOTEC, I started a monthly training session for our junior developers. When I hand someone a problem, I explain why it matters and then give them the freedom to work out how to approach it. 
- **Leaving things clearer than I found them.** I keep detailed documentation with diagrams, write down my decisions, and present what I learn, so the next person doesn't have to start from scratch.

## 🤖 How I work with AI

I use Claude Code, Codex, Cursor, and Orca to plan, build, and review. On my own projects, the plan lives in the repo, and every task has an owner: the agent, me, or the business owner. Anything hard to undo stays with me, including history rewrites, secrets, CI files, deployment, and DNS.

Decisions get written down as they're made, so the next session starts from the reasoning instead of a guess. Tests, accessibility checks, and dependency audits run on the work, because a confident summary isn't the same as working software.

## 🔨 Things I'm building

Most of this work lives in private repos. I'm happy to walk through any of it.

**Finance OS** — A local-first personal finance dashboard, and what I'm working on now. It imports bank statements into a review grid, learns categorization rules from past transactions, tracks spending against budgets, and generates a monthly payment schedule with email reminders. Built with React Router, TypeScript, Prisma, and PostgreSQL.

**QR Management** — Dynamic QR codes for real estate signs. A printed code never changes, but what it does when scanned can: open a listing, start a text, place a call, or send an email. Every scan is attributed to the action that was live at the time, with analytics, scan alerts, and no raw IPs stored. Built on Cloudflare Workers, D1, Durable Objects, Hono, and Drizzle.

**[Ash Iyer Real Estate](https://www.ashiyer.com)** — A website for a Calgary realtor, with a backend admin system for running themed event registrations and photobooths. Built with Next.js 16, React 19, and Tailwind, with Vitest, Playwright, and axe in the quality gates. Admin access is checked independently in the proxy and in the API routes, and end-to-end tests confirm each check holds on its own.

**Calgary real estate market data** — Python scrapers and data pipelines that run on a schedule, merge what they collect into one dataset, and record what changed between runs. Each run tracks its own health, so a source that quietly stops returning data gets noticed.

## 💻 Usually working with

**Languages:** TypeScript · JavaScript · Python · Java · PHP · Ruby · C# · SQL

**Frontend & backend:** React · Remix · Next.js · Tailwind CSS · Node.js · Express · REST APIs · WebSockets · Auth0

**Data:** PostgreSQL · Prisma · Redis · Valkey · MS SQL Server · MongoDB

**Cloud & DevOps:** AWS · Docker · GitHub Actions · ECR · CodeDeploy · Cloudflare Workers

**Testing:** Jest · Vitest · Cypress · Playwright · Storybook · RSpec

## 🔗 Find me

[LinkedIn](https://www.linkedin.com/in/momoiyer/) · [Email](mailto:iyermomo@gmail.com)
