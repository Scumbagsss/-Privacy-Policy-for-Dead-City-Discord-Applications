[PRIVACY.md](https://github.com/user-attachments/files/32806470/PRIVACY.md)
# Privacy Policy for Dead City Discord Applications

**Last updated:** 29 September 2026  
**Applications covered:** DeadCity SoC MainBot ("SoC") and Bot_DC_RoleManager ("RoleManager")

This policy explains how the Dead City bot administrators ("we") process data when these applications operate in the Dead City Discord community. The person or organization responsible for the applications is **[INSERT THE OPERATOR'S LEGAL NAME]**. Privacy requests can be sent through a support ticket in the official Dead City Discord server or to [@dilarion on Telegram](https://t.me/dilarion).

Discord also processes data under [Discord's own Privacy Policy](https://discord.com/privacy). This document describes our applications' processing, including data we store outside Discord.

## 1. Data and purposes

| Application | Data processed | Purpose |
| --- | --- | --- |
| SoC | Discord user, server, role, channel and message IDs; usernames, display names, nicknames and member role changes; join, leave and other configured audit events; message text involved in edit/delete logs or configured moderation and administrative-log checks. | Member and staff authorization, server audit logs, moderation, abuse and prohibited-spawn alerts, and maintaining bot panels and workflows. |
| SoC | Ticket messages, author names, timestamps, embedded content and links to attachments; ticket and application details; event request text, scheduled times and uploaded event media; voting records; nickname and other administrative requests. | Support and administrative review, ticket transcripts, scheduling and publishing events, voting and keeping workflows available after bot restarts. |
| SoC | Priority-access request information, including Discord ID, game nickname, position, SteamID64, linked project-site account ID and the outcome of the request; role eligibility and revocation records. Quenta requests can include a submitted Google Docs link, Steam ID, review information and related ticket messages. | Checking eligibility with the project's game-site API, managing priority access, reviewing roleplay applications and keeping administrative records. |
| RoleManager | Discord IDs, names, nicknames, member and staff roles, requested role/nickname changes and moderation outcomes; the text of ordinary messages checked for configured prohibited words. | Role and nickname management, automated message moderation and staff review of possible violations. |

The applications receive data through Discord events, commands, forms, buttons and messages in channels they can access. SoC may also receive information from the project's game-site API when processing priority access. The submitted contents of a publicly accessible Google document may be retrieved for a quenta review. The applications do not ask for Discord passwords.

The current reviewed versions do not maintain a database of individual Discord presence history or a live staff-presence panel. The applications do not use the information described here for advertising or to train AI models.

## 2. Where data is kept and who can see it

SoC saves workflow information in local SQLite databases and JSON files on a Timeweb VPS. It also saves uploaded event media and can save HTML exports of ticket conversations on that VPS. Some records, including message edit/delete logs, ticket transcripts, review messages and moderation alerts, are posted to channels or direct messages within Discord. Their visibility depends on the permissions of the relevant Discord channel or recipient.

The reviewed RoleManager code does not create a separate database or local archive of member records or message text. It processes messages to apply moderation rules and may post the relevant text and incident details in a staff review channel inside Discord. Configuration files contain the IDs and settings needed for the bot to operate.

Authorized Dead City staff may view relevant requests, audit logs, moderation records and transcripts to perform their duties. Timeweb provides the VPS on which SoC is hosted. For priority access, SoC communicates with the configured project game-site API to verify or manage an account associated with a submitted SteamID64. For a submitted public Google Docs link, SoC accesses the document through Google. We do not sell Discord API data. We otherwise share it only where necessary to operate the applications, where a user directs us to do so, or where the law requires it.

## 3. Retention and deletion

There is currently **no universal automatic 30-day deletion rule** for these applications. SoC's databases, JSON state, event media and locally saved HTML ticket exports may remain for longer than 30 days. Discord-hosted audit, review and transcript messages may also remain until they are removed from the server under its moderation and retention practices. RoleManager does not intentionally save a separate local archive of moderated message text in the reviewed version.

We keep operational records only while they are needed for the stated application functions, such as active access grants, ongoing requests, moderation review, resolving disputes and recovery after a restart. We review requests to delete or correct information and remove or correct eligible data when it is no longer needed or when required by applicable law. A request concerning a multi-person ticket or moderation record may require us to remove or redact the requester's information while preserving information relating to other people or a still-active investigation. Data already posted to Discord is also subject to Discord's own systems and the server's channel permissions.

If either application stops operating, we will remove stored Discord API data as required by Discord's Developer Terms and applicable law.

## 4. Security

Staff functions use role-based permission checks, and administrative records posted in Discord are intended for channels with staff-only access. Locally stored SoC data is kept on the hosted VPS rather than in a public repository. We restrict operational access to people who need it to run or administer the applications and work to prevent unauthorized access, alteration or disclosure. We will update this policy if the storage or security arrangements materially change.

## 5. Your choices and requests

To request access to, correction of or deletion of data associated with your Discord account, open a support ticket in the official Dead City Discord server or contact [@dilarion on Telegram](https://t.me/dilarion). Include your Discord user ID and say which application or feature your request concerns. We may ask you to verify control of the account before changing or disclosing records. Do not send passwords or tokens.

The applications' server-wide moderation and audit functions do not offer an individual opt-out from checking new messages in the channels where those functions are active. You can still request deletion or correction of eligible stored data. Where applicable law gives you additional rights, including an objection to processing, you may raise them through the same contact route.

## 6. Changes

We may update this policy if application features, data practices or legal requirements change. The date at the top will show the latest revision. A public link to the current version should remain available in the applications' Discord Developer Portal entries and accessible to community members.
