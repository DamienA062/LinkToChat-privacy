# Privacy Policy - StreamLink

**Last updated:** August 30, 2026

StreamLink ("the extension") is a browser extension that lets you send the
URL of your current tab directly to your Twitch chat. This document
explains what data the extension accesses, how it is used, and how it is
stored.

## What data we access

To connect your Twitch account, StreamLink uses Twitch's official OAuth
authorization flow. When you click "Connect," you are redirected to
Twitch's own login page, where you authorize StreamLink to:

- read your public Twitch username, to identify your connected account
- send chat messages on your behalf, only when you explicitly click
  "Send link to chat"

StreamLink also reads the URL of your active browser tab, but only at the
moment you trigger a send action (clicking the extension icon, using the
keyboard shortcut, or right-clicking "Send link to chat"). It never reads
or monitors your browsing activity outside of these moments.

## Where your data is stored

StreamLink has no backend server. There is no external server operated by
the developer, and no data is ever transmitted to the developer or to any
third party other than Twitch itself.

Your Twitch access token and your send history (the links you've sent,
with their timestamp) are stored locally in your browser, using the
standard browser extension storage API. This data:

- never leaves your device except when directly communicating with
  Twitch's own servers to authenticate you or send a chat message
- is not visible to the developer, to other extensions, or to websites
  you visit
- is permanently deleted if you uninstall the extension, or can be
  cleared at any time from the extension's settings ("Clear history")

## What we do not do

- We do not operate any server that stores or processes your data.
- We do not collect analytics, usage statistics, or tracking data of any
  kind.
- We do not sell, rent, or share your data with any third party.
- We do not access your browsing history, bookmarks, or any tab other
  than the one you are actively sending from.

## Third-party services

StreamLink communicates directly with Twitch's API (id.twitch.tv,
api.twitch.tv) to authenticate you and send chat messages. Your use of
Twitch remains subject to Twitch's own Privacy Policy and Terms of
Service: https://www.twitch.tv/p/legal/privacy-notice/

## Revoking access

You can disconnect StreamLink from your Twitch account at any time,
either from the extension's settings, or directly from your Twitch
account: https://www.twitch.tv/settings/connections

## Contact

Questions about this policy can be sent to: 
