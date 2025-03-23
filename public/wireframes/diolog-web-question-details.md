# Diolog Web Application - Question Details Wireframe

## Overview
This document describes the Question Details wireframe for the Diolog Web Application. The Question Details view provides a comprehensive interface for viewing and responding to individual investor questions, including detailed question information, investor details, assignment options, and response capabilities.

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

### Question Details Content

3. **Page Header**
   - "Question Details" title
   - Back to Board button

4. **Question Information Section**
   - Question title ("Q3 Results")
   - Status toggle buttons (Outstanding, Active, Closed) with Outstanding selected
   - Full question text
   - Category tag ("Financial")
   - Question metadata (asked by, timestamp)

5. **Investor Details Section**
   - Investor profile picture/initials
   - Investor name and email
   - Investor type badge ("Shareholder")
   - Question count
   - Join date

6. **Assignment & Categorization Section**
   - Team member assignment dropdown
   - Category tags with option to add more categories

7. **Question History/Activity Log**
   - Chronological list of actions taken on the question
   - Timestamps for each action

8. **Response Area**
   - Rich text editor for composing responses
   - Text formatting toolbar
   - Response template selection dropdown
   - Action buttons:
     - Send Response (primary action)
     - Close Question
     - Add to Registry

## Design Notes

- **Status Visualization**: Clear visual indication of the question's current status with color-coded toggle buttons
- **Rich Text Editor**: Comprehensive editor for formatting responses professionally
- **Investor Context**: Dedicated section for investor details to provide context about who is asking the question
- **Activity Tracking**: Chronological history of all actions taken on the question for accountability and reference

## Interactions

- Clicking status toggle buttons changes the question's status
- Team member assignment dropdown allows selecting a team member to handle the question
- Category tags can be added or removed
- Response templates can be selected to pre-populate the response area
- Send Response button sends the response to the investor and potentially changes the question status
- Close Question button marks the question as closed
- Add to Registry button adds the question and response to the Question Registry for future reference
- Back to Board button returns to the Questions Board view

## Changelog

| Date | Version | Description | Author |
|------|---------|-------------|--------|
| 2023-11-01 | 1.0 | Initial wireframe creation | AI-generated based on PRD requirements |

![Question Details Wireframe](diolog-web-question-details.svg)