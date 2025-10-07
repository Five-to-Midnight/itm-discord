

> **Legend for overrides table**
>
> * **ALLOW / DENY** = explicit channel overwrite
> * **—** = no channel overwrite (inherits from roles / category)
> * Only roles with at least one explicit overwrite appear in a given table

---

# Channels.md

> Baseline: `@Verified` is the member base; gating roles unlock categories; `@Trusted` adds perks; staff roles add moderation. Channel tables below only show **overrides** needed to make a channel behave differently from the baseline.

---

## Welcome & Onboarding

### #server-guide  *(Text • public read‑only)*  

**Overview (Text channel options)**

| Option                | Value                                  |
| --------------------- | -------------------------------------- |
| Channel Topic         | Welcome, mission, new‑member checklist |
| Slowmode              | Off                                    |
| Age‑Restricted        | Off                                    |
| Hide After Inactivity | 3 Days                                 |

**Permissions — Overrides only**

| Permission                         | @everyone | @Moderator | @Admin    |
| ---------------------------------- | --------- | ---------- | --------- |
| View Channel                       | **ALLOW** | —          | —         |
| Read Message History               | **ALLOW** | —          | —         |
| Send Messages and Create Posts     | **DENY**  | **ALLOW**  | **ALLOW** |
| Send Messages in Threads and Posts | **DENY**  | **ALLOW**  | **ALLOW** |
| Create Public Threads              | **DENY**  | **ALLOW**  | **ALLOW** |
| Create Private Threads             | **DENY**  | **ALLOW**  | **ALLOW** |

> Rationale: keep it truly read‑only except staff edits; baseline `@Verified` sending is suppressed via @everyone **DENY** and staff **ALLOW**.

---

### #rules  *(Text • public read‑only)*  

**Overview**

| Option                | Value                                  |
| --------------------- | -------------------------------------- |
| Channel Topic         | 10–16 short rules; link to full policy |
| Slowmode              | Off                                    |
| Age‑Restricted        | Off                                    |
| Hide After Inactivity | 3 Days                                 |

**Permissions — Overrides only**

| Permission                         | @everyone | @Moderator | @Admin    |
| ---------------------------------- | --------- | ---------- | --------- |
| View Channel                       | **ALLOW** | —          | —         |
| Read Message History               | **ALLOW** | —          | —         |
| Send Messages and Create Posts     | **DENY**  | **ALLOW**  | **ALLOW** |
| Send Messages in Threads and Posts | **DENY**  | **ALLOW**  | **ALLOW** |
| Create Public Threads              | **DENY**  | **ALLOW**  | **ALLOW** |
| Create Private Threads             | **DENY**  | **ALLOW**  | **ALLOW** |

---

### #introductions  *(Text • public chat)*  

**Overview**

| Option                | Value                       |
| --------------------- | --------------------------- |
| Channel Topic         | Quick intro template pinned |
| Slowmode              | Off                         |
| Age‑Restricted        | Off                         |
| Hide After Inactivity | 3 Days                      |

**Permissions — Overrides only**

| Permission                     | @everyone |
| ------------------------------ | --------- |
| View Channel                   | **ALLOW** |
| Read Message History           | **ALLOW** |
| Send Messages and Create Posts | **DENY**  |

> Members post via `@Verified` baseline; @everyone can read during onboarding.

---

## Information & Announcements

### #announcements  *(Announcement)*  

**Overview (Announcement options)**

| Option                | Value                     |
| --------------------- | ------------------------- |
| Channel Topic         | New videos, major updates |
| Age‑Restricted        | Off                       |
| Announcement Channel  | **On**                    |
| Hide After Inactivity | 3 Days                    |

**Permissions — Overrides only**

| Permission                         | @everyone | @Verified | @Moderator | @Admin    | @Bot      |
| ---------------------------------- | --------- | --------- | ---------- | --------- | --------- |
| View Channel                       | **ALLOW** | —         | —          | —         | —         |
| Read Message History               | **ALLOW** | —         | —          | —         | —         |
| Send Messages and Create Posts     | **DENY**  | **DENY**  | **ALLOW**  | **ALLOW** | **ALLOW** |
| Send Messages in Threads and Posts | **DENY**  | **DENY**  | **ALLOW**  | **ALLOW** | **ALLOW** |
| Create Public Threads              | **DENY**  | **DENY**  | **ALLOW**  | **ALLOW** | **ALLOW** |
| Create Private Threads             | **DENY**  | **DENY**  | **ALLOW**  | **ALLOW** | **ALLOW** |

