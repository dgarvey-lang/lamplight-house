# Lamplight House

A chore tracker game: every chore you finish lights a window in the house. Light the whole house before Sunday night for a bonus.

- Earn coins for chores (+5 for finishing on or before the planned day, +50 for a full-house week)
- Level up from total coins earned and build a weekly streak
- Plan chore days on the week board
- Add your own activities (just once, once a week, or every day) with your own point values
- Spend coins in a reward shop you set up yourself

## Running it

It's a single self-contained page. Open `index.html` in a browser, or serve it with GitHub Pages.

When opened outside Claude, progress is saved in the browser's local storage on that device (the cloud sync only works in the Claude-hosted version).

## Daily Chore Planner (`chores.html`)

A phone-friendly planner built from the full chore list (daily, weekly, twice a month, monthly, every 3 and 6 months, yearly). Each chore gets a fixed spot on the calendar so the work is spread out, and the **Today** tab shows just what's due that day.

- Tap a chore to check it off; tap **Reschedule** to move it to another day this week (or **Do today** on a future day)
- Anything missed shows up under **Catch up** until it's done (or its next turn comes around)
- **Coming up** shows the next two weeks and the bigger jobs ahead
- **+ Add a chore** and **− Remove a chore** buttons on the Today screen; Remove asks you to tap twice and can be undone
- **Chores** lets you rename or reschedule any chore; "Pick the least busy day" places a chore automatically
- Mowing only shows April through November
