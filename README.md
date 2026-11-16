# BLACKGLASS — Trojan Response Simulator

A browser-based, fictional DFIR training exercise. Investigate a suspected Trojan-style execution chain across four stages: initial triage, process behaviour, persistence/network correlation, and containment/reporting.

## Run locally

Open `index.html` in a modern browser. No build step, dependencies, backend, or account is required.

## Training scope

- Fictional endpoint and user telemetry only.
- No malware or payload is included or executed.
- No processes are spawned and no files, registry settings, or network connections on the host are changed.
- The destination `198.51.100.24` is in the TEST-NET-2 documentation range and is shown as simulated telemetry only.
- Endpoint isolation is a decision recorded by the exercise, not a real EDR action.

## Learning objectives

1. Triage suspicious process relationships without jumping to conclusions.
2. Correlate parent/child process behaviour and command-line indicators.
3. Treat persistence and network signals as leads requiring validation.
4. Choose proportionate containment, preserve evidence, and scope the incident.

## Publish with GitHub Pages

In the repository, open **Settings → Pages**. Under **Build and deployment**, select **Deploy from a branch**, choose **main** and **/(root)**, then save. GitHub will provide the published URL after deployment completes.

## Project

Single-page HTML/CSS/JavaScript. No external libraries or tracking scripts.
