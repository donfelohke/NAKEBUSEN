# NAKEBUSEN DIGITAL — Service Playbook

**Public description:** Practical technology. Reflective systems. Greater digital independence.  
**Relationship:** NAKEBUSEN DIGITAL is powered by WARENA.  
**Status:** PROPOSAL — operating framework; individual capabilities and offers require verification.

## Purpose

Give clients a clear, human-understandable path from technology problem to agreed scope, tested delivery, handover and support. Avoid selling a tool before understanding the need.

## Service families to assess

These are candidate service families, not a promise that every job is currently available:

- GNU/Linux installation, configuration and troubleshooting.
- Computer setup, maintenance and performance diagnosis.
- Development environment and IDE setup.
- Local networks, Wi-Fi, routers and small-office connectivity.
- Basic server, lab and service deployment.
- Backup planning, restore tests and data migration.
- Reproducible development environments and documented workflows.
- Technical review, training and operational handover.

Complexity, hardware availability, licensing, connectivity, security, travel and support requirements affect feasibility and price. Confirm the actual offer and capability before quoting.

## Intake and discovery

Ask:

1. What is not working, or what outcome should the client be able to achieve?
2. Which devices, operating systems, applications, network equipment and versions are involved?
3. What changed before the problem appeared? What troubleshooting has already been attempted?
4. What data is important, and is there a current backup whose restoration has been tested?
5. What constraints apply: budget, deadline, connectivity, power, location, licences, data sensitivity or downtime?
6. Who owns the equipment and has authority to approve changes?
7. What does a successful result look like, and who will verify it?

Do not request passwords, private keys or other secrets through public issues, repository commits or routine messages. Use a secure, appropriate method only when access is necessary. Obtain permission before accessing, copying, moving or deleting client data.

## Scope and quote

Before work starts, write down:

- Problem statement and desired outcome.
- In-scope tasks and explicit exclusions.
- Equipment, software versions and assumptions.
- Data handling, backup and rollback approach.
- Expected downtime, dependencies and risks.
- Deliverables, verification steps and acceptance criteria.
- Price, any travel/material/licence costs, estimate limits and approval.
- What is not included in follow-up support.
- Client approval and the process for handling scope changes.

If the problem cannot yet be diagnosed, quote a bounded assessment first rather than promising a fixed solution.

## Delivery workflow

1. **Baseline:** Record the minimum relevant system facts and reproduce the issue where safe.
2. **Protect:** Confirm authorisation, backup status, rollback plan and data sensitivity.
3. **Change:** Make the smallest appropriate change; preserve configuration and version history where possible.
4. **Test:** Run the agreed checks and record expected versus actual results.
5. **Recover:** If a change fails, follow the rollback plan and communicate the result.
6. **Handover:** Explain what changed, how to use it, how to maintain it, and what remains unresolved.
7. **Close:** Obtain client acceptance or document the outstanding issue and next step.

Do not claim a backup is reliable until restoration has been tested. Do not claim a network is secure, a system is production-ready or a deployment is successful without relevant evidence.

## Minimum technical record

For each technical job, retain only the necessary information in a controlled location:

- Job/reference ID without unnecessary personal details.
- Approved scope and environment.
- Device/model, software and relevant versions.
- Commands/configuration changes, with secrets removed.
- Tests, expected results and actual results.
- Known limitations, incidents and rollback result.
- Handover date and agreed support boundary.

Never commit client names, addresses, phone numbers, credentials, private IP/topology details that create a security risk, private data or raw diagnostic dumps to this public repository.

## Acceptance and handover checklist

- [ ] Agreed scope completed or remaining work explicitly listed.
- [ ] Tests run and results recorded.
- [ ] Data protection and backup/restore status stated accurately.
- [ ] Client can access and operate the delivered system.
- [ ] Credentials and ownership are handed over through an appropriate secure channel.
- [ ] Documentation and recovery instructions are supplied where in scope.
- [ ] Known risks, licences, recurring costs and support limits are explained.
- [ ] Client acceptance or unresolved items are recorded.

## Service and pricing status

No specific DIGITAL price is established by this playbook. Quote after discovery based on scope, time, travel, materials, licensing, risk and support obligations. Record owner-approved public prices separately before publishing them.

## Source of technical truth

Implementation belongs in the relevant WARENA repository or controlled project record. Record the repository, version/commit, hardware assumptions, commands, test output and limitations. This playbook is not evidence that a proposed deployment has been performed.

## Status and review

**Status:** PROPOSAL. Approve only after the practitioner reviews feasibility, service boundaries, privacy/security practices, quote terms, and the handover process.