---

### #calendar-of-events  *(Text • public read‑only)*  

**Overview**

| Option                | Value                      |
| --------------------- | -------------------------- |
| Channel Topic         | Scheduled livestreams/AMAs |
| Slowmode              | Off                        |
| Age‑Restricted        | Off                        |
| Hide After Inactivity | 3 Days                     |

**Permissions — Overrides only**

| Permission                     | @everyone | @Verified | @Event Host | @Bot      |
| ------------------------------ | --------- | --------- | ----------- | --------- |
| View Channel                   | **ALLOW** | —         | —           | —         |
| Read Message History           | **ALLOW** | —         | —           | —         |
| Send Messages and Create Posts | **DENY**  | **DENY**  | **ALLOW**   | **ALLOW** |

---

### #faq-and-guides  *(Text • public read‑only)*  

**Overview**

| Option                | Value                           |
| --------------------- | ------------------------------- |
| Channel Topic         | Options basics, risk checklists |
| Slowmode              | Off                             |
| Age‑Restricted        | Off                             |
| Hide After Inactivity | 3 Days                          |

**Permissions — Overrides only**

| Permission                     | @everyone | @Moderator | @Admin    |
| ------------------------------ | --------- | ---------- | --------- |
| View Channel                   | **ALLOW** | —          | —         |
| Read Message History           | **ALLOW** | —          | —         |
| Send Messages and Create Posts | **DENY**  | **ALLOW**  | **ALLOW** |

---

## Trading Floor — Live & Voice

### Live‑Trading Voice  *(Voice)*  

**Overview (Voice options)**

| Option                | Value                                             |
| --------------------- | ------------------------------------------------- |
| Slowmode (voice text) | Off                                               |
| Age‑Restricted        | Off                                               |
| Bitrate               | **96 kbps** (use 64 if users on poor connections) |
| Video Quality         | Auto                                              |
| User Limit            | ∞                                                 |
| Region Override       | Automatic                                         |

**Permissions — Overrides only**

| Permission       | @everyone | @Verified | @Event Host |
| ---------------- | --------- | --------- | ----------- |
| View Channel     | **ALLOW** | —         | —           |
| Connect          | —         | **ALLOW** | —           |
| Speak            | —         | **ALLOW** | —           |
| Video            | —         | **ALLOW** | —           |
| Use Soundboard   | —         | **DENY**  | —           |
| Priority Speaker | —         | —         | **ALLOW**   |

---

## Options

### #options-discussion  *(Text • private; gated by @Options)*  

**Overview**

| Option                | Value                                     |
| --------------------- | ----------------------------------------- |
| Channel Topic         | Strategy talk; actionable but educational |
| Slowmode              | 5–15s during volatility (otherwise Off)   |
| Age‑Restricted        | Off                                       |
| Hide After Inactivity | 3 Days                                    |

**Permissions — Overrides only**

| Permission   | @everyone |
| ------------ | --------- |
| View Channel | **DENY**  |

> Gating handled by category; no other channel override needed.

---

### Options Forum  *(Forum • private; gated by @Options)*  

**Overview (Forum options)**

| Option                | Value                                                       |
| --------------------- | ----------------------------------------------------------- |
| Post Guidelines       | Template for ticker/strategy/thesis/risk                    |
| Tags                  | Spreads, Straddles/Strangles, Earnings, Risk Mgmt, Newbie Q |
| Require Tag to Post   | **On**                                                      |
| Default Reaction      | 👍                                                          |
| Slowmode – Posts      | Off                                                         |
| Slowmode – Messages   | Off                                                         |
| Default Layout        | List                                                        |
| Sort Order            | Recent Activity                                             |
| Tag Matching          | Match Some                                                  |
| Age‑Restricted        | Off                                                         |
| Hide After Inactivity | 3 Days                                                      |

