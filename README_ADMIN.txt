MYSTERY Website - Private Admin Entry

CUSTOMERS: https://YOUR-DOMAIN/index.html
ADMIN: https://YOUR-DOMAIN/admin.html

The admin link is removed from the customer navigation. Admin.html is not advertised in navigation, but anyone knowing the URL can visit the login page. Supabase Auth and store_admins permissions/RLS MUST remain configured. Hiding the URL is NOT a security boundary.

Deploy the entire folder, including config.js, logo.png, and dessert images. The included config.js is browser publishable/anon configuration; NEVER use a service_role/secret key.

Sign in with your Supabase Authentication user account. Ensure its UUID is registered in public.store_admins.
