# Quiet Rooms: study room booking prototype
 
A clickable prototype of a campus app for booking quiet study rooms. It is built for UX testing, so everything is fake: no server, no login, no real data.
 
## Purpose
 
Undergraduates often need a room at short notice between lectures. This prototype tests whether a student can find a free room for their group, book it, and check the booking afterwards.
 
**Main task for test participants:** find a room for 4 people tomorrow between 2pm and 4pm, book it, and check that the booking appears in "My bookings".
 
## Key features
 
- **Quick search** by date, start and end time, and group size, with helpful error messages.
- **Results list** with filters for building and facilities. Rooms that are booked or too small are listed separately with the reason.
- **Room details** with a photo placeholder, facilities, a description and room rules.
- **Confirm booking** with an editable group size, an optional purpose and a check-in tick box.
- **Success screen** with a booking reference (for example QR-7K3M9).
- **My bookings** where students can cancel a booking, with a confirmation step and an Undo option.
- **Going back:** every screen has a back or change link, and the search and filters are kept.
- **Out-of-scope parts** (Help, Add to calendar, Report a problem) show the message "This part isn't in the prototype yet."
## Content
 
10 rooms across 3 buildings (Marlowe Library, Ashdown Building and Kingsley Science Centre), seating 2 to 10 people. Some rooms are already booked tomorrow afternoon. One booking for next Monday is pre-loaded. All content is invented.
 
## Files
 
| File | Description |
| --- | --- |
| `index.html` | The whole prototype: HTML, CSS and JavaScript in one file. |
| `README.md` | This description. |
 
## How to use
 
1. Open `index.html` in a web browser. No installation or server is needed.
2. An internet connection is needed to load Pico CSS v2 from its official CDN (`cdn.jsdelivr.net`).
3. Reload the page to reset all bookings.
## Notes
 
- Built with [Pico CSS v2](https://picocss.com/), using its default look and semantic HTML.
- Designed mobile-first for a 375px-wide screen, and also works on a laptop.
- Accessibility: a label on every input, visible keyboard focus, a logical heading order and a skip link.
- The browser's back button does not move between screens. Use the on-screen buttons.
- Bookings are held in memory only and are lost when the page is reloaded.