**Permissions — Overrides only**

| Permission   | @everyone |
| ------------ | --------- |
| View Channel | **DENY**  |

*(Posting rights come from `@Options` + `@Verified`; no extra overwrite needed.)*

---

### #flow-alerts  *(Text • private; gated by @Options)*  

**Overview**

| Option                | Value                         |
| --------------------- | ----------------------------- |
| Channel Topic         | Unusual options activity feed |
| Slowmode              | Off                           |
| Age‑Restricted        | Off                           |
| Hide After Inactivity | 3 Days                        |

**Permissions — Overrides only**

| Permission                         | @everyone | @Options  | @Bot      |
| ---------------------------------- | --------- | --------- | --------- |
| View Channel                       | **DENY**  | —         | —         |
| Send Messages and Create Posts     | —         | **DENY**  | **ALLOW** |
| Send Messages in Threads and Posts | —         | **ALLOW** | **ALLOW** |
| Embed Links                        | —         | —         | **ALLOW** |
| Attach Files                       | —         | —         | **ALLOW** |

> Members discuss in **threads**; the parent channel stays feed‑only.

---

## Stocks

### #stocks-discussion *(Text • private; gated by @Stocks)*  

**Overview**

| Option                | Value                           |
| --------------------- | ------------------------------- |
| Channel Topic         | Stocks chat (catalysts, thesis) |
| Slowmode              | Off                             |
| Age‑Restricted        | Off                             |
| Hide After Inactivity | 3 Days                          |

**Permissions — Overrides only**

| Permission   | @everyone |
| ------------ | --------- |
| View Channel | **DENY**  |

---

### Stocks Forum *(Forum • private; gated by @Stocks)*  

**Overview**

| Option                | Value                                    |
| --------------------- | ---------------------------------------- |
| Post Guidelines       | Stock idea template (thesis/risk/levels) |
| Tags                  | Earnings, Momentum, Value, Long‑term     |
| Require Tag to Post   | **On**                                   |
| Default Reaction      | 👍                                       |
| Slowmode – Posts      | Off                                      |
| Slowmode – Messages   | Off                                      |
| Default Layout        | List                                     |
| Sort Order            | Recent Activity                          |
| Tag Matching          | Match Some                               |
| Age‑Restricted        | Off                                      |
| Hide After Inactivity | 3 Days                                   |

**Permissions — Overrides only**

| Permission   | @everyone |
| ------------ | --------- |
| View Channel | **DENY**  |

---

## Crypto (optional)

### #crypto-talk *(Text • private; gated by @Crypto)*  

**Overview**

| Option                | Value                       |
| --------------------- | --------------------------- |
| Channel Topic         | High‑risk disclosure pinned |
| Slowmode              | Off                         |
| Age‑Restricted        | Off                         |
| Hide After Inactivity | 3 Days                      |

**Permissions — Overrides only**

| Permission   | @everyone |
| ------------ | --------- |
| View Channel | **DENY**  |

---

## Analysis & Tools

### #charts-and-analysis *(Media • public)*  

**Overview (Media options)**

| Option                   | Value                                          |
| ------------------------ | ---------------------------------------------- |
| Post Guidelines          | One image + one thesis; use threads to discuss |
| Tags                     | (optional)                                     |
| Default Reaction         | 👍                                             |
| Messages Slowmode        | Off                                            |
| Sort Order               | Recent Activity                                |
| Tag Matching             | Match Some                                     |
| Age‑Restricted           | Off                                            |
| Hide After Inactivity    | 3 Days                                         |
| Save/Copy Embedded Media | **On**                                         |

**Permissions — Overrides only**

| Permission           | @everyone |
| -------------------- | --------- |
| View Channel         | **ALLOW** |
| Read Message History | **ALLOW** |

> Posting uses `@Verified` baseline; no extra overwrite.

---

### #macro-news *(Text • public)*  

**Overview**

| Option                | Value                    |
| --------------------- | ------------------------ |
| Channel Topic         | Macro calendar, CPI/FOMC |
| Slowmode              | Off                      |
| Age‑Restricted        | Off                      |
| Hide After Inactivity | 3 Days                   |

