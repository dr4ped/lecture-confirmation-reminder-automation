# Lecture Confirmation and Reminder Automation

A Power Automate workflow for automating lecture confirmation, faculty reminders, and response tracking.

## Overview

This project automates faculty teaching coordination using:

- Microsoft Excel
- Power Automate
- Gmail
- Microsoft Forms

## Workflow

1. Read teaching activities from an Excel table.
2. Send confirmation requests to faculty with status `Pending`.
3. Faculty confirm availability through Microsoft Forms.
4. Power Automate updates the matching Excel row using `Activity ID`.
5. Faculty who remain `Pending` continue to receive confirmation requests.
6. A separate reminder branch sends a reminder before the scheduled teaching activity.

## Architecture

Excel Schedule  
→ Power Automate  
→ Gmail  
→ Microsoft Forms  
→ Power Automate  
→ Excel Update

## Status

Working prototype successfully tested in a real academic teaching workflow.

## Privacy

This repository uses fictitious sample data only. No real faculty names, emails, or institutional identifiers are included.
