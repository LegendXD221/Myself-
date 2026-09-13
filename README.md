# Knight Hub V2
A polished animated Linktree-style personal hub with Supabase admin control.

1. Run supabase.sql in Supabase SQL Editor.
2. Create your Auth user.
3. Insert its UUID into public.profiles with is_admin=true.
4. Put your Supabase Project URL and public anon/publishable key in BOTH index.html and admin.html.
5. Deploy the folder to Netlify or Cloudflare Pages.
6. Open /admin.html to manage profile, sections, links and downloads.

Never put a Supabase service-role/secret key in the frontend.