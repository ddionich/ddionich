# Dylan Dionich

### Senior Software Engineer · Backend

I build backend systems for financial products — fintech, KYC, compliance, onboarding — where the hard part usually isn't the code, but keeping a system correct and understandable while the rules around it keep changing.

Currently at **Blockchain.com**, on backend systems across compliance, operations, finance and onboarding. On the side I design and ship products at **[Bimo](https://bimolabs.com)**.

[LinkedIn](https://www.linkedin.com/in/dionich/) · [Personal GitHub](https://github.com/ddionich) · [Work GitHub](https://github.com/ddionich-bc)

---

## Projects

### [nafti.app](https://nafti.app) · beta

A web app that helps drivers decide **where and when to refuel**. It compares the official pump price against prices reported by the community, turns that gap into an actual savings figure, and ranks nearby stations with a single score — the Nafti Score — built from trust, distance and convenience.

The real problem underneath is cold start: the app is only valuable with fresh community reports, and people only report once it's already valuable. Nafti breaks out of that loop using an Argentine government dataset — but stations aren't required to publish per-station prices, so its freshness is wildly uneven. Some stations reported yesterday; others last reported more than five years ago. Under Argentine inflation a five-year-old price isn't approximately right, it's noise. Showing nothing isn't an option either.

So most of the work has gone into two things at once: squeezing the most accurate price possible out of data of very uneven age, and being explicit with the user about how much any given price can be trusted. The transparency is a feature, not a disclaimer — it's what makes a stale number usable instead of misleading.

Mobile-first, currently in beta: station discovery with a recommended pick, station detail with price history, fuels, services and promos, community price reporting, a trip planner with estimated cost, and a contributor profile with email/password auth gating the personal features.

Built at **[Bimo](https://bimolabs.com)** — a small studio I use to take my own products end to end: API, frontend, infrastructure and everything in between. Source is private for now.

---

## What I work on

Backend development, data infrastructure, event-driven systems and observability — plus full-stack product work when a project needs it.

<!-- REVISAR: el párrafo de abajo lo redacté como ejemplo concreto a partir de
     tu descripción general. Ajustalo o reescribilo para que describa trabajo
     tuyo real antes de mergear. -->
Most of what I've built lives in regulated workflows: onboarding pipelines that depend on external providers, compliance processes where a retry has to be idempotent because a duplicate is a regulatory problem and not just a bug, and internal platforms that other teams depend on daily.

**Interested in:** backend architecture · distributed systems · event-driven architecture · data-intensive applications · AI-assisted software engineering

---

## Stack

**Backend**

<p>
  <img alt="Kotlin, Java, Spring, PostgreSQL, MySQL, Redis, Kafka" src="https://skillicons.dev/icons?i=kotlin,java,spring,postgres,mysql,redis,kafka" />
</p>

Kotlin · Java · Ktor · Spring Boot · PostgreSQL · MySQL · Redis · Kafka · Microservices

**Frontend**

<p>
  <img alt="React, Next.js, Vite, JavaScript" src="https://skillicons.dev/icons?i=react,nextjs,vite,js" />
</p>

React · Next.js · Vite · JavaScript

**Infrastructure & Observability**

<p>
  <img alt="Docker, Kubernetes, AWS, GCP, Linux, Bash, Git, GitHub" src="https://skillicons.dev/icons?i=docker,kubernetes,aws,gcp,linux,bash,git,github" />
</p>

Docker · Kubernetes · AWS · GCP · Linux · Bash · Git · Datadog

---

## GitHub

<table>
  <tr>
    <td align="center"><b>Work</b><br/><sub>@ddionich-bc</sub></td>
    <td align="center"><b>Personal</b><br/><sub>@ddionich</sub></td>
  </tr>
  <tr>
    <td>
      <img alt="Contribution streak for @ddionich-bc" src="https://streak-stats.demolab.com/?user=ddionich-bc&hide_border=true&theme=transparent" />
    </td>
    <td>
      <img alt="Contribution streak for @ddionich" src="https://streak-stats.demolab.com/?user=ddionich&hide_border=true&theme=transparent" />
    </td>
  </tr>
</table>

---

<p align="center">
  <sub>Building at <a href="https://bimolabs.com">Bimo</a> · Reach me on <a href="https://www.linkedin.com/in/dionich/">LinkedIn</a></sub>
</p>
