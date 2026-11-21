LIFT. UPDATED WORKOUT APP

Upload all files in this folder to the root of your existing GitHub repository, replacing the old files.
Then open your existing GitHub Pages URL in Safari and refresh it. If an old version remains, close the app and reopen the site in Safari.

Progression logic:
- Each exercise starts at the prescribed rep target.
- On a fully completed exercise, if every set reaches the target, next session target rises by 1 rep.
- After reaching prescribed reps +2 on every set, the next session increases weight by the listed increment and resets the target to the prescribed reps.
- Bodyweight exercises continue adding reps and do not add weight.
- The current version starts a fresh v2 data store; prior v1 local workout history/weights are not automatically migrated. Export any old backup before replacing if you need it.
