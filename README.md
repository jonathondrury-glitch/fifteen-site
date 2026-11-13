# Fifteen website (studyfifteen.com)

The public landing page for Fifteen. One file, `index.html`, served by Vercel as it is (no build step).
The app itself lives in the separate `fifteen` repository.

Sign-ups from the form go into the `early_access` table in Fifteen's Supabase project
(set up by `supabase/migrations/004_early_access.sql` in the app repository).
To see them: Supabase → Table Editor → early_access.
