# Diwali Afterglow

Upload `index.html`, `style.css`, `script.js` to a GitHub repo, then Settings > Pages > Deploy from branch (main, root).

## Send RSVPs straight into the Google Form
1. In the form, add a short-answer question called "Your name" (required).
2. Form editor > three dots > Get pre-filled link. Fill the name, pick "I'll be there", click Get link, copy it.
3. In that link, find `entry.XXXX=...` for the name and for the attendance question. Put them in `ENTRY_NAME` and `ENTRY_COMING` at the top of `script.js`.
4. Make sure `YES` / `NO` match the form's option text exactly.
5. Commit, then test in an incognito window. Check the Responses tab.

Until the two entry ids are filled, the RSVP button just opens the form.
