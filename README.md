# Project Reese — Employee Recognition Experience Prototypes

> A set of high-fidelity prototypes exploring the **Employee Recognition** experience — showing how recognition can be **discovered, sent, celebrated, and remembered** within the everyday flow of work, across multiple Microsoft 365 surfaces (Copilot / Outlook / Teams / Viva).

## Background

**Recognition should happen where work happens.**

Employees rarely open a standalone recognition tool just to thank a teammate. Genuinely valuable contributions — especially "invisible work" — are often forgotten because of fragmented workflows and missed timing. And when people do want to express appreciation, they often give up because they "don't know what to write" or "worry it sounds generic."

This project explores an **embedded, AI-assisted** recognition experience: the system surfaces recognition opportunities naturally within everyday collaboration (meetings, email, project work), proactively recommends contributors worth acknowledging, helps users express authentic appreciation with editable AI drafts, celebrates that recognition in the right team context, and ultimately turns it into long-term **career visibility** and **organizational talent insight**.

### Journey (4 stages)

| Stage | 1. Discover Contributions | 2. Send Recognition | 3. Celebrate Recognition | 4. Build Career Visibility |
|---|---|---|---|---|
| Type | Discovery | Creation | Celebration | Memory |
| Goal | Identify contributors worth recognizing | Express appreciation clearly and meaningfully | Help employees feel seen and share the moment with the team | Understand and demonstrate long-term impact |

See the full journey map in [`recognition-journey-map.html`](recognition-journey-map.html) (source of truth).

## What's in each file

| File | Touchpoint / Stage | What it shows |
|---|---|---|
| [`recognition-journey-map.html`](recognition-journey-map.html) | Overview · Stages 1–4 | **Horizontal product journey map** (final version / source of truth). Shows the 4 stages from discovery to career memory, each with Current State (challenges / opportunity) and Future Experience (trigger / user actions / system actions / key outputs). The bottom "Cross-platform Touchpoints" section lets you click Cowork / Outlook / Teams to open each prototype in an embedded iframe. |
| [`copilot-recognition-prototype.html`](copilot-recognition-prototype.html) | Copilot / Cowork · Stages 1–2 | **Microsoft 365 Copilot recognition workflow.** Demonstrates how Copilot identifies collaborators in meeting-recap / task contexts, proactively recommends recognition opportunities, and helps the user start a recognition. |
| [`copilot-recognition-prototype-outlook.html`](copilot-recognition-prototype-outlook.html) | Copilot → Outlook · Stages 1–2 | An **extended version** of the Copilot workflow that hands off to the Outlook email context, showing the cross-surface flow from discovering an opportunity in Copilot to completing recognition through email. |
| [`outlook-recognition-prototype.html`](outlook-recognition-prototype.html) | Outlook · Stages 1–3 | **Outlook email recognition & setup.** Shows recognition reminder emails, recognition announcement emails, and opening the Teams app directly from email to configure / unsubscribe (links point to the Teams prototype's settings page at `?pg=set`). |
| [`teams-recognition-prototype.html`](teams-recognition-prototype.html) | Teams · Stages 1–3 | **Microsoft Teams Recognition Hub.** The main recognition hub: left rail with Notifications and Recognition; notifications let you handle an "approval request," compose and send recognition using an editable AI draft card; includes a Settings page (trigger types, reminder preferences, etc.). |
| [`Recognition_Journey_Map_CN.md`](Recognition_Journey_Map_CN.md) | Documentation | A companion document for the journey map, kept in sync with `recognition-journey-map.html` (the HTML is the final source of truth). |

## How to view

All prototypes are **plain static HTML/CSS/JS** — no build step or dependencies required.

- Open any `.html` file directly in a browser;
- Recommended entry point is [`recognition-journey-map.html`](recognition-journey-map.html), from which you can navigate to each prototype via the bottom touchpoints.

## Design

Follows the Microsoft Fluent / Teams visual language: brand color `#5b5fc7`, 16px corner radius, light-gray background `#f6f6f9`, with consistent card and divider conventions.