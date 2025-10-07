## 2025-10-05 — ITM Discord: roles, channels, onboarding (v1)
**Why:** Activity dipped after merging to one channel; want higher signal and a path for premium without hiding the community.
**Outcome:**
- Role‑gated visibility via short onboarding; members can re-run it anytime.
- Enable “Apply to Join” for **new** members (existing stay).
- **Premium** category (initial):
  - `#premium-announcements` (read‑only)
  - `#itm-options-trades` (read‑only)
  - `#community-trades` (discussion)
  - `#ask-me-anything` (tentative in premium; we’ll test)
- **General:** keep `#general`; drop `#off-topic-lounge` to reduce duplication.
- **Analysis & Tools:** add Robinhood forum/channel for FAQs.
- **Learning:** `#faq-and-guides` (tagged; Adam to help seed).
- **Community:** `#off-topic`, add `#sports-bets` (incl. binaries).
- **Archives:** add an Archived category; move legacy channels there.
- **Moderation:** expand volunteer mod pool; push casual talk to `#off-topic`.
- **Challenges:** monthly paper‑trading comp with leaderboard + vanity role; prize = 1 mo. premium/AutoPilot/Patreon (TBD). Note: most bots are equities‑only; options support sparse.

|Role|Description|
|---|---|
|@Admin|Owners/co-owners (full control)|
|@Moderator|Moderation staff|
|@Bot|Automations and feeds|
|@Verified|Completed onboarding & accepted rules|
|@Trusted|Members with a good track record, gives access to #live-trading-voice|
|@Options|Interest role: options|
|@Stocks|Interest role: stocks|
|@Crypto|Interest role: crypto|
|@Off-Topic|Opt-in off-topic access|
|@Historian|Opt-in archive access (read only)|
|@Event Host|Hosts for Stage/Events|
|@Stage Speaker|Pre-approved speakers|
|@Muted|No send permissions|

**Links:**  
Interactive map: https://five-to-midnight.github.io/itm-discord/  
Working files: https://drive.google.com/drive/folders/1hhLF5MIDCpK8tAzqB_g7wgg-mKNJIGui?usp=sharing

**Owners:** Adam (@inthemoney), Denzalo, Eric (@OutoftheMoney)

**Next:**  
- Implement roles/channels + onboarding + Archived category. *(Denzalo)*  
- Draft “Apply to Join” questions. *(Adam)*  
- Bot shortlist for challenges; pick one. *(Denzalo)*  
- Seed initial FAQ entries. *(Adam)*

## 2025-10-06
* Decided to go with layered approach to Roles management
* @Verified is the "base" layer with the minimum permissions
* Other layers add permissions on top of @Verified without duplicating permissions

### Migration Instructions
* When it's time to migrate the server - the @everyone role needs to be wiped out of all permissions so we can move people through the @Verified funnel
* Category: Welcome & Onboarding
  * Flip Private to Public
  * Give @everyone View Channels (maybe also message history?)
* Category: Information & Announcements
  * Flip Private to Public
  * Give @everyone View Channels (maybe also message history?)
* Category: Events & Live
  * Flip Private to Public
  * Give @everyone View Channels (maybe also message history?)
* Still need to create a Premium role and gate it to Premium payers


GIve any bots the @Verified role as well if they need to type?
* No. Give specific laser focus permissions only where needed
