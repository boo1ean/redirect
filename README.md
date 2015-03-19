# redirect
Redirect service flow

## Redirection flow

1. Identify redirect scope (campaign id or something).
2. Figure out redirect conditions and variants.
3. Get user data based on request for conditions matching (ip, user agent, cookies, session data, etc.).
4. Match conditions and figure out which variant to use for redirect.
5. Track redirect.
6. Save user session data.
7. Redirect user.
