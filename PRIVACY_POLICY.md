# Street Rivals — Privacy Policy

**Last updated:** June 1, 2026  
**Effective date:** June 1, 2026

This Privacy Policy explains how **Shadowbyte Bots** (“**we**,” “**us**,” or “**our**”) collects, uses, stores, and protects information when you use **Street Rivals** (the “**Game**” or “**Service**”) on Discord.

By using Street Rivals, you agree to this Privacy Policy. If you do not agree, please do not use the Service.

---

## 1. Who We Are

**Data controller:** Shadowbyte Bots  
**Contact email:** Shadowbytebots@gmail.com  
**Location:** Sonoma County, California, United States  
**Official Discord hub:** https://discord.gg/FVGsUfZQAX (Server ID: `1511056773048438973`)

For privacy requests, data deletion, or questions: email **Shadowbytebots@gmail.com** or open a **Support** ticket on the hub via the bot’s ticket panel.

---

## 2. Scope

This policy covers:

- The Street Rivals Discord bot and slash/button interactions
- Game data we store on our servers
- Our official hub server operations (welcome messages, roles, tickets, updates)

It also applies when you use the bot on **community servers** that install Street Rivals, but those servers have their own moderators and rules. Discord itself processes data under [Discord’s Privacy Policy](https://discord.com/privacy).

---

## 3. Information We Collect

### 3.1 Information from Discord (API data)

Depending on how you use the Service, we may receive:

| Data | How we get it | Why we need it |
|------|----------------|----------------|
| **Discord user ID** | Interactions, joins, races | Link your Game account to you |
| **Display name / username** | Interactions, member events | Show names in races, leaderboards, welcomes |
| **Server (guild) ID & channel ID** | Commands, races, lobbies | Run races in the correct place |
| **Role & boost status** | Member data on our hub | Assign Street Rank roles; verify server booster perks |
| **Message content (limited)** | Only in specific cases below | See Section 4 |

We **do not** collect or use:

- Voice or video content
- Discord **Presence** (online/activity/status) — we do not request the Presence intent
- Direct messages to the bot except where you initiate support
- General chat logs from servers

### 3.2 Game data we create and store

Stored on our game servers (JSON database files), linked to your Discord user ID:

- Street Cash, XP, level, lifetime XP, rank tier
- Cars, upgrades, cosmetics, garage settings
- Race stats (wins, losses, quests, badges)
- Auto-join pass expiry and preferred auto-join car
- Guild IDs where you have raced or registered for auto-join
- Daily streak and reward claim history
- Booster perk claim dates (hub)
- Onboarding and profile preferences

### 3.3 Server & race state

For servers that use the bot, we may store:

- Open lobby and active race state (who joined, pit counts, event state)
- Server settings (pit defaults, role permissions, auto-race schedules)
- Server “bank” and hosted-race bonus settings
- Archived race result snapshots (so “View results” buttons keep working)

### 3.4 Support tickets (hub)

If you open a ticket on our official server, we may store:

- Ticket channel ID, opener user ID, ticket type, open/close timestamps
- **Ticket transcripts** that can include messages, embeds, and attachment references from the **private ticket channel only**

We do **not** archive public race-channel conversation.

### 3.5 Payment data (if you buy supporter perks)

If we offer paid subscriptions or tips, payment is handled by a third-party processor (e.g. Stripe, PayPal, Patreon). We receive confirmation of payment and your Discord identity to grant perks — **not** your full card number.

---

## 4. How We Use Message Content (Limited)

We **do not** monitor, log, or analyze general server chat.

Message content is used only in these narrow cases:

1. **Race status phrases (active races only)**  
   If you type certain short phrases during a live race (e.g. “am I still racing,” “how many pits left”), the bot reads your message **in memory**, replies once with your status, and **does not save** the message text to disk.

2. **Legacy prefix commands**  
   If you use `!` commands where enabled, the bot reads the command text to run the feature. We recommend **slash commands** (`/startrace`, `/srprofile`, etc.) instead.

3. **Ticket transcripts**  
   When a **support or prize ticket** you opened is closed, message text from that **private ticket channel** may be saved in a transcript for you (DM) and staff support.

**Opt-out:** Do not type race-status phrases (use slash commands/buttons). Do not use `!` commands. Do not open tickets if you do not want ticket-channel content in a transcript.

---

## 5. How We Use Your Information

We use collected information to:

- Operate gameplay (races, lobbies, events, payouts, quests)
- Save and restore your garage and progression
- Assign and sync Discord rank roles on our hub
- Deliver booster perks and daily rewards
- Provide support and investigate abuse
- Improve stability, fix bugs, and prevent cheating
- Post aggregate community updates (e.g. member count milestones — no sale of personal data)

We **do not**:

- Sell your personal information
- Use message content to train AI or machine learning models
- Use your data for unrelated advertising profiles

---

## 6. Legal Bases (EEA/UK users)

Where GDPR or similar law applies, we rely on:

- **Contract / service delivery** — to run the Game you use
- **Legitimate interests** — security, anti-cheat, support, hub moderation
- **Consent** — where you voluntarily open tickets or opt into optional features

You may have rights to access, correct, delete, or restrict processing — see Section 10.

---

## 7. Where Data Is Stored & Security

- Game data is stored on servers hosted by **PebbleHost** (and backups we or the host maintain).
- Data is stored as application files (e.g. JSON) on our bot instance.
- Access is limited to authorized administrators with strong credentials and panel access controls.
- We use HTTPS for Discord API communication.
- No system is 100% secure. Report suspected issues to **Shadowbytebots@gmail.com**.

**Encryption at rest:** Our hosting environment does not guarantee application-level encryption of all files. We minimize sensitive data, avoid storing general chat logs, and restrict server access.

---

## 8. How Long We Keep Data

| Data type | Typical retention |
|-----------|-------------------|
| Game account (`players.json`) | While you use the Service, or until you request deletion |
| Guild/race state | Active during events; cleared when races end |
| Race result button snapshots | Up to **90 days** |
| Ticket metadata & transcripts | As needed for support; deleted on request where possible |
| Backups | Rolling backups per host policy (may persist briefly after deletion) |

We may retain minimal records longer if required for legal compliance, fraud prevention, or dispute resolution.

---

## 9. Sharing With Others

We share information only when necessary:

- **Discord** — required to operate the bot (under Discord’s terms)
- **Hosting provider (PebbleHost)** — stores our application files
- **Payment processor** — if you purchase paid perks
- **Law enforcement** — if legally required and properly requested

We do **not** sell or rent your Discord identity or game data to marketers.

Community server staff may see your Discord name and public race activity in **their** channels when you race there; their privacy practices are separate from ours.

---

## 10. Your Rights & Choices

Depending on your location, you may have the right to:

- **Access** a copy of personal data we hold about you
- **Correct** inaccurate game-linked data
- **Delete** your game account and related ticket data
- **Object** to certain processing
- **Complain** to your local data protection authority

California residents may have additional rights under the **California Consumer Privacy Act (CCPA/CPRA)**, including the right to know what personal information we collect and to request deletion, subject to certain exceptions.

### How to request deletion or access

1. **Email:** Shadowbytebots@gmail.com — include your Discord username and user ID if possible  
2. **Support ticket:** https://discord.gg/FVGsUfZQAX → ticket panel → **Support**

We will verify you control the Discord account (e.g. ticket from that account or confirmation in email). We aim to respond within **30 days**.

Deleting game data removes your garage, cash, and stats from our active database. It may not remove messages you already posted in Discord public channels (those are controlled by Discord and server staff).

---

## 11. Children’s Privacy

Street Rivals is not directed at children under **13**. We do not knowingly collect data from anyone under 13. If you believe a child under 13 has provided data, contact **Shadowbytebots@gmail.com** and we will delete it.

---

## 12. International Users

We operate from the **United States** (Sonoma County, California). If you use the Service from other countries, your information may be processed in the United States or where our host stores data. By using the Service, you understand your data may cross borders.

---

## 13. Third-Party Links & Servers

Our hub or guides may link to YouTube, Spotify, external sites, or community servers. We are not responsible for third-party privacy practices. Read their policies before sharing information there.

---

## 14. Changes to This Policy

We may update this Privacy Policy. The “Last updated” date at the top will change, and material updates will be announced on our hub or updates channel when practical.

Continued use after changes means you accept the updated policy.

---

## 15. Contact

**Shadowbyte Bots**  
**Email:** Shadowbytebots@gmail.com  
**Location:** Sonoma County, California, United States  
**Discord:** https://discord.gg/FVGsUfZQAX — Support ticket via bot panel  

---

*Street Rivals is an independent Discord application operated by Shadowbyte Bots. This policy describes our practices only; Discord’s own Privacy Policy applies to Discord’s platform.*
