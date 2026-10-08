# Swipe it

Swipe it — Personal Content Organiser

A visual, swipe-based Reddit media and content management application.

Project status: Planning / Early Development
Platform: Android
Reddit Integration: Official Reddit OAuth 2.0 API
Purpose: Personal Reddit content organisation and management

---

Overview

Swipe it, is a proposed third-party application designed to help Reddit users efficiently review, organise and manage their saved, upvoted, downvoted and hidden content.

Over time, Reddit users can accumulate hundreds or thousands of saved submissions, including images, videos, GIFs, educational resources, discussions and other content.

Managing these collections individually can become time-consuming.

Swipe it aims to simplify this process through an intuitive, visually appealing, swipe-based interface.

Users will be able to review their existing Reddit content, decide what they want to retain and manage their collections without repeatedly navigating through individual submissions.

Planned Features

1. Swipe-Based Content Management

The central feature will be a simple gesture-based interface:

- Swipe Right: Keep the current item.
- Swipe Left: Remove the item from the relevant collection, where supported.
- Tap: Open or expand the original submission.
- Undo: Reverse recent actions where technically possible.
- Filter: Display content according to selected categories.

Actions that modify Reddit account data will require explicit user interaction.

2. Visual Media Gallery

A dedicated gallery interface will allow users to browse Reddit media in a visually organised environment.

Planned capabilities include:

- Image and video previews.
- GIF and gallery support.
- Grid-based media layouts.
- Full-screen viewing.
- Filtering by media type.
- Sorting by date and subreddit.
- Navigation to original Reddit submissions.

3. Account Content Organisation

The application aims to support the following categories, subject to Reddit API availability and permissions:

- Saved submissions and comments.
- Upvoted submissions.
- Downvoted submissions.
- Hidden submissions.

Users will be able to select a category and review its contents using the swipe interface.

4. Personalised Browsing

Potential future functionality includes:

- Customisable gallery layouts.
- Adjustable sorting preferences.
- Review progress indicators.
- Content grouping by subreddit.
- Optional local organisation labels.
- Remembering the user's browsing preferences.

These features are proposed and may change during development.

---

Example Use Case

A user has accumulated 1,500 saved Reddit submissions over several years.

Their saved collection includes photography, interesting discussions, educational material, videos and content that is no longer relevant.

Using Swipe it, the user could:

1. Authenticate securely with their Reddit account.
2. Select their saved content collection.
3. Browse submissions in a visual gallery.
4. Swipe right to retain useful content.
5. Swipe left to unsave unwanted content.
6. Continue reviewing their collection at their own pace.

This provides an alternative way to manage existing Reddit activity without requiring automated account interactions.

---

Reddit API Integration

The application is intended to use Reddit's official API and OAuth 2.0 authentication.

Planned API Functionality

Function| Purpose
OAuth authentication| Securely authorise account access
Read saved content| Retrieve the user's saved submissions
Read voting history| Display accessible voting history
Read hidden content| Retrieve the user's hidden submissions
Unsave content| Remove saved status when requested
Unhide content| Reverse hidden status when requested
Retrieve submission metadata| Display titles, media and subreddit information

All functionality will be subject to Reddit's approved API permissions, endpoint availability and usage restrictions.

Requested Permissions

The application is expected to require appropriate read and account-history permissions, together with permissions for explicitly authorised content-management actions.

The exact OAuth scopes will be determined during implementation and limited to those necessary.

---

Privacy and Security

Protecting user privacy is a central design consideration.

The application is intended to follow these principles:

- Authentication through Reddit's official OAuth system.
- No collection or storage of Reddit passwords.
- No sale or distribution of user information.
- No unnecessary collection of personal data.
- Secure handling of authentication credentials.
- Minimal local caching of Reddit content.
- No automated posting, commenting or voting.
- No scraping or circumvention of Reddit API restrictions.
- Compliance with applicable Reddit Developer Terms and API policies.

Users will retain control over any actions performed on their accounts.

---

---

Swipe it, is intended to be a standalone personal account-management application rather than an application embedded within an individual subreddit.

Its functionality requires an independent interface capable of presenting authorised account history from multiple communities in a unified gallery.

The proposed application also requires custom navigation, gesture-based interactions and personal content-management workflows.

These requirements make an independently hosted application using Reddit's external API more appropriate than Devvit's embedded application model.

---

Intended Audience

The application is initially proposed as a personal productivity tool for managing Reddit content.

Any potential public distribution will depend on development progress, Reddit API approval and compliance with the applicable platform policies.

Disclaimer

Swipe it, is an independent proposed third-party project and is not affiliated with, endorsed by or officially associated with Reddit, Inc.

Reddit and its associated trademarks belong to their respective owners.

The application will only operate within the permissions and functionality authorised by Reddit.

---

Project Status: Concept / Pre-development

Primary Objective: Make managing Reddit content simpler, faster and more visually intuitive.