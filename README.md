Obsidian Work System – Setup Guide

This repository contains ready-made templates for a daily-note–driven Obsidian workflow.
This README walks you through setting it up correctly from scratch.

You do NOT need to design anything — just follow the steps in order.

Prerequisites

Obsidian (desktop recommended)

Community Plugins enabled

A new or existing Obsidian vault

1. Folder Structure

Create the following folders at the root of your vault:

Daily Notes/
Projects/
Templates/
Weekly Reviews/


Folder names must match exactly for Dataview queries to work as written.

2. Copy Files from This Repository

This repository already contains:

Daily note template

Weekly review template

Work Dashboard

After cloning or downloading the repo:

Copy the contents into your Obsidian vault

Keep folder names the same

Do not rename files unless you also update references later.

3. Enable Required Plugins
Enable Community Plugins

Open Settings → Community plugins

Turn Safe Mode OFF

Install Dataview (Required)

Community plugins → Browse

Install Dataview

Enable it

Then configure:

Settings → Dataview

Enable Dataview

Enable JavaScript Queries

Dataview powers dashboards, task rollups, and activity timelines.

Install Periodic Notes (Required)

Community plugins → Browse

Install Periodic Notes

Enable it

Configure Weekly Notes:

Settings → Periodic Notes → Weekly Notes

Weekly note folder: Weekly Reviews

Weekly note template: Templates/Weekly Review

First day of week: Monday (recommended)

4. Configure Daily Notes

If using the Daily Notes feature:

Settings → Daily Notes

New file location: Daily Notes

Template file location: Templates/Daily Notes

5. Create Project Notes

Inside the Projects/ folder, create one note per project.

Example: Projects/OS Query.md

Add aliases at the top to prevent broken links:

---
aliases:
  - OS QUERY
  - osquery
  - OSQUERY
---

6. Verify Backlinking Works

Open today’s Daily Note

Add:

🧠 [[OS Query]] — initial setup

Open Projects/OS Query.md

Open the Backlinks panel (right sidebar).
You should see today’s Daily Note listed.

7. Open the Work Dashboard

Open Work Dashboard.md.

If Dataview is configured correctly, you should see:

Actionable tasks

Waiting items

Recent activity

8. How to Use the System
Logging work

🧠 [[Project]] — deep work

🧯 [[Project]] — ops / incident

🧭 [[Project]] — unblocked someone

📌 [[Project]] — decision made

Creating tasks

 🧠 [[Project]] — task description #p2

Priority tags:

#p1 = urgent

#p2 = important

#p3 = nice-to-have

Waiting on others

 ⏳ [[Project]] — waiting on approval #waiting #p1

9. Weekly Reviews

Each week:

Open Command Palette

Run Periodic Notes: Open weekly note

Weekly notes are created automatically using the template.

Mental Model

Daily Notes → what happened

Projects → what it belongs to

Dashboard → what needs attention

Backlinks → history for free
