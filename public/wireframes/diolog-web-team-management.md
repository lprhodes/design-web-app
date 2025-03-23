# Diolog Web Application - My Team Wireframe

## Overview
This document describes the My Team wireframe for the Diolog Web Application. The Team Management page provides a comprehensive interface for managing team members who have access to the company's Diolog account, allowing administrators to invite, edit, and remove team members, as well as manage their roles and permissions.

## Components

### Navigation Elements
1. **Sidebar Navigation**
   - Company logo/branding
   - Menu items with My Team highlighted as active
   - Notification badge showing 5 outstanding questions in Questions Board
   - Upgrade to Premium CTA button

2. **Top Header**
   - Company profile dropdown
   - Invite Team Member button (primary action)
   - Notification icon
   - User profile dropdown

### Team Management Content

3. **Page Header**
   - "My Team" title
   - Search bar for team members

4. **Team Members List**
   - Each team member card includes:
     - Profile picture/avatar with initials
     - Full name
     - Work email
     - Job title
     - Role/Permissions badge (Admin, Moderator, Editor, Viewer)
     - Status indicator (Active, Invited, Inactive)
     - Edit button
     - Remove button

5. **Role Information Section**
   - Brief description of available roles and their permissions
   - Role comparison table showing permissions for each role:
     - Admin: Full access to all features and settings
     - Moderator: Access to manage content but restricted access to user management
     - Editor: Access to create and edit content but limited management capabilities
     - Viewer: Read-only access to view data and content

6. **Invite Team Member Modal**
   - Work Email field (required)
   - First Name field (required)
   - Last Name field (required)
   - Job Title field (optional)
   - Role/Permissions dropdown
   - Send Invitation button
   - Cancel button

7. **Edit Team Member Modal**
   - First Name field (pre-filled)
   - Last Name field (pre-filled)
   - Job Title field (pre-filled)
   - Role/Permissions dropdown (pre-selected)
   - Save Changes button
   - Cancel button

8. **Remove Team Member Confirmation Dialog**
   - Warning message about removing team member
   - Confirm Remove button
   - Cancel button

## Design Notes

- **Card Layout**: Clean, card-based layout for team members with consistent spacing and information hierarchy
- **Visual Role Indicators**: Color-coded badges for different roles (Admin: blue, Moderator: green, Editor: purple, Viewer: gray)
- **Status Indicators**: Clear visual indicators for team member status (Active: green dot, Invited: yellow dot, Inactive: gray dot)
- **Responsive Design**: Layout adapts to different screen sizes while maintaining usability

## Interactions

- Clicking "Invite Team Member" button opens the Invite Team Member modal
- Clicking the search bar allows searching team members by name or email
- Clicking the Edit button opens the Edit Team Member modal with pre-filled values
- Clicking the Remove button shows a confirmation dialog before removing the team member
- Clicking "Send Invitation" in the Invite Team Member modal sends an invitation email to the provided work email address
- Clicking "Save Changes" in the Edit Team Member modal updates the team member's information

## Changelog

| Date | Version | Description | Author |
|------|---------|-------------|--------|
| 2023-11-02 | 1.0 | Initial wireframe creation | AI-generated based on PRD requirements |

![My Team Wireframe](diolog-web-team-management.svg)
