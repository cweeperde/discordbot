# Botanaki Privacy Policy

**Last updated:** September 23, 2026

## 1. Operator and contact

The controller for data processing carried out by Botanaki is the bot's operator, known on Discord as **cweeper**. Bot data is hosted in Germany.

For privacy questions, access, correction, or deletion requests, email [botanaki@cweeper.simplelogin.com](mailto:botanaki@cweeper.simplelogin.com) or contact **cweeper** on Discord. Include the relevant user or server ID so the records can be located.

## 2. Data and purposes

Depending on the features used or enabled in a server, Botanaki processes:

- **Discord and configuration data:** User, server, channel, role, and message IDs; names and profile images; permissions and server settings needed to run the configured features.
- **Community features:** XP, levels, counting and starboard records, role settings, optional birthdays (including a year if supplied), and reminder text and delivery details.
- **Moderation and support:** Reports, moderator notes, ticket records, anonymous-ticket messages, audit-log actions, feedback, and appeals, including associated IDs, text, status, and timestamps.
- **Operation and abuse prevention:** Command and error logs, usage counts, global bans, appeal restrictions, cooldowns, and server-owner IDs used to check appeals.

These data come from Discord, your submissions, and other server members or administrators using the relevant features. They are used to provide those features, maintain settings, handle support and appeals, diagnose failures, and prevent abuse.

Optional submissions are voluntary. Without the information required for a particular feature, that feature cannot be provided.

## 3. Message content and visibility

Botanaki does not keep a general archive of all chat messages. The following features process or copy content:

- Chat and invite filters inspect messages locally. Enabled moderation logs may copy an excerpt of a removed message to the server's logging channel.
- Starboards repost selected messages, author details, and attachment links.
- Ticket transcripts read ticket history and are sent through Discord. Anonymous-ticket messages are also stored in the bot database; the ticket creator's ID is retained, so these tickets are not anonymous to the Operator.
- Reports, notes, reminders, feedback, and appeals store or transmit the submitted text. Feedback and appeals are sent to the Operator's configured Discord channel.

Server members or moderators can see bot output according to the destination channel's permissions. Server administrators choose settings and manage access to their channels. Profile images and generated cards are processed in memory; temporary caches support bot operation.

## 4. External services

- **Discord** receives bot messages, logs, attachments, and other feature output. Its own processing is described in [Discord's Privacy Policy](https://discord.com/privacy).
- **OpenWeather** receives the location entered in `/weather` to return weather information. Botanaki does not include your Discord user ID in that request. See [OpenWeather's Privacy Policy](https://openweather.co.uk/privacy-policy).

Local message filtering does not send message content to an external filtering service. Personal data is not sold or used for targeted advertising.

## 5. Retention

- Server settings and feature records remain until removed through available commands, administration, or server cleanup. Successfully delivered or cancelled reminders are deleted.
- After Botanaki leaves a server, ordinary server feature data is kept for **30 days** to allow restoration. Re-adding the bot cancels cleanup if the server is not banned. Cleanup runs every six hours while the bot is operating, so deletion is not instantaneous.
- The active audit archive uses a **30-day** retention setting with periodic cleanup. Exported audit files and operational logs rotate by size and can remain longer.
- Ban and appeal restrictions, ownership records, and submission cooldown records have no fixed automatic expiry. Migration backups also remain until manually removed. These records are not all covered by the 30-day server cleanup.
- Local deletion does not automatically remove messages, attachments, transcripts, or reposts already sent to Discord. Those copies require separate handling through Discord and the relevant server or Operator.

You can request deletion without waiting for server removal or the 30-day period. Any legally required retention and any remaining copies must be addressed when handling the request.

## 6. Updates

This policy will be updated when data practices change. The date above identifies the latest revision.
