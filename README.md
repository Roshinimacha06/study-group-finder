# Study Group Finder

A web prototype where students create study groups by subject and timing. Members request to join, and the group leader approves.

**Live demo:** https://YOUR-USERNAME.github.io/study-group-finder/

## Features

- **Sign-in options:** continue with Google, Microsoft, email, or as a guest (demo sign-in, no real authentication).
- **Group creator information:** name, course, year and a short bio shown on every group.
- **Joiner information:** each join request carries the student's name, course, year, email and an optional message.
- **Leader approval:** the leader reviews each request and approves or declines it. Seats update automatically.
- **Location:** in-person groups show a venue with a "View on map" link. Online groups show a meeting link.
- **Direct invite link:** every group has a copy button, and the link opens that group directly.
- **Search and filters:** search by topic, subject, venue or leader. Filter by subject, day, format and open seats. Sort by newest, most open seats or title.
- **In-app notifications:** a bell icon alerts leaders to new requests and members to approvals or declines.
- **My groups:** a tab showing groups you lead or have requested to join.
- **Responsive design:** works on phones and desktops, with light and dark themes.

## Tech stack

- HTML, CSS and JavaScript in a single file (`index.html`)
- Browser `localStorage` for saving data
- GitHub Pages for hosting
- No frameworks, no build step, no server

## Run locally

1. Download or clone this repository.
2. Open `index.html` in any modern browser.

## Host on GitHub Pages

1. Push `index.html` to the `main` branch.
2. Go to **Settings, then Pages**.
3. Set the source to **Deploy from a branch**, choose `main` and `/ (root)`, then save.
4. Your site will be live at `https://YOUR-USERNAME.github.io/study-group-finder/`.

## Demo walkthrough

1. Sign in as the leader of a sample group: use the email `aarav@campus.edu`, then sign out.
2. Sign in as a new student, open "Calculus II problem sets" and send a join request.
3. Sign out and sign in again as `aarav@campus.edu`. Open the bell, then open the group and approve the request.
4. Sign in as the student again. The bell shows the approval.

## Limitations

- Data is saved in each visitor's browser, so groups and notifications are not shared between devices.
- Sign-in is a demo and does not verify identity.
- Notifications work inside the app only, with no email or push alerts.
- There is no in-group chat and no moderation of new groups.
- Invite links open a group only on the device where it exists.

## Future scope

1. **Foundation:** shared database (Firebase or Supabase), real sign-in, college email verification.
2. **Engagement:** email and push alerts, group chat, session reminders.
3. **Smart tools:** calendar sync, matching by course and timing, ratings and attendance.
4. **Growth:** Android and iOS app, campus integration, moderation dashboard.

## Project structure

```
study-group-finder/
├── index.html   # the whole application
└── README.md    # this file
```

## Author

Replace this line with your name, course and college.