**Permissions — Overrides only**

| Permission                     | @everyone | @Bot      |
| ------------------------------ | --------- | --------- |
| View Channel                   | **ALLOW** | —         |
| Read Message History           | **ALLOW** | —         |
| Send Messages and Create Posts | **DENY**  | **ALLOW** |
| Embed Links                    | —         | **ALLOW** |

---

### TradingView Forum *(Forum • public)*  

**Overview**

| Option                | Value                            |
| --------------------- | -------------------------------- |
| Post Guidelines       | Tool tips, indicator lists       |
| Tags                  | Indicators, Pine Script, Layouts |
| Require Tag to Post   | **On**                           |
| Default Reaction      | 👍                               |
| Slowmode – Posts      | Off                              |
| Slowmode – Messages   | Off                              |
| Default Layout        | List                             |
| Sort Order            | Recent Activity                  |
| Tag Matching          | Match Some                       |
| Age‑Restricted        | Off                              |
| Hide After Inactivity | 3 Days                           |

**Permissions — Overrides only**

| Permission           | @everyone |
| -------------------- | --------- |
| View Channel         | **ALLOW** |
| Read Message History | **ALLOW** |

---

### ThinkOrSwim Forum *(Forum • public)*  

*(Same as TradingView Forum; View + Read for @everyone explicitly ALLOW.)*

---

## Community & Off‑Topic

### #general *(Text • public)*  

**Overview**

| Option                | Value                     |
| --------------------- | ------------------------- |
| Channel Topic         | Day‑to‑day chat           |
| Slowmode              | Off (raise during spikes) |
| Age‑Restricted        | Off                       |
| Hide After Inactivity | 3 Days                    |

**Permissions — Overrides only**

| Permission           | @everyone |
| -------------------- | --------- |
| View Channel         | **ALLOW** |
| Read Message History | **ALLOW** |

---

### #off-topic-lounge / #fitness / #gaming / #music *(Text • private; gated by @Off‑Topic)*  

**Overview (each)**

| Option                | Value    |
| --------------------- | -------- |
| Channel Topic         | As named |
| Slowmode              | Off      |
| Age‑Restricted        | Off      |
| Hide After Inactivity | 3 Days   |

**Permissions — Overrides only**

| Permission   | @everyone |
| ------------ | --------- |
| View Channel | **DENY**  |

---

### Casual Voice 1 / Casual Voice 2 *(Voice • private; gated by @Off‑Topic)*  

**Overview (each)**

| Option                | Value      |
| --------------------- | ---------- |
| Slowmode (voice text) | Off        |
| Age‑Restricted        | Off        |
| Bitrate               | 64–96 kbps |
| Video Quality         | Auto       |
| User Limit            | ∞          |
| Region Override       | Automatic  |

**Permissions — Overrides only**

| Permission     | @everyone | @Trusted  | @Server Booster |
| -------------- | --------- | --------- | --------------- |
| View Channel   | **DENY**  | —         | —               |
| Use Soundboard | —         | **ALLOW** | **ALLOW**       |

---

### #ask-me-anything *(Forum • public)*  

**Overview**

| Option                | Value                               |
| --------------------- | ----------------------------------- |
| Post Guidelines       | Question format; one topic per post |
| Tags                  | Content, Strategy, Life, Tools      |
| Require Tag to Post   | **On**                              |
| Default Reaction      | 👍                                  |
| Slowmode – Posts      | Off                                 |
| Slowmode – Messages   | Off                                 |
| Default Layout        | List                                |
| Sort Order            | Recent Activity                     |
| Tag Matching          | Match Some                          |
| Age‑Restricted        | Off                                 |
| Hide After Inactivity | 3 Days                              |

**Permissions — Overrides only**

| Permission           | @everyone |
| -------------------- | --------- |
| View Channel         | **ALLOW** |
| Read Message History | **ALLOW** |

---

## Events & Engagement

### InTheMoney Live *(Stage • public)*  

**Overview (Stage options)**

| Option                | Value   |
| --------------------- | ------- |
| Slowmode (stage chat) | Off     |
| Age‑Restricted        | Off     |
| Bitrate               | 64 kbps |
| Video Quality         | Auto    |
| User Limit            | 10,000  |

