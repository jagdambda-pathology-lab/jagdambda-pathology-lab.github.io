# Jagdamba Pathology Lab — GitHub Pages (Deployment)

This repository hosts the **compiled production build** of the Jagdamba Pathology Lab software.

**Live site:** https://jagdambda-pathology-lab.github.io

---

## Important — do not edit this repo manually

All files here are auto-generated. Any manual changes will be overwritten the next time the app is deployed.

To make changes to the application, work in the **private source repository**:
**https://github.com/bikcrum/jagdamba-pathology-lab-software**

---

## How this repo is updated

From the source repo, running:

```bash
npm run deploy
```

builds the React app and pushes the compiled output directly into the `deploy` branch of this repo. GitHub Pages then serves it automatically.

---

## Repository layout

| Branch | Purpose |
|---|---|
| `deploy` | Current live build — what GitHub Pages serves |

---

## GitHub Pages configuration

- **Source branch:** `deploy`
- **Served at:** `https://jagdambda-pathology-lab.github.io`

To change the Pages source branch, go to:
`Settings → Pages → Branch` in this repo.

---

## Source repository

All development, history, and documentation:
https://github.com/bikcrum/jagdamba-pathology-lab-software *(private)*
