# course-materials-f2025

Course materials - the source for the **Release materials** action.

## Structure

Any top-level directory containing at least one ordinal-prefixed subdirectory (`00_`, `01_`, `02_`, ...) is a releasable section - no config to declare it:

- `lectures/00_session-1/` - one folder per session's lecture files
- `readings/00_session-1/` - one folder per session's readings
- `*syllabus*`, this `README.md` (root) - released via the syllabus / README toggles

Add more sessions by creating `lectures/01_session-2/`, `readings/01_session-2/`, ... (only the ordinal prefix matters - name the rest whatever you like), or add a whole new section (e.g. `labs/00_intro/`) - then run **Refresh actions** so the session dropdown and Release button's section toggles pick it up.

## Public course website (optional)

The **Publish course website** action can share this repo's materials on a public open-courseware site. Lecture files are always hosted; for readings you choose `reading-list` (text/citation files are shown as a list - keep copyrighted PDFs out of the list by leaving them as non-text files) or `actual-readings` (every reading file is hosted and downloadable - you carry the copyright responsibility).
