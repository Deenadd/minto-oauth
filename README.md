# minto-oauth

The redirect page for signing in to Minto with Slack.

Slack requires an HTTPS address to send you back to after you approve access.
This page is that address: it takes the result and hands it straight to the
Minto app on your Mac through a `minto://` link. It holds no secrets and stores
nothing.