**Permissions — Overrides only**

| Permission         | @everyone | @Verified | @Event Host | @Stage Speaker |
| ------------------ | --------- | --------- | ----------- | -------------- |
| View Channel       | **ALLOW** | —         | —           | —              |
| Request to Speak   | —         | **ALLOW** | —           | —              |
| Start/Manage Stage | —         | —         | **ALLOW**   | —              |
| Speak on Stage     | —         | —         | **ALLOW**   | **ALLOW**      |

---

### #stage-chat *(Text • public)*  

**Overview**

| Option                | Value                          |
| --------------------- | ------------------------------ |
| Channel Topic         | Questions & links during Stage |
| Slowmode              | Off                            |
| Age‑Restricted        | Off                            |
| Hide After Inactivity | 3 Days                         |

**Permissions — Overrides only**

| Permission           | @everyone |
| -------------------- | --------- |
| View Channel         | **ALLOW** |
| Read Message History | **ALLOW** |

---

### #polls *(Text • public)*  

**Overview**

| Option                | Value                       |
| --------------------- | --------------------------- |
| Channel Topic         | Polls for topics/challenges |
| Slowmode              | Off                         |
| Age‑Restricted        | Off                         |
| Hide After Inactivity | 3 Days                      |

**Permissions — Overrides only**

| Permission           | @everyone | @Verified |
| -------------------- | --------- | --------- |
| View Channel         | **ALLOW** | —         |
| Read Message History | **ALLOW** | —         |
| Create Polls         | —         | **ALLOW** |

---

### #challenges *(Forum • public)*  

**Overview**

| Option                | Value                          |
| --------------------- | ------------------------------ |
| Post Guidelines       | Paper‑trading challenge format |
| Tags                  | P/L, Risk‑adjusted, Journal    |
| Require Tag to Post   | **On**                         |
| Default Reaction      | 👍                             |
| Slowmode – Posts      | Off                            |
| Slowmode – Messages   | Off                            |
| Default Layout        | List                           |
| Sort Order            | Recent Activity                |
| Tag Matching          | Match Some                     |
| Age‑Restricted        | Off                            |
| Hide After Inactivity | 3 Days                         |

**Permissions — Overrides only**

| Permission           | @everyone |
| -------------------- | --------- |
| View Channel         | **ALLOW** |
| Read Message History | **ALLOW** |

---

## Archive (Read‑Only) — via `@Historian`  

*(Each archived text channel below uses the same overrides.)*

**Overview (each)**

| Option                | Value                  |
| --------------------- | ---------------------- |
| Channel Topic         | “LEGACY … (read‑only)” |
| Slowmode              | Off                    |
| Age‑Restricted        | Off                    |
| Hide After Inactivity | 3 Days                 |

**Permissions — Overrides only (each archived channel)**

| Permission                         | @Historian | @Moderator | @Admin    | @everyone |
| ---------------------------------- | ---------- | ---------- | --------- | --------- |
| View Channel                       | **ALLOW**  | —          | —         | **DENY**  |
| Read Message History               | **ALLOW**  | —          | —         | —         |
| Send Messages and Create Posts     | **DENY**   | **ALLOW**  | **ALLOW** | **DENY**  |
| Send Messages in Threads and Posts | **DENY**   | **ALLOW**  | **ALLOW** | **DENY**  |
| Create Public Threads              | **DENY**   | **ALLOW**  | **ALLOW** | **DENY**  |
| Create Private Threads             | **DENY**   | **ALLOW**  | **ALLOW** | **DENY**  |

> Applies to: `#stock-discussion`, `#earnings`, `#income-investing`, `#crypto`, `#in-the-news`, `#options-discussion (archived)`, `#bullish`, `#bearish`, `#strategies`, `#the-wheel`.

---

## Moderation, Safety & Ops (Private)  

### #mod-chat *(Text • staff)*

**Overview**

| Option                | Value                   |
| --------------------- | ----------------------- |
| Topic                 | Day‑to‑day coordination |
| Slowmode              | Off                     |
| Age‑Restricted        | Off                     |
| Hide After Inactivity | 3 Days                  |

