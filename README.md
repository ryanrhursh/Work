# Ticket Board

A single-file tracker for IT tickets. Open `index.html` in a browser; no build or server needed.

- Each ticket has a number, description, an optional deliverable (tick "Deliverables?", max 100 characters), center (one of six short codes) and requestor.
- Status tabs: Open, In Progress, Resolved (plus All), each with a live count.
- Change status from the dropdown on any row; edit or delete with the row buttons. Every change has an Undo.
- Search, filter by center, and sort from the bar above the list.
- **Centers & backup** sets your six center codes (renaming updates existing tickets) and copies or restores a JSON backup.
- Data lives in the browser's local storage, so it stays on that browser and device. Use the backup to move it.
- Ticking "Deliverables?" requires a description (max 100 characters) and a "complete by" date. Tick "Mark complete" on a ticket when it is done.
- A deliverable past its date and not complete is flagged as overdue everywhere: a red bar above the tabs, a red outline on the ticket, a "late" count on the tabs, and the browser tab title. This holds even if the ticket itself is Resolved.
- The **Deliverables** page (switch at the top) lists every deliverable, grouped as Overdue, Due in the next 7 days, Later and No due date, with a Completed tab. Tick the checkbox to mark one complete; it updates the ticket and the overdue bar too. The ticket number jumps to that ticket on the board.
