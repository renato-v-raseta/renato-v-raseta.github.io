# Claude working rules for this folder

This is the source of the public CV landing page at renato-v-raseta.github.io.

## This repository is PUBLIC

Anyone can read every file here, and every past version of every file, forever. Deleting a file does not remove it from the history.

Never put any of these in this folder:

- an email address, a phone number, a home address
- a client name
- anything copied from elsewhere in the vault
- credentials of any kind
- a personal note of any kind

## After every session that changes anything here

1. Stage only the files this session changed, by name. **Never use `git add -A` here.** Other sessions and Obsidian drop stray files into vault folders, and on 2026-09-21 an untitled Obsidian note carrying a phone number was swept into this public repository that way.
2. Before committing, read the list of staged files out loud to yourself. If a file is not part of the web page, take it out.
3. Commit with a plain message saying what changed and why, then push.
4. Confirm there is nothing left unpushed.

## Changing the page

`index.html` holds the words, `styles.css` holds the look, `photo.jpg` is the profile photo. No build step. GitHub republishes within a minute or two.

Renato must see and approve the exact words before anything new is published here.

## Safety

- If the start-of-session check or the snapshot log reports BLOCKED, SKIPPED or an upload failure for this project, tell Renato in plain words what it says and fix the cause before other work here.
- Facts on this page also live in `40-49 Work/44 Career/Job Search 2026/Profile.md`, which is the canonical source. If a fact changes, change it there too.
