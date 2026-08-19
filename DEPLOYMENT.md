# World Mechanics — Publication Runbook

## GitHub Pages

Repository: `seshu469/world-mechanics`

1. Copy the release files into the repository root.
2. Commit and push to `main`.
3. GitHub → repository → Settings → Pages.
4. Source: **Deploy from a branch**.
5. Branch: `main`, folder: `/ (root)`.
6. Save and wait for the Pages deployment to complete.

The package defaults to the known GitHub Pages address `https://seshu469.github.io/world-mechanics/`.

## Optional custom domain

`CNAME.example` contains the intended domain `worldmechanics.ai`, but it is deliberately **not active** in this release because domain ownership has not been confirmed in this workflow. After you own/control that domain:

1. Rename `CNAME.example` to `CNAME`.
2. Add the GitHub Pages DNS records at the registrar/DNS provider.
3. Configure `www` as a CNAME to `seshu469.github.io`.
4. Verify the domain in GitHub account Pages settings and retain the verification TXT record.
5. Enable Enforce HTTPS after GitHub's DNS check passes.

## ORCID

Create or use an ORCID iD and add it to `CITATION.cff`, `.zenodo.json`, the website author profile and archive metadata. Do not invent an ORCID; add it only after registration.

## DOI / research archive

A DOI should be added only after an actual archive record is published. Recommended workflow: publish the PDF and source release to a DOI-issuing research repository such as Zenodo, then add the issued DOI back to the website, README, `CITATION.cff` and `.zenodo.json` in a follow-up version.

## Release checklist

- [ ] Read the complete PDF and approve the wording
- [ ] Confirm author name and affiliation wording
- [ ] Add ORCID if available
- [ ] Push files to GitHub
- [ ] Verify Pages on desktop and mobile
- [ ] Tag/release `v1.0.0`
- [ ] Publish/archive the release and obtain a DOI
- [ ] Add the DOI back to the project metadata
- [ ] Only activate `CNAME` after domain ownership is confirmed
- [ ] Keep the AI-assistance disclosure visible

## Publication status wording

Use **independent open research preprint**, **review and position paper**, or **open research draft**. Do not describe the paper as peer reviewed unless it later completes a genuine peer-review process.
