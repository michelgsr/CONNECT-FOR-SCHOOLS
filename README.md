# CONNECT for schools

**CONNECT isn’t another app for teenagers. It’s a tool that helps schools get their students out into the neighbourhood.**

Young people spend a lot of time on screens. Barcelona has hundreds of free activities for 12–18 year olds, but the information is scattered. CONNECT lets tutors bring those activities to their class on paper and in person: teachers use the screen, students live the activity.

## The tutor’s 4 steps (`#plan`)

1. **Your class**: school district and age of the group (school and class names are optional and only appear on printouts).
2. **Choose activities**: 3 to 8 real activities near the school, filterable by type, price and “after school / weekends”, each with its official link and verification date.
3. **Print materials** (A4, `@media print`):
   - *Classroom board* for the noticeboard (no QR code)
   - *Interest sheet* where students write their names on paper
   - *Family letter* with official links (text + QR) and a tear-off authorisation for a first group visit
   - *Class challenge*: one sticker per visit, a class goal instead of individual points
4. **Organise & follow up**: form groups from the interest sheet, checklist for a first visit together, and an end-of-term count (numbers only, no names).

The plan is saved in the browser (`localStorage`).

## Students

Students don’t need an app, an account or a phone: everything reaches them on paper and in class. The only QR codes are in the family letter, and they point to each activity’s official page.

## Other pages

- **For families**: privacy, registration through official organisers, first group visit.
- **About**: the problem, the school-led approach, what CONNECT does and doesn’t do, official sources.
- **Team** (`#admin`): internal dashboard to add, edit and verify activities.

## Configuration

```js
const TEAM_EMAIL = '';  // email for the contact button
```

## Run it

Single static file, no build step. Open `index.html` or publish with **GitHub Pages** (*Settings → Pages → Deploy from a branch → `main` / root*).

## Data

Activity information was checked against official Barcelona sources on **3 November 2026**. Always confirm on the official page.

QR codes: [qrcode-generator](https://github.com/kazuhikoarase/qrcode-generator) by Kazuhiko Arase (MIT), embedded.
