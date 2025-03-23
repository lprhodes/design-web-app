# Diolog Web Application - Questions Board Wireframe

## Overview
This document describes the Questions Board wireframe for the Diolog Web Application. The Questions Board provides a Kanban-style interface for managing investor questions, allowing IR teams to efficiently track, categorize, and respond to inquiries.

## Components

### Navigation Elements
1. **Sidebar Navigation**
   - Company logo/branding
   - Menu items with Questions Board highlighted as active
   - Notification badge showing 5 outstanding questions
   - Upgrade to Premium CTA button

2. **Top Header**
   - Company profile dropdown
   - Notification icon
   - User profile dropdown

### Questions Board Content

3. **Page Header**
   - "Questions Board" title
   - Search bar for questions
   - Filter dropdown

4. **Kanban Board Layout**
   - Three main columns:
     - Outstanding (5) - with red header
     - Active (3) - with orange header
     - Closed (12) - with green header

5. **Outstanding Column**
   - Grid layout for question cards
   - Each card includes:
     - Question title
     - Question snippet
     - Investor name and submission time
     - Category tag
     - Red status indicator

6. **Active Column**
   - List layout for question cards
   - Each card includes:
     - Question title
     - Question snippet
     - Investor name and submission time
     - Category tag
     - Assigned team member avatar
     - Orange status indicator

7. **Closed Column**
   - List layout for question cards
   - Each card includes:
     - Question title
     - Question snippet
     - Investor name and submission time
     - Category tag
     - Green status indicator

8. **Bulk Actions Bar**
   - Located at the bottom of the board
   - Actions include: Archive, Assign Category, Assign Team Member, Export

## Design Notes

- **Color Coding**: Status columns use color-coded headers and card indicators (red for Outstanding, orange for Active, green for Closed)
- **Card Layout Differences**: Outstanding column uses a grid layout for better visibility of new questions, while Active and Closed columns use a more compact list layout
- **Category Tags**: Questions are tagged with categories (Financial, Product, ESG, Corporate, Strategy, Operations, Governance) with appropriate color coding
- **Drag and Drop**: The design supports drag-and-drop functionality to move questions between columns (not explicitly shown in static wireframe)

## Interactions

- Clicking on any question card should open the Question Details view
- Questions can be dragged between columns to change their status
- Search bar allows filtering questions by keyword
- Filter dropdown provides additional filtering options (by category, date, etc.)
- Bulk actions can be applied to multiple selected questions

## Changelog

| Date | Version | Description | Author |
|------|---------|-------------|--------|
| 2023-11-01 | 1.0 | Initial wireframe creation | AI-generated based on PRD requirements |

![Questions Board Wireframe](diolog-web-questions-board.svg)