**Permissions — Overrides only**

| Permission                     | @Admin    | @Moderator |
| ------------------------------ | --------- | ---------- |
| View Channel                   | **ALLOW** | **ALLOW**  |
| Send Messages and Create Posts | **ALLOW** | **ALLOW**  |

---

### #admin-chat *(Text • admins only)*

**Overview**

| Option                | Value                       |
| --------------------- | --------------------------- |
| Topic                 | Owner/co‑owner private room |
| Slowmode              | Off                         |
| Age‑Restricted        | Off                         |
| Hide After Inactivity | 3 Days                      |

**Permissions — Overrides only**

| Permission                     | @Admin    | @Moderator |
| ------------------------------ | --------- | ---------- |
| View Channel                   | **ALLOW** | **DENY**   |
| Send Messages and Create Posts | **ALLOW** | **DENY**   |
| Read Message History           | **ALLOW** | **DENY**   |

---

### #mod-log *(Text • staff + bot)*

**Overview**

| Option                | Value                |
| --------------------- | -------------------- |
| Topic                 | AutoMod + audit feed |
| Slowmode              | Off                  |
| Age‑Restricted        | Off                  |
| Hide After Inactivity | 3 Days               |

**Permissions — Overrides only**

| Permission                     | @Admin    | @Moderator | @Bot      |
| ------------------------------ | --------- | ---------- | --------- |
| View Channel                   | **ALLOW** | **ALLOW**  | **ALLOW** |
| Send Messages and Create Posts | **DENY**  | **DENY**   | **ALLOW** |
| Embed Links                    | —         | —          | **ALLOW** |
| Attach Files                   | —         | —          | **ALLOW** |
| Read Message History           | **ALLOW** | **ALLOW**  | **ALLOW** |

---

### #mod-mail *(Text • staff)*

**Overview**

| Option                | Value             |
| --------------------- | ----------------- |
| Topic                 | Reports & appeals |
| Slowmode              | Off               |
| Age‑Restricted        | Off               |
| Hide After Inactivity | 3 Days            |

**Permissions — Overrides only**

| Permission                     | @Admin    | @Moderator |
| ------------------------------ | --------- | ---------- |
| View Channel                   | **ALLOW** | **ALLOW**  |
| Send Messages and Create Posts | **ALLOW** | **ALLOW**  |

---

### #bot-commands *(Text • semi‑private)*

**Overview**

| Option                | Value                    |
| --------------------- | ------------------------ |
| Topic                 | Keep bot noise contained |
| Slowmode              | Off                      |
| Age‑Restricted        | Off                      |
| Hide After Inactivity | 3 Days                   |

**Permissions — Overrides only**

| Permission                     | @Verified | @Bot      |
| ------------------------------ | --------- | --------- |
| View Channel                   | **ALLOW** | **ALLOW** |
| Send Messages and Create Posts | **ALLOW** | **ALLOW** |
| Embed Links                    | —         | **ALLOW** |
| Attach Files                   | —         | **ALLOW** |

---

## Premium (private; future `@Premium` role)  

### #premium-announcements *(Announcement • private)*

**Overview**

| Option                | Value                   |
| --------------------- | ----------------------- |
| Channel Topic         | Updates for subscribers |
| Age‑Restricted        | Off                     |
| Announcement Channel  | On                      |
| Hide After Inactivity | 3 Days                  |

**Permissions — Overrides only**

| Permission                     | @Premium  | @Admin    | @Moderator | @everyone |
| ------------------------------ | --------- | --------- | ---------- | --------- |
| View Channel                   | **ALLOW** | **ALLOW** | **ALLOW**  | **DENY**  |
| Send Messages and Create Posts | **DENY**  | **ALLOW** | **ALLOW**  | **DENY**  |
| Read Message History           | **ALLOW** | **ALLOW** | **ALLOW**  | —         |

---

### How to use this file
* When you add a bot or a premium role, insert that role into the specific channel tables and mark only the needed **ALLOW/DENY** overwrites.
* For any channel not explicitly listed above, it inherits the category gates and the layered role defaults from `Roles.md` (no extra overwrites needed).
