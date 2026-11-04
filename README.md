# Ticket Board

A single-file tracker for IT tickets. Open `index.html` in a browser; no build or server needed.

- Each ticket has a number, description, center (one of six 3-letter codes) and requestor.
- Status tabs: Open, In Progress, On Hold, Resolved, Closed (plus All), each with a live count.
- Change status from the dropdown on any row; edit or delete with the row buttons. Every change has an Undo.
- Search, filter by center, and sort from the bar above the list.
- **Centers & backup** sets your six center codes (renaming updates existing tickets) and copies or restores a JSON backup.
- Data lives in the browser's local storage, so it stays on that browser and device. Use the backup to move it.
