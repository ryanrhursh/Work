# Ticket Board

A single-file tracker for IT tickets. Open `index.html` in a browser; no build or server needed.

- Each ticket has a number, description, an optional deliverable (tick "Deliverables?", max 100 characters), center (one of six short codes) and requestor.
- Status tabs: Open, In Progress, Resolved (plus All), each with a live count.
- Change status from the dropdown on any row; edit or delete with the row buttons. Every change has an Undo.
- Search, filter by center, and sort from the bar above the list.
- **Centers & backup** sets your six center codes (renaming updates existing tickets) and copies or restores a JSON backup.
- Data lives in the browser's local storage, so it stays on that browser and device. Use the backup to move it.
