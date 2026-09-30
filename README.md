# website-migration
Website Migration HQ: the tracker for moving mismo.org from Sitefinity to Higher Logic.
Live at https://resources.mismo.org/website-migration/ (sign-in required).

The records live in the private `website-migration-data` repo and are saved through the
resources.mismo.org relay under the project key `website-migration`. No token or secret is
ever kept in this repo.

Who can do what:
- **Admin**: change everything, add and delete.
- **Staff**: add tasks, and edit tasks where they are the Owner. Everything else is read-only.
  (The relay lets staff save; the own-tasks rule is kept by the page.)
- **View**: read-only.

Before uploading a new copy of index.html, download the current one from GitHub first and
make changes to that copy, so nothing that changed since is undone.
