---
title: Bug Prioritization Matrix
---
Something I used in my previous life as a product manager. 

Note: This is from before I knew anything about accessibility, so does not explicitly cover accessibility issues.  

## Priority 1 - Highest (Urgent)
These are 'launchblockers', or even in some cases 'someone needs to wake up right now'

- Security, privacy, or life-altering information is compromised
  - Security cert or encryption fails
  - User is shown or able to access another user’s information
  - Incorrect information or advice shown which could be life-altering (financial, health, legal, etc)
  - Legal or regulatory risk (for example, GDPR non-compliance)
- App is completely inaccessible or unusable
  - Browser crashes or freezes 
  - Page is blank or inaccessible
  - UI elements broken such that it renders the page on usable

## Priority 2 - High

- Functionality is broken such that user cannot proceed or cannot perform a core action:
  - Unresponsive UI elements
  - Infinite or unreasonably long page loading time
  - Broken links
  - Error message that is unresolvable by the user

## Priority 3 - Medium

- Functionality technically works but usability is severely affected:
  - UI elements distorted or mispositioned making them hard to access or interact with
  - Visual or textual elements are not intuitive, potentially inhibits uses understanding of feature

## Priority 4 - Low

- Core design elements are incorrectly implemented:
  - Brand colours
  - Typography
  - UI components (buttons, selection components)
- Design details that affect polish or slickness of the products, but do not impact usability:
  - Minor inconsistencies in size or positioning of UI elements
  - Design or wording is inconsistent with other parts of the app
  - Animation or interaction is missing or incorrect